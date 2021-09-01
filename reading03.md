# Passing Functions as Props

## [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?

  - creates a new array populated with the results of calling a provided function on every element in the calling array

- If I want to loop through an array and display each value in JSX, how do I do that in React?

  - Using the JS map() and using curly braces {}

- Each list item needs a unique ____.

  - A unique **STRING**

- What is the purpose of a key?

  - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

  - The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?

  - Spread syntax can be used when all elements from an object or array need to be included in a list of some kind

- List 4 things that the spread operator can do

  - Copying an array

  - Using math functions

  - Adding an item to a list

  - Combining objects

## [How to pass functions between components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?

  - Creates a function wherever the state is that he is going to change

- In your own words, what does the increment function do?

  - It takes a variable and increments it and then returns the new value

- How can you pass a method from a parent component into a child component?

  - By using props

### Additonal material:

- [Intro to React](https://reactjs.org/tutorial/tutorial.html)

- [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

#### Some information taken from websites linked above
