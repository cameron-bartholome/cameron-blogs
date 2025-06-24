---
title: "Drawing Titles vs Commit Messages: A Tragedy in Three Acts"
layout: single
date: 2025-06-20
author: Cameron Bartholome
categories: [engineering, github, workflow]
---

### Act I: “Updated per Feedback”

You’ve opened a drawing. Rev B.  
In the title block: “Change made based on team input.”  
And that’s it.

What changed?  
Who asked for it?  
What problem did it solve?  
Nobody knows. The engineer who made the change is on vacation, the project lead is in another meeting, and you’re sitting there with a confused expression and a deadline.

Welcome to the **Shakespearean tragedy** that is drawing change notes.

### Act II: Commit Messages Enter Stage Left

Meanwhile, in the world of code:

```bash
git commit -m "Fix: swapped X and Y axis labels in sensor output"
```

Clear. Precise. Searchable.  
You can see what changed, why it changed, when it changed, and even link it to the issue that caused it.

This isn’t just logging — this is **context**.  
Context is the difference between “Why did you do this?” and “Ah, makes sense.”


### Act III: The Revenge of Revision C

Back in CAD land, you're now on Rev C.  
This time the note reads:  
> “Minor adjustments.”

Like… what kind of adjustments?  
Was the hole resized? A chamfer added? Did you rotate the entire bracket 45 degrees and forget to update the assembly?

Nobody knows. Everyone suffers.


### 🛠️ We Need Better Tools (or Better Habits)

Mechanical design deserves better.  
If we can't have commit messages in NX or SolidWorks, we *can* at least do better with:

- A changelog per part  
- Devlogs in Markdown  
- Clear naming of revisions  
- Linking reasons to changes

Imagine:

> `Rev B – Increased slot width from 10mm to 12mm due to tolerance stack-up issues in assembly.`  
Now that’s useful.

---

### 🧠 TL;DR

Commit messages in GitHub = brilliant.  
Drawing titles = vague sticky notes in PDF form.

If you’ve ever stared at a drawing and thought _"What the hell changed here?"_ — this post’s for you.

---