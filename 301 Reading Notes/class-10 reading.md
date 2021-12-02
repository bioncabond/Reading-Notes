Readings: In memory storage

Reading
Understanding the JavaScript Call Stack

## What is a ‘call’?

Functional invocation

## How many ‘calls’ can happen at once?

One at a time

## What does LIFO mean?

Last In First Out

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

1. When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.
2. secondFunction() then calls firstFunction()which is pushed into the stack.
3. firstFunction() returns and prints “Hello from firstFunction” to the console.
4. firstFunction() is pop off the stack.
5. The execution order then move to secondFunction().
6. secondFunction() returns and print “The end from secondFunction” to the console.
7. secondFunction() is pop off the stack, clearing the memory.

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

JavaScript error messages

## What is a ‘refrence error’?

Errors associated when you haven’t used a variable

## What is a ‘syntax error’?

An error associated with the format of the acceptable language in use.

## What is a ‘range error’?

When the length of an array for example doesn’t make logical sense for what is to be returned or used in the array

## What is a ‘tyep error’?

When the type you are trying to use or access are incompatible.

## What is a breakpoint?

A line in your code that will allow execution to continue if it is not working as intended.

## What does the word ‘debugger’ do in your code?

It executes your code and shows you where errors occurred during the execution.