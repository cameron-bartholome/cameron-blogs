---
title: "A Designer’s Guide to Devlogs: Thinking in Features, Not Just Files"
layout: single
date: 2025-06-23
author: Cameron Bartholome
categories: [engineering, devlogs]
---

If you’re a mechanical engineer, chances are your documentation consists of a CAD file, a few screenshots, and that one folder named “_OldStuff_DoNotDelete”.  

If someone asked _why_ you added that fillet or _when_ you made the wall thickness 2.5mm instead of 3, your best answer might be:  
> “I think I remember doing that two Tuesdays ago... maybe?”

Let’s be honest — **our process is not built for memory**. It’s built for files. But files don’t tell the story. Features do.

---
### 🧱 Traditional Engineering Thinking: File-Based

Mechanical workflows tend to revolve around **objects**:  
- Part files  
- Assembly trees  
- Drawings and revisions  
- PDFs and folders that go through five versions before someone renames them "Final_REAL_final_v2"

We treat the creation of these files as the *work itself* — and forget that what really matters is what those files **change**.

---
### 🧠 Devlogs: The Missing Middle Layer

When I started coding, I discovered this brilliant thing developers use: **devlogs**.

They’re like diaries for your project — but structured.  
Notebooks that don’t say *what* exists, but *why* it was added, changed, or deleted.

Each entry is tied to:
- A specific problem  
- A proposed solution  
- A reflection on what worked (or didn't)

Basically, it's project memory. In human-speak.

---
### 💡 From Parts to Features

So I started writing devlogs for mechanical design too.  
Instead of just naming a model `LaserHousing_Rev3`, I now have entries like:

> **[DEV-2025-06-15-01] Improve Cooling Path in Laser Housing**  
> Problem:: Too much heat at 60% duty cycle  
> Solution:: Added angled fin array, airflow simulation shows 15% improvement  
> Notes:: Next test: real-world fan placement

Suddenly, I wasn’t guessing anymore.  
Every design choice had a breadcrumb trail.

---
### 🛠️ Tools That Make It Easy

You don’t need Jira or Teamcenter or an IT degree.

You just need:
- **Obsidian** (or Notion, or a plain folder of Markdown files)  
- A simple template (date, issue, solution, file touched, maybe a screenshot)  
- A commitment to write 1–2 sentences when you finish a task

Bonus: you’ll look way more organized in meetings.  
Even if you did just throw it together in five minutes before the call.

---
### 🚀 Why It Matters

Devlogs:
- Help you debug faster when something breaks
- Let others (or future-you) understand what’s going on
- Turn chaotic projects into clean timelines
- Make handovers actually survivable

And the best part?  
You stop feeling like you're drowning in version folders — and start seeing your work like a series of solved problems.

---