Readings: Passing Functions as Props

Map

Readings: Passing Functions as Props

Map

## What does .map() return?
A new array with the same number of elements.

## If I want to loop through an array and display each value in JSX, how do I do that in React?
Using curly braces

## Each list item needs a unique ____.
Key/IDs

## What is the purpose of a key?
Keys help React identify which items have been changed, added, or are removed.

Spread Operator

## What is the spread operator?
a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

## List 4 things that the spread operator can do.
-Math functions

-Adding to stat in React

-Combining Objects

- “spread” the array into separate arguments

## Give an example of using the spread operator to combine two arrays.
-Converting NodeList to Array like when selecting HTML elements on the page.

## Give an example of using the spread operator to add a new item to an array.
-Using an array as arguments

## Give an example of using the spread operator to combine two objects into one.
-array concatenation

Videos

## In the video, what is the first step that the developer does to pass functions between components?
Create a function where ever the state is

## In your own words, what does the increment function do?
We are passing through p which means to look for he name of p in the array and if it matches, increase the count. Then return that value and store it in the variable ppl

## How can you pass a method from a parent component into a child component?
Pass through the increment function down to the person object

## How does the child component invoke a method that was passed to it from a parent component?
Pass the name back up to the increment method by using this.props.increment(this.props.name); which causes the state to change and cause a re-render
What does .map() return?
A new array with the same number of elements.

## ## If I want to loop through an array and display each value in JSX, how do I do that in React?
Using curly braces

Each list item needs a unique ____.
Key/IDs

What is the purpose of a key?
Keys help React identify which items have been changed, added, or are removed.

 

Spread Operator

What is the spread operator?
a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

List 4 things that the spread operator can do.
-Math functions

-Adding to stat in React

-Combining Objects

- “spread” the array into separate arguments

Give an example of using the spread operator to combine two arrays.
-Converting NodeList to Array like when selecting HTML elements on the page.

Give an example of using the spread operator to add a new item to an array.
-Using an array as arguments

Give an example of using the spread operator to combine two objects into one.
-array concatenation

Videos

In the video, what is the first step that the developer does to pass functions between components?
Create a function where ever the state is

In your own words, what does the increment function do?
We are passing through p which means to look for he name of p in the array and if it matches, increase the count. Then return that value and store it in the variable ppl

How can you pass a method from a parent component into a child component?
Pass through the increment function down to the person object

How does the child component invoke a method that was passed to it from a parent component?
Pass the name back up to the increment method by using this.props.increment(this.props.name); which causes the state to change and cause a re-render
