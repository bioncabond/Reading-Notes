Readings: FUNCTIONAL PROGRAMMING

## What is functional programming?

A programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## What is a pure function and how do we know if something is a pure function?

A function that returns the same result if given the same arguments (it is also referred as deterministic); does not cause any observable side effects

## What are the benefits of a pure function?

Code is easier to test;

## What is immutability?

unchanging over time/unable to be changed;  

## What is Referential transparency?

If a function consistently yields the same result for the same input, it is referentially transparent. Pure function s+ immutable data = referential transparency

Modules Youtube

## What is a module?

A logical section of code that has a different but certain functionality within our application then we call on those modules as we need them.

## What does the word ‘require’ do?

A way to pass through the access to different module files.

## How do we bring another module into the file the we are working in?

Require(‘./filename.js)

## What do we have to do to make a module available?

We allow accessibility to the function within that module file so:

Module.exports = function_variable_name;
