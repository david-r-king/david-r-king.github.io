---
layout: essay
type: essay
title: "Software Engineering Reflection"
# All dates must be YYYY-MM-DD format!
date: 2025-12-15
published: true
labels:
  - Ethics in Software Engineering
  - Issue Driven Project Management
  - Functional Programming
  - App Development
---

<div class="essay-page se-reflection">
  <img
    src="../img/essays/SoftwareEngineering.png"
    class="essay-header-img"
    alt="coding"
  >
</div>

---

<div class="text-center">
  <h2> Reflecting on Software Engineering </h2>
</div>

This class introduced us to more detail of the process that comes with software engineering. Up to this point, the extent of our coding experience has been writing a program in an IDE to meet a submission date. This was the first class I have taken involving multiple pieces of technology, group projects, and common mothedologies. This exposure helped me learn how much more effort goes into large applications, far beyond writing the correct code to meet an objective. Specifically, this course helped me understand the importance of Agile Project Management, Configuration Management, and Design Patterns.

<div class="text-center">
  <h2> Agile Project Management and Issue-Driven Development </h2>
</div>

Agile Project Management is a way of organizing and managing software projects by breaking work into small, incremental tasks that can be completed, reviewed, and adjusted frequently. Instead of planning everything in advance and building the entire system at once, Agile emphasizes flexibility, collaboration, and continuous improvement.

One specific Agile approach we learned was Issue-Driven Project Management, where all work is tracked as issues in a shared repository. An “issue” represents a specific task, bug, feature, or improvement. Developers select issues to work on, create branches for those issues, and submit changes through pull requests. This creates a clear connection between planning, implementation, and review.

Through working on the CampusArena project, I saw how this approach applies to projects beyond web applications. For example, this same model could be used for embedded systems, desktop applications, or even non-software engineering projects like documentation or research workflows. Any project that benefits from breaking work into small, trackable units can use Issue-Driven Project Management. Personally, I can see myself using this approach in future projects because it keeps work organized, reduces confusion, and makes collaboration much easier.

<div class="text-center">
  <h2> Configuration Management </h2>
</div>

Another major concept I learned is Configuration Management, which refers to the process of controlling changes to software over time. This includes tracking versions of code, managing branches, handling dependencies, and ensuring that development, testing, and production environments remain consistent.

Before this class, I underestimated how critical configuration management is. Through real experience, I learned how mismatches between database schemas, environment variables, or dependency versions can break an otherwise working application. For example, we encountered issues where code expected database fields that did not exist locally because migrations had not been applied correctly. Solving these problems required understanding tools like Git, Prisma migrations, and environment configuration files.

Configuration management is not limited to web development. Any long-term software system—such as operating systems, network infrastructure, or enterprise tools—relies on strict configuration control to prevent failures. This course showed me that writing code is only one part of engineering; maintaining consistency across systems is just as important.

<div class="text-center">
  <h2> Design Patterns </h2>
</div>

Design patterns are reusable solutions to common problems in software design. Rather than focusing on specific syntax or frameworks, design patterns describe proven ways to structure code so it is easier to understand, extend, and maintain.

During this course, I saw design patterns emerge naturally in our project. For example, separating server logic from client components, using shared utility functions, and centralizing data access through service files are all examples of design patterns. These patterns reduce duplication and make the codebase easier to modify without breaking unrelated parts of the system.

Design patterns apply to all areas of software engineering. Whether building a mobile app, a game engine, or a cloud service, engineers rely on patterns to manage complexity. Learning to recognize and apply these patterns helped me think more like an engineer rather than just a programmer.

<div class="text-center">
  <h2> Ethics in Software Engineering </h2>
</div>

Finally, this course reinforced the ethical responsibilities of software engineers. Ethics in software engineering involves considering how software affects users, organizations, and society. This includes protecting user data, avoiding deceptive design, ensuring accessibility, and being honest about system limitations.

Working on a real project made these concerns feel concrete. Decisions about authentication, permissions, and data visibility are not just technical choices—they impact privacy and trust. Even small mistakes can lead to security vulnerabilities or user harm. This awareness will influence how I approach future projects, especially those involving sensitive information.

---

<div class="text-center">
  <h4> Conclusion </h4>
</div>

Overall, this course taught me that software engineering is about much more than building web applications. Concepts like Agile Project Management, Configuration Management, and Design Patterns apply across all types of software systems. Through hands-on experience, I learned how engineering decisions affect not only functionality, but also reliability, collaboration, and ethics. These lessons will carry forward into any technical project I work on in the future, regardless of platform or programming language.
