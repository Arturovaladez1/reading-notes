# Reading Class Notes 2

## React Life Cycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

- What is the very first thing to happen in the lifecycle of React?

Mounting 

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
What does componentDidMount do?

constructor, render, react Updates, componnet did mount, componentWillUnmount.

componenent did mount: This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().


## React State Vs Props 

- What types of things can you pass in the props?

things you want your function or componenet to take

- What is the big difference between props and state?

props pass into a componenent 
state is inside a component can update inside
state is handled outside of a component

- When do we re-render our application?
when we change the state of application

- What are some examples of things that we could store in state?

in a form because its being updated by user
if your handling that peice of info in that component

[State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

[Handling Events](https://reactjs.org/docs/handling-events.html)

[Intro to React](https://reactjs.org/tutorial/tutorial.html)

[React Bootstrap](https://react-bootstrap.github.io/)

[Bootstrap](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

[Bootstrap shuffle](https://bootstrapshuffle.com/classes)

[Netlify](https://www.netlify.com/)