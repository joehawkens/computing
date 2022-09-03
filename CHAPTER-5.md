# Programming Lanugage Paradigms

This chapter aims to dig deeper into programming; we'll be doing this by exploring programming paradigms. A programming paradigm is a way to classify languages. The reason for doing this is to help label their features in order to know which ones would fit the needs of a project. If we compare programming languages to tools in a toolbox, you will know that some tools are better suited than others for problems, for example: you wouldn't use a hammer to paint wall, much like you wouldn't use MySQL to build a gaming engine, since MySQL is a database language and not suited for that level of complexity, i.e. it's not the right tool for the job, so we have paradigms to help us classify these languages so we can understand their features and know what tools (tech stack) are best suited to complete a project.

The two major paradigms I'll be discussing are Imperative and Declarative programming.




## Imperative

Imperative programming is simply defined as this: If you can trace the execution of the program as it runs. Consider the following code: you know you'll be reading it from top to bottom, the typical way of execution in programing. You're thinking like a computer this way.

```Python
counter = 0


while counter != 10:

    counter += 1
    print(counter)
```




## Declarative

Declarative is the reverse; you're thinking like a human, and can't always trace execution. You merely DECLARE what you want done, in the example below: you use different command clauses in SQL, you tell the computer what you're referencing (container) in CSS. And you DECLARE to the computer you want a hiearchy of headers and paragraphs in HTML. You don't care about what makes the h1 tag work, you're only concerned with it getting the job done - in Imperative you're more concered with a deeper level of abstraction - bringing in variables and shifting states.

```MySQL
SELECT * FROM Users WHERE country='USA';
```
```CSS
.container{
  color: green;
 }
 ```
 ```HTML
 <h1>
      <h2>
          <p>
      <h2>
 <h1>
 ```

### Important note regarding Programming Paradigms:

There is a lot of controversy online of what makes something Declarative and something Imperative, since the only difference is abstraction - the line is blurred so much that one should view paradigms as a spectrum measuring human readability rather than distinct categories of one or the other. For example: when writing a loop in Python code, how a variable is able to be declared is of no immediate concern to you, it has been abstracted away, and therefore could technically be considered declarative since it's more human-readable code.

## Examples of Imperative languages:
   
   * C++
   * Assembly Language
   * Python
   * JavaScript
   * Java

## Examples of Declarative languages:
   
   * MySQL
   * HTML
   * CSS
   



# Conclusion

   We have covered essential concepts from the way electricity powers the computer, to the components of a machine, to how hardware turns into software. The goal of this short course was to simplify concepts and help you along the way in creating meaningful software, because in the end that's what it's all about - sure many of these concepts are important, but the most important takeaway is that you create something that provides value and meaning for people. That is the ethos of the Software Engineer. Now go out and create something you love.
