---
title: "Building Safety Maze: From Sketch to Simulation"
layout: single
date: 2025-06-25
author: Cameron Bartholome
categories: [safety-maze, devlog, simulation]
---

# 🌀 Building Safety Maze: From Sketch to Simulation

It started with a sketch and a simple question:  
**"Can I simulate a laser safely bouncing through a labyrinth?"**

Welcome to the *Safety Maze* project — a chaotic mix of math, canvas code, and occasionally yelling at angles.

## ✍️ Step 1: Sketching the Idea

Like most of my side projects, it began with a scribble on paper.  
A maze. A laser. A dream.

The goal?  
- Visualize the beam path
- Prove it won’t escape
- Maybe avoid setting fire to imaginary walls

## 🧱 Step 2: Building the Base

Tools I grabbed:
- Python + tkinter (because why not)
- Maze presets as wall segments
- A canvas to draw the chaos

First version?  
It drew one line. And that’s it.  
Confidence: 100%. Reality: 0%.

## 🔁 Step 3: Getting the Beam to Reflect

This is where things got spicy.

“Angle in equals angle out,” they said.  
Sure — until you forget that tkinter’s Y-axis is upside down and your beam starts moonwalking off-screen.

Eventually:
- I used `shapely` to detect wall collisions
- Calculated surface normals to bounce the beam
- Drew red lines and blue dots like I was charting UFO sightings

## 📊 Step 4: Visual Feedback + Logging

Turns out staring at the screen waiting for a beam to “feel right” isn’t very scientific.

So I added:
- Blue dots = hit points
- Green dot = start point
- CSV output to track each bounce and angle
- Bonus points for exporting frustration as data

## 🚧 What’s Next?

- Add multiple beams (because one beam isn’t chaotic enough)
- Let users draw their own mazes (dangerous but fun)
- Use Excel to catch bugs my eyes missed

## 🧘‍♂️ Final Thoughts

Safety Maze started as “just a small thing.”

Now?  
It’s a red-line-filled, angle-tracking, devlog-generating machine.  
And yeah, it’s kind of cool watching your laser bounce perfectly through a world you designed.

More weird reflections coming soon.
