# Class 5 notes

## Thinking React

- What is the single responsibility principle and how does it apply to components?

single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

- What does it mean to build a ‘static’ version of your application?

you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

- Once you have a static application, what do you need to add?



- What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

- How can you identify where state needs to live?

Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand. we need to identify which component mutates, or owns, this state.

## Higher Order Functions

- What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

it is returning m setting m is greater than n true.


- Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

## Sources
[Thinking React](https://reactjs.org/docs/thinking-in-react.html)

[Higher Thinking](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)