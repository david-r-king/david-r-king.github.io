
---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2025-12-04
published: true
labels:
  - Education
  - Software Design
  - Planning
  - Patterns
  - Architecture
---

<div class="text-center">
  <h2> The Invisible Structure </h2>
</div>

I think most people recognize the front-end of software development like buttons, color schemes, and the overall layout or functionality. Since it’s what we physically see with our eyes, it’s probably the aspect that gets the most attention. However, the real structure of an application that holds everything together is made of design patterns—reusable architectural solutions that keep complex systems from collapsing into chaos. They’re basically the “invisible structure” the entire program is built on.
---

<div class="text-center">
  <h4> Putting It All Together </h4>
</div>

I began noticing these patterns, after I knew what to look for, in our final project. Fortunately for us, Next.js has plenty of built-in design patterns that make our job much easier. One major one would be the file-based routing system. Think of it as building a new house, and everyone in the neighborhood immediately knows how to get there. It alleviates us from having to send mail to the whole neighborhood, notifying them of the new address or build any new roads to get there. This routing system keeps everything clean and organized, allowing my team and I to put more attention towards bigger problems.

Another pattern I’ve noticed, also due to Next.js’s genius, is the way it separates server logic from client components. This again helps to keep the project clean and organized. Loading tournament data shouldn’t be mixed in with cards, tables, and buttons since they have nothing to do with each other. This prevents the application from too much entanglement and helps us isolate any issues we may come across. This concept would be similar to the relationship a car engine and steering wheel have. They are both built to help the vehicle move, but need their own space to operate effectively.

The last design pattern I’ve noticed so far is the reusable UI pieces like our standings table, navbar, and event detail cards. These showcase a component-based pattern, which is building an application or website using small blocks of code independent of one another. Once we have a block of code for a certain function or visual, we are able to apply that same block to multiple pages. This helped us a great deal in maintaining the same aesthetics and color scheme to every page.

---

<div class="text-center">
  <h4> Conclusion </h4>
</div>

Applying these concepts to our project has already made a huge impact, and we aren’t even at the more difficult parts yet. I could only imagine how much slower and inefficient our progress would be without these solutions to common problems. Organization is everything. It can determine failure or success and design patterns have helped us build, maintain, expand, and one day soon, deploy our application.
