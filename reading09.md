# Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

* What is functional programming?

  * Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia

* What is a pure function and how do we know if something is a pure function?

  * A function is pure if:

    * It returns the same result if given the same arguments (it is also referred as deterministic)

    * It does not cause any observable side effects

* What are the benefits of a pure function?

  * The code is easier to test

* What is immutability?

  * When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value

* What is Referential transparency?

  * If a function consistently yields the same result for the same input, it is referentially transparent

## [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

* What is a module?

  * A module is essentially another JavaScript file

* What does the word ‘require’ do?

  * It allows you to use modules in your app

* How do we bring another module into the file the we are working in?

  * Use require and pass through a string with the module that we require to use

* What do we have to do to make a module available?

  * Have to specify what part of the module we want to make available to other files that require the module


### Some information taken from the websites listed above