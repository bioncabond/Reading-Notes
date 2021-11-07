React Docs - Thinking in React (Links to an external site.)

## What is the single responsibility principle and how does it apply to components?
 a component should ideally only do one thing
## What does it mean to build a ‘static’ version of your application?
To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child.
## Once you have a static application, what do you need to add?
You can build top-down or bottom-up but still in the vain if hierarchy.
## What are the three questions you can ask to determine if something is state?
-Is it passed in from a parent via props? If so, it probably isn’t state.
-Does it remain unchanged over time? If so, it probably isn’t state.
-Can you compute it based on any other state or props in your component? If so, it isn’t state.
## How can you identify where state needs to live?
For each piece of state in your application:

-Identify every component that renders something based on that state.
-Find a common owner component (a single component above all the components that need the state in the hierarchy).
-Either the common owner or another component higher up in the hierarchy should own the state.
-If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
Higher-Order Functions (Links to an external site.)

## What is a “higher-order function”?
Functions that operate on other functions, either by taking them as arguments or by returning them
## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
returning the m value if it is greater than n
## Explain how either map or reduce operates, with regards to higher-order functions. 
There is a built-in array method, forEach, that provides something like a for/of loop as a higher-order function.