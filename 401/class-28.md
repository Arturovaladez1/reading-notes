# Class 28 Notes

## Thinking in React

Summarize the five steps of thinking in react.

## State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?

components often need to keep track of their state over time, and local variables are reset every time the component is rendered

What is the argument to the useState hook, and what are the two parts of its return array?

the initial state value of the state variable.
current state value.
function that can be used to update the state value.

How can Component A access state from Component B?

need to pass the state value and the updating function down to Component A as props. Component B can manage the state and provide the state values and functions as props to its child components, including Component A

## Sources

![React](https://react.dev/learn/thinking-in-react)

![State](https://react.dev/learn/state-a-components-memory)

![Props](https://react.dev/learn/passing-props-to-a-component)

![Lists](https://react.dev/learn/rendering-lists)

![state](https://react.dev/learn/state-as-a-snapshot)

![usestate](https://react.dev/reference/react/useState)

