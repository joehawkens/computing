# Problem Solving

Now that we know the core principles of Software Engineering - it's time for application. This is where the problem solving method comes in; it should be used on **every** problem you encounter in your career, it should become second nature and used as a guiding force for every decision you make, hence why it gets its own chapter. The problem solving method is broken up into steps, there are several versions, but most of them cover the same things - my version has 5 steps:

```
1. Understand the Problem
    - Context
    - Issue
    - Reason for Solving
2. Research 
    - Read Documentation
    - Discuss with Teammates
    - Look for problem previously solved by someone online (Stack Overflow)
3. Plan a Solution
    - Write Psuedocode
    - Write Tests (Prevent Regression)
4. Implementation
    - "Done is better than perfect"
5. Optimization
    - Improve Readability
    - Add Comments
    - Remove Duplication
    - Optimize time/space complexity
    - Add error handling
```


## Understand the Problem

Jumping right into an issue without first understanding limitations and context will make things difficult. Take time to truly understand the problem, so you know not only how to solve it, but how to optimize it later. The first step is creating a problem statement: this provides 1. context, 2. the main issue, and 3. The reason for solving.

* **Context:** The story of development and where the problem fits into it.
* **Issue:** The bug or problem itself.
* **Reason for solving:** Why is it important to solve this issue.

Giving the problem context, identifying the issue, and knowing **why** you're doing something are critical because they help to facilitate greater confidence in step two of this process: Research

## Research

Research is simply understanding what tools you'll be using, syntax, documentation, and working with teammates to gather information regarding the problem, this helps to plan a solution.

### Loops

Most code problems will involve some kind of loop. ALWAYS consider if you can implement a function before ever thinking of using a loop, for example: Map(), Filter(), Reduce(). These will carry the workload and make your code a lot cleaner, saving you a heartache.

## Plan a Solution

Once you know your tools that will help within the scope of the problem you can plan a solution. To begin you can write Pseudocode, or code that lays outs steps to solving the problem. Another consideration to take at this stage is setting up tests. This will help with regression, or, when your program breaks in the future - causing you to go back and figure out what happened, it's best to catch those problems when developing to ensure quality code is created.

## Implementation

Once you have a solution planned out, implementation is the next step. This is a messy process and you'll need to repeat step 2-4 a few times before you get it right. "Getting is done is better than getting it perfect".

## Optimization

Once your code works and the problem is solved, optimization is the next step. Error handling, improving readability, and performance (time/space complexity). The problem is solved and your code runs smoothly. On to the next problem!

