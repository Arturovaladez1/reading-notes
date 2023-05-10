# Class 27 Notes

## React Quickstart

1. What are the building blocks of a React app?
The building blocks of a React app are components. Components are independent and reusable parts of a user interface that can be composed together to create complex user interfaces. Each component encapsulates its own state and logic, making it easier to manage and debug.

2. What is the difference between an HTML element and a React component?
HTML elements are predefined tags in HTML, such as <div>, <span>, <img>, etc. that are used to define the structure and content of a web page. React components, on the other hand, are custom-made user interface elements that can be composed together to create complex user interfaces. React components are written in JavaScript and provide a more declarative and functional approach to building user interfaces.

3. What is JSX and why do we use it?
JSX is a syntax extension for JavaScript that allows developers to write HTML-like code in their JavaScript code. JSX makes it easier to create React components and manage their rendering logic. It also allows developers to use JavaScript expressions in their HTML-like code.

4. Describe the process of embedding JavaScript expressions in JSX.
To embed JavaScript expressions in JSX, you can use curly braces {}. For example, if you want to render the value of a variable named "name" in a JSX element, you can do it like this: `<div>Hello, {name}!</div>`. The expression inside the curly braces will be evaluated and its value will be inserted into the JSX element.

5. Does React or JSX have any special features for iteration or conditional logic?
Yes, React provides several features for iteration and conditional logic, such as the map() method for iterating over arrays, the ternary operator for conditional rendering, and the && operator for conditional rendering. JSX also supports the use of these features within its syntax.

6. How does React know to respond to a user’s inputs?
React uses event handlers to respond to user inputs. When a user interacts with a component, such as clicking a button, React triggers the appropriate event handler function, which can then update the component's state or trigger other actions.

7. What word indicates that a React component manages data with a Hook?
The word is "useState". useState is a built-in Hook in React that allows components to manage their own state.

8. How can two React components share data?
There are several ways for two React components to share data. One way is to pass data down from a parent component to a child component via props. Another way is to use a state management library like Redux or MobX to manage shared state across multiple components. A third way is to use the useContext Hook to share data between components without having to pass props down through intermediate components.

## Render and Commit

1. What are the three steps of refreshing a React UI?
The three steps of refreshing a React UI are:

Updating the component state or props
Re-rendering the component
Updating the DOM with the changes

2. How do you trigger updates to a component after the initial render?

You can trigger updates to a component after the initial render by updating its state or props. React will then re-render the component with the new data and update the DOM.

To update the state of a component, you can use the setState() method, which is provided by React. To update the props of a component, you can pass new props to the component from its parent.

Does React recreate DOM nodes on every rerender?

No, React uses a virtual DOM to efficiently update the DOM. When a component is re-rendered, React creates a new virtual DOM tree and compares it with the previous one to find the differences. Then, it only updates the parts of the DOM that have changed, without recreating all the DOM nodes.

After React has updated the DOM, what still needs to happen before the user sees the change?

After React has updated the DOM, the browser still needs to paint the updated content on the screen. This process is called layout and painting. The browser computes the layout of the updated elements and then paints them on the screen. The time it takes for this process to complete depends on the complexity of the updated content and the performance of the user's device.

## Sources

[quickstart react](https://react.dev/learn)

[Render and Commit](https://canvas.instructure.com/courses/6390937/discussion_topics/17583800)

[First Component](https://react.dev/learn/your-first-component)

[importing and exporting components](https://react.dev/learn/importing-and-exporting-components)

[JSX](https://react.dev/learn/writing-markup-with-jsx)

[SASS](https://devhints.io/sass)

[REACT Cheatsheet](https://devhints.io/react)
