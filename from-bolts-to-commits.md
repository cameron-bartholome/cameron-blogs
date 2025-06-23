# From Bolts to Commits: Why GitHub Feels Like Magic for a Mechanical Engineer

So here’s the thing.

I’ve spent a few years in mechanical engineering, designing parts, assemblies, brackets, and random bits that hold lasers or guide air or just exist to make something else not fall over. It’s CAD all day, Siemens NX, SolidWorks, Shapr3D, you name it. You get your model, your drawing, your exploded view, your tolerances... and then you try to remember what the heck you changed last week.

Enter: chaos.  
Or better said: Excel files, email chains, and your memory, which by Wednesday is basically a black hole.

## 🧠 Mechanical Engineering: The Manual Save Game

In mechanical design, "issue tracking" usually means:

- Your colleague yelling "Hey, this hole’s the wrong diameter!" from across the room.  
- A sticky note taped to your monitor.  
- A file named `final_final_version3_FINAL.stp` because, yeah, you forgot to version it properly again.

Sure, we have PLM systems like Teamcenter. But using them feels like applying for a visa every time you want to save a file. It’s not agile. It's... glacial.

Want to make a change? Better write it down somewhere. Maybe a change request, maybe an email, maybe just try to remember it when someone asks later. I’m convinced most of our time is spent trying to figure out *why* we made a change, not even *what* the change was.

## 💻 Then I Met GitHub

When I started learning to code and stumbled onto GitHub, it felt like I’d unlocked a superpower.

```bash
git commit -m "Fix: laser path bounced into hyperspace on shallow angles"
```

Boom. That’s it. You see exactly what changed, why it changed, and when. You can even link it to a task or issue.

It’s not just logging. It’s context.  
And context means fewer headaches and fewer guesswork meetings.

## 🧱 Mechanical Design: Where Version Control Is... a Folder Mess

In CAD, we don’t really commit anything. You save your file and just hope no one overwrites it.

Yeah, you can track changes in Teamcenter or add notes in your revision block. But it’s slow. It’s clunky. And honestly, I’ve seen people make PowerPoint slides to explain design changes because it was faster than dealing with the system.

Imagine if we could write commit messages like:

- "Replaced M6 screw with M8 after Peter snapped the first one."  
- "Removed third bracket because, surprise, it wasn't doing anything."  
- "Rotated entire sub-assembly 90 degrees. Apparently, it's been upside down for 3 months and nobody noticed."

But instead we get "Rev 3.2 – updated per feedback."  
What feedback? From who? About what?

## 🤔 What I'm Really Saying

Mechanical design needs something better.  
Maybe not full Git, but at least the mindset.

Tracking changes with intent. Writing down what we changed and why. Making decisions traceable. That’s what commit culture brings.

Even if CAD doesn’t support it natively, I’ve started using Obsidian to log my design updates. Now, when someone asks about that weird bracket slot I added last month, I actually know the answer.

So until CAD gets proper version control, I’ll be over here writing devlogs and pretending I’m committing my models.

And if I ever forget why I added that extra support tab?  
I’ll just call it a “legacy feature” and move on, like a true developer.

