# Week 3 Resources

## Unit 1 Algorithm Analysis

Understand time and space complexity of important algorithms and data structures usin [Analysis of Algorithms By Steven Skiena](https://www.youtube.com/playlist?list=PLOtl7M3yp-DXbHTFe_w9zFPXeau28CDao). Videos 1 to 6 and 8 should be enough.
You could also refer to his book [The Algorithm Design Manual ](https://www.amazon.com/Algorithm-Design-Manual-Computer-Science/dp/3030542556). 


## Unit 2 Generic Programming in Rust

Read chapters 10 to 12 from `The Rust Programming Language` book. Spend extra time on Chapter 10. Implement all the algorithms and data structures you learnt from previous day using Rust and generics. You can use some basic collections from Rust standard for some of these(eg Vector). Where possible keep things as generic as possible.

For example

- Binary Search
- Quicksort and MergeSort
- Hashtable
- Binary search tree: insertion and traversal


## Unit 3 Testing Principles

- Learn essentials of unit testing with [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530/). Part 1(chaptersw 1 to 17). As many as you can cover, these are really really short chapters, each around 4 pages. 

- More specifically learn Act-Arrange-Assert pattern with [Unit Testing Principles, Practices, and Patterns](https://www.amazon.com/Unit-Testing-Principles-Practices-Patterns/dp/1617296279). Chapters 2 and 3. Also learn about [Given-When-Then](https://martinfowler.com/bliki/GivenWhenThen.html) pattern.

- Read chapters 1-6 from [Effective Software Testing: A developer's guide](https://www.amazon.com/dp/1633439933)
Learn basics of [Integration Testing](https://martinfowler.com/bliki/IntegrationTest.html)

- Write unit tests for all Rust programs you have written till now using the principles above. Integrate this into git hooks or your CI/CD pipeline

- Learn the testing patterns: [The Practical Test Pattern](https://martinfowler.com/articles/practical-test-pyramid.html) and [The Testing Trophy](https://kentcdodds.com/blog/write-tests)

Note that TDD might not be suitable for many projects. Also note that AAA might not be suitable for a lot of projects. Some might disagree the Testing Pyramid pattern. Learn both and use what's best for your project/team.

I personally pick Given-When-Then, Testing Trophy for most projects. I generally don't use test driven development. Still, I learnt most about testing from Kent Beck's book.

- [The Magic Tricks of Testing by Sandi Metz](https://www.youtube.com/watch?v=URSWYvyc42M)

- I would highly recommend reading first four chapters from [Refactoring](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599). Optional


## Unit 4 Functional Programming in Rust

- In my opinion, Rust is the best functional programming language! Many disagree. First learn the most accurate description of [functional programming](https://www.amazon.com/Functional-Programming-Second-Michael-Pilquist/dp/1617299588) by reading chapter 1.

- You have already learned about value/identity/time. Read another, more [practical explaination](https://www.infoq.com/articles/Datomic-Information-Model/). Note that this equally good description of functional programming!

- Read chapter 13 and 19 from The Rust book.

- Implement linked with the list interface from 'Why functional programming matters'. Implement that interface for list. Use generics. Make sure the list is immutable. Write a few functions like insert, remove, reverse. Write tests for everything.

- Read chapter 12 from The Rust book. Write basic integration tests. Try to separate functional code from imperative code. Write unit tests for functional code. Find some programs from [Command Line Rust](https://www.amazon.com/Command-Line-Rust-Project-Based-Primer-Writing/dp/1098109430) and do the same: split functional from imperative, write unit tests for pure core and integration tests for imperative shell.

## Unit 5: Github Actions

You could read the first four chapters from [Learning Github Actions](https://www.amazon.com/Learning-GitHub-Actions-Automation-Integration/dp/109813107X). Optional.

Lab: 
- Take flight with GitHub Copilot section of [](https://learn.github.com/skills)
- [Building and Testing Rust](https://docs.github.com/en/actions/tutorials/build-and-test-code/rust)
