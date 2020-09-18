# 3. Functions

#### Small!

* The first rule of functions is that they should be small. The second rule of functions is that they should be smaller than that

* The indent level of a function should not be greater than one or two

#### Do One Thing

* Functions should do one thing. They should do it well. they should do it only

* The reason we write functions is to decompose a larger concept into a set of steps at the next level of abstraction

* Another way to know that a function is doing more thatn "one thing" is if you can extract another function from it with a name that is not merely a restatement of its implementation

* Functions that do one thing cannot be reasonably divided into sections

#### One Level of Abstraction per Function

* Make sure that the statements within our function are all at the same level of abstraction
* Make the code read like a top-down set of TO paragraphs

#### Switch Statements

* Make sure that each switch statement is buried in a low-level class and is never repeated

#### Use Descriptive Names

* Better describes what the function does
* Choose good names for small functions that do one thing
* A long descriptive name is better than a short enigmatic name. A long descriptive name is better than a long descriptive comment
* It is not at all uncommon that hunting for a good name results in a favorable restructuring of the code

#### Function Arguments

* The ideal number of arguments for a function is zero (niladic)
* Arguments are even harder from a testing point of view
* Flag arguments are ugly. Passing a boolean into a function is a truly terrible practice
* Reducing the number of arguments by creating objects out of them may seem like cheating, but it's not
* If the variable arguments are all treated identically then they are equivalent to a single argument of type list

#### Have No Side Effects

* Side effects are lies. Your function promises to do one thing, but it also does other hidden things
* Anything that forces you to check the function signature is equivalent to a double-take. e.g, output argument
* Functions should either do something or answer something, but not both

#### Prefer Exceptions to Returning Error Codes

* When you return an error code, you create the problem that the caller must deal with the error immediately
* It is better to extract the bodies of the try and catch blocks out into functions of their own
* Error handling is one thing

#### Don't Repeat Yourself

Duplication my be the root of all evil in software

#### Structured Programming

* Dijkstra said that every function, and every block within a function, should have one entry and one exit
* serve little benefit when functions are very small

#### How Do You Write Functions Like This?

Writing software is like any other kind of writing

1. Write first draft
2. Make a suite of unit tests
3. Wordsmith it

> The art of programming is, and has always been, the art of language design.
>
> Never forget that your real goal is to tell the story of the system, and that the functions you write need to fit cleanly together into a clear and precise language to help you with that telling

