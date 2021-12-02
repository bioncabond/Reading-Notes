Readings: State and Props

Reading
## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render is first

## What is the very first thing to happen in the lifecycle of React?
Mounting: when the instance of a component is being created and inserted into the DOM it occurs during the mounting. Phase.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
Constructor=>Render=>React Updates=>componentDidMount=>componentWillUnmount

## What does componentDidMount do?
Since this follows after the component is mountd; this is were you place anything that needs to load using a network request or initialize the DOM. Good place for subscriptions but you will have to unsubscribe in the componentWillUnmount().

Videos
## What types of things can you pass in the props?
Initial counts; display titles and subtitles;

## What is the big difference between props and state?
Props you pass into and update outside of the component. Changes have to be made outside of the component; State is updated inside of the component. When you change something within state it will re-render that section of the application.

## When do we re-render our application?
Use state to update an application based on what the user has done.

## What are some examples of things that we could store in state?
This that will continue to update based on user input. When using a form or checkbox that needs to be updated by the user.