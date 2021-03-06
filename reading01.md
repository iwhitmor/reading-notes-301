# Introduction to React Components

## Component Based Architecture

### What is a component?
  
- A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

- A compoenent is a software object that is intended to interact with other components

### What are the charactistics of a component?

- Reusability: Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

- Replacable: Components may be freely substituted with other similar components.

- Not context specific: Components are designed to operate in different environments and contexts.

- Extensible: A component can be extended from existing components to provide new behavior.

- Encapsulated: A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

- Independent: Components are designed to have minimal dependencies on other components.

### What are the advantages of using component based architecture?

- There are a lot of advantages to using components

  - **Ease of deployment:** As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

  - **Reduced cost:** The use of third-party components allows you to spread the cost of development and maintenance.

  - **Reusable:** The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

  - **Reliable:** The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

  - **System maintenance and evolution:** Easy to change and update the implementation without affecting the rest of the system.

  - **Independent:** Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.
  
## What is Props and How to Use in React

### What is Props short for?

- It stands for "Properties" and is used for passing data from one component to another

- Props is a special keyword in React

### How are Props used in React?

- Passing data from one component to another

### What is the flow of Props?

- Passed in a uni-directional flow from parent to child

- The data is read-only so the parent should not be changed by the child

#### All information read and used from [Component based architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm) and [What is props and how to use it in react](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)


#### Additional readings
- [React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [React: Hello World](https://reactjs.org/docs/hello-world.html)
- [Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)
- [React: Rendering elements](https://reactjs.org/docs/rendering-elements.html)
- [React: Components and props](https://reactjs.org/docs/components-and-props.html)
