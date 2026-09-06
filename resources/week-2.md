# Week 2 Resources for Rust, Git, CI/CD pipelines

## Day 1

Most of the modern solutions to distributed systems are based on the following fundamental idea. This is critical to understand concepts later, so watch it twice(Monday and then on Friday).

- [Database as value](https://www.youtube.com/watch?v=EKdV1IgAaFc)

You can first watch the following video. Optional.

- [Simple Made Easy](https://www.youtube.com/watch?v=SxdOUGdseq4)

Understand the above ideas by learning internals of git. git is a distributed system and broadly follows the above principles.

- [Git Internals - A Database Perspective](https://www.youtube.com/watch?v=6b6iOPvspPs&t=107s)
- [Git Internals](https://www.youtube.com/watch?v=lG90LZotrpo)
- [The Git Parable](https://www.infoq.com/presentations/git-details/)

Once you have a good understanding of git internals and how it relates to value, identity, time, read the following. You don't need to complete it.

- [Why functional programming Matters](https://www.researchgate.net/publication/2452204_Why_Functional_Programming_Matters)

## Day 2

Rust is a safe systems programming language. Rust is not a functional programming language. Rust will teach you fundamentals of writing good code without having to resort to full functional programming paradigm hence far more useful to everyday java, typescript and python programmers.

You should try and understand why Rust works. Why software written in rust is predictable compared to other imperative languages. Also understand how it's mostly equivalent to functional programming languages like scala, clojure or elixir.

Use [The Rust Programming Language](https://rust-book.cs.brown.edu/) book. Read first 6 chapters. Note that it's interactive and execute most code in the book inline.
If you prefer video [Ultimate Rust Lang tutorial](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8). This will cover the book(almost).

**Lab**: Write a lot of small programs with the help of your mentor, without using AI. Get comfortable with the concepts and syntax.

## Day 3

Learn advanced concepts in git using [Everything You'll Need to Know About Git](https://master.dev/courses/everything-git/). 

Watch the following sections

- Branching, merging and Rebasing 
- Working with Remote Repositories
- Conflict Resolution

Optionally watch Git Basics.

For those who prefer a book, use [Learning Git](https://www.amazon.com/Learning-Git-Hands-Visual-Basics/dp/1098133919). This is a detailed hands-on approach to git. This is a short book. Cover chapters 3 to 5 and 9 to 12.

Use both resources if possible. When the videos are difficult, read the same topic in book and if a concept is absent in book, watch the video.

**Lab**:  Use [Learn GitHub within GitHub](https://learn.github.com/skills). Cover First week on Github section.

## Day 4

Simple introduction to continuous integration and continuous deployment.

- [Continuous Integration](https://www.youtube.com/watch?v=1er2cjUq1UI)
- [Continuous Testing](https://www.youtube.com/watch?v=RYQbmjLgubM)
- [Continuous Delivery](https://www.youtube.com/watch?v=2TTU5BB-k9U)
- [Continuous Deployment vs Continuous Integration](https://www.youtube.com/watch?v=LNLKZ4Rvk8w)

Read chapters 3 to 5 from [Continuous Delivery](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley-ebook/dp/B003YMNVC0)

Read blog article [Branching Patterns](https://martinfowler.com/articles/branching-patterns.html) or [Branching Strategies explained](https://www.youtube.com/watch?v=U_IFGpJDbeU)

Watch  Git Tools and Techniques section from frontend masters git course.

**Lab**: Learn [git flow/github flow](https://www.youtube.com/watch?v=GQQqf-C2ha4&t=531s). With your mentor decide your [commit messages format](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html), branching strategies, implement an AI agent skill and use it for all of your code.

## Day 5

Read Common collections and Error handling chapters from the Rust book.

**Lab**: 

- Implement a single linked list using the borrow checker ideas and database as a value(naive/basic) idea. Do not use any collections from standard library. Incorporate some of the knowledge you gained from error handling chapter.
- Rewrite your programs using collections and include robust error handling. 
- Write a few more programs(larger) using  collections and error handling.

We will revisit error handling and data structures in later weeks.
