# Thinking in React

* How would you break a mock into a component heirarchy?

  * Draw boxes around each component and give them all names

  * Figure out if you need to create a new function or object

  * Next, arrange all components into a hierarchy

* What is the single responsibility principle and how does it apply to components?

  * The single responsibility principle is if your component is growing to be more than one thing, then you should create smaller components within it

* What does it mean to build a ‘static’ version of your application?

  * 'static' version is taking your data model that you just created and renders it onto the page, but with no interactivity

  * You do this by building components that reuse other components and pass data using props. Props are a way of passing data from parent to child. (Do not use state for the static version)

* Once you have a static application, what do you need to add?

  * You will need to be able to implement state into your app

* What are the three questions you can ask to determine if something is state?

  * Is it passed in from a parent via props?

  * Does it remain unchanged over time?

  * Can you compute it based on any other state or props in your component?

* How can you identify where state needs to live?

  * For each piece of state in your applicaton:

    * Find every component that renders something based on the state

    * Find a common owner component (the highest in the hierarchy)

    * Either the common owner or another component higher up in the hierarchy should own the state

    * If you cannot find the component, create a new component soley for holding the state and add it somewhere in the hierarchy above the common owner component

* Some information taken from [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)