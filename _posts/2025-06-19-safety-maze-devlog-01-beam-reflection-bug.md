---
title: "Safety Maze Devlog #1 – The Great Beam Reflection Bug"
layout: single
date: 2025-06-19
author: Cameron Bartholome
categories: [safety-maze, reflections, debugging]
---

# 🔁 Bouncing Beams and Misbehaving Mazes: Debugging Reflections in Python

---

Ever tried to make a laser beam bounce off walls inside a 2D maze, only to watch it hit the first wall and... just stop? Yeah. That’s what happened.

Welcome to the world of **Safety Maze**, my Python app where lasers meet geometry — and bugs meet determination.

---

## 🚧 The Problem

We had a beam.

We had a maze.

We had a single bounce.

**That’s it.**

Despite planning for full beam reflection through a maze, the simulation hit one wall and just called it a day. “I’ve done enough,” said the beam. “I’m out.”

We needed to:
- Calculate multiple reflections
- Respect the laws of physics (you know... angle in = angle out)
- Not bounce the beam *through* the maze walls like a chaotic pinball

---

## 🧠 The Plan

To fix this, we planned to:
1. Rewrite the `trace_beam_path()` function
2. Log every bounce:
    - Start point
    - Hit point
    - Incoming angle
    - Outgoing angle
3. Save everything to a CSV or Excel file for inspection and debugging
4. Update the GUI to **read from that file** and draw the beam path

Now we’d be able to actually **see** what’s going wrong (and right) — and adjust without guesswork.

---

## 🔍 Why Log to File?

Because looking at beam data like this:

```python
[(100, 325), (200, 300), (400, 100), ...]
```

...gets old fast. Saving to a CSV gives you:

| start_x | start_y | hit_x | hit_y | angle_in | angle_out |
|---------|---------|-------|-------|----------|-----------|
| 100     | 325     | 200   | 300   | 45°      | 315°      |

Now *that’s* something I can debug. Or plot. Or cry over, if it still fails.

---

## 🧪 The Current Status

We fixed the logic, and the beam now:
- Starts from the correct location
- Hits the first wall correctly
- Reflects… and that’s it (for now)

So we wrote a full plan for the new version. Tomorrow, we’ll:
- Implement full bounce tracing
- Record every bounce in a file
- Plot it on the canvas from that file

---

## 🧘‍♂️ Lessons Learned

- If your beam is acting up, make it log everything.
- Never trust a red line until it’s been through Excel.
- And don’t worry — tomorrow, we bounce properly.

---

Stay tuned for Part 2: *Return of the Reflections™*.
