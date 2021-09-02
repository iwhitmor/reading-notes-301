# React and Forms

## [Forms](https://reactjs.org/docs/forms.html)

- HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state

### Controlled Components

- In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState()

- With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

### The <select> tag

- The <select> tag creates a drop-down list

## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

### Why would we use the ternary operator?

- To simplify if/else statements

- Uses less code so quicker/easier

- Rewrite to a ternary operator:

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

 x===y ? true : false

#### Some information taken from websites linked above

- Additional readings

- [React Bootstrap Forms](https://react-bootstrap.github.io/components/forms/)

- [React Docs Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)
