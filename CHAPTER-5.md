# Programming Language Paradigms

This chapter aims to dig deeper into programming; we'll be doing this by exploring programming paradigms. A programming paradigm is a way to classify languages. The reason for doing this is to help label their features in order to know which ones would fit the needs of a project. If we compare programming languages to tools in a toolbox, you will know that some tools are better suited than others for problems, for example: you wouldn't use a hammer to paint wall, much like you wouldn't use MySQL to build a gaming engine, since MySQL is a database language and not suited for that level of complexity, i.e. it's not the right tool for the job, so we have paradigms to help us classify these languages so we can understand their features and know what tools (tech stack) are best suited to complete a project.

The two major paradigms I'll be discussing are Imperative and Declarative programming - each major paradigm has sub-paradigms that further classify and label languages, such as Object-Oriented Programming (OOP).




## Imperative

Imperative programming is simply defined as this: If you can trace the execution of the program as it runs, it's imperative. Consider the following code: you know you'll be reading it from top to bottom, the typical way of execution in programing. You're thinking like a computer this way.

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

### Important note regarding Imperative and Declarative:

There is a lot of controversy online of what makes something Declarative and something Imperative, since the only difference is abstraction - the line is blurred so much that one should view paradigms as a spectrum measuring human readability rather than distinct categories of one or the other. For example: when writing a loop in Python code, how a variable is able to be declared is of no immediate concern to you, it has been abstracted away, and therefore could technically be considered declarative since it's more human-readable code.

### Examples of Imperative languages:
   
   * C++
   * Assembly Language
   * Python
   * JavaScript
   * Java

### Examples of Declarative languages:
   
   * MySQL
   * HTML
   * CSS


## Further sub-paradigms:


### Object-Oriented Programming

A subcategory of the Imperative paradigm, an object is a single abstract entity which contains many points of data, methods, and functions. In OOP the fundamental concept underlying this paradigm is the relationship objects have to one another. It's very heavily used within game development since characters, items in game, and environments constitute as objects. OOP has reigned the supreme paradigm for many years now, but recently there has been much discussion on branching to other paradigms such as functional programming.

### Functional Programming

A subcategory of the declarative paradigm, functional programming uses purely function to have strict control flow and less side-effects gained from extra logical operations found in imperative programming. It's a very streamlined paradigm that has gained a lot of favor in recent years due to its simplicity and ease of implementation.


### Procedural Programming

This sub-paradigm is what the name entails - it follows procedure, code is executed from top to bottom. But one may ask: "Wait, isn't that how most languages run anyway?" - You'd be correct, yes, which is why a lot of languages can fall under the category of multiple paradigms, like C++ - it's both an Object-Oriented language and a Procedural language - think of a warehouse full of construction equipment and tools. There are some tools which are drastically different: a paint brush and a hammer, but there are other tools that can overlap with one another and require to be put in the same category with each other - like how a chainsaw and a table saw both cut, but have different specialized utility based on their shape and form.
   
   
## How Code Runs

On top of having a paradigm (or paradigms) - languages are either interpreted or compiled. What does this mean? It's simply the means by which your program is translated into machine code. Interpreted languages are translated instantly to the computer, line by line, allowing you to see errors immediately upon writing. Compilers, which take longer to translate, take the entire file of code all at once for translation into machine code.

## Type System

Each Programming language has a type system, defined as either Strong or Weak - Dynamic or Static. Programmers know what a type is in programming: Bool, String, Int, Double, etc. Let's take a look at these four terms and put them to examples, starting with the dynamic type system:

### Dynamically Typed vs. Statically Typed

```Python
# Python is dynamically typed because it allows type reassignment throughout the life of the program.

number = 12
print(type(number))
# type: int

...

number = "string"
print(type(number))
# type: string
```

Let's look at a statically typed language: C++
```C++
#include <iostream>
using namespace std;

int main() {
  int number = 15; // The variable "number" is declared a type of int.
  
  str number = "number"; // If you try to reassign the variable data type, it will throw an error.
}
```

Statically typed languages are created this way as a means of safety. Imagine you're creating Software for a nuclear defense missile, you're going to want a safety net to ensure that everything is correctly defined before you compile, otherwise the consequences could be catastrophic.



### Weak Typed vs. Strongly Typed

A weak typed language is very relaxed on how data types are created. In JavaScript, if you create a string you don't have to explicitly say that it's going to be a string, this is inferred by the language itself...

```JavaScript
let number = "two";
```

In a strongly typed language, you must declare your data types. Here's an example in C#...

```C#
int number = 2;
```

Notice how you had to declare the the variable "number" was an int.


In conclusion:

WHEN typing is checked - definitive:
* Static: Types are checked when code is compiled.
* Dynamic: Types are checked after code is compiled (during runtime).

HOW STRONG typing is enforced - a spectrum:
* Strong: You need to strictly declare data types.
* Weak: Data types are inferred when created.


