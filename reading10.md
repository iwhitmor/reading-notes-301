# In Memory Storage

## [Understanding the JavaScript Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)

* What is a ‘call’?

  * A function invocation

* How many ‘calls’ can happen at once?

  * One at a time

* What does LIFO mean?

  * Last in, first out data structure

* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![Example of call stack](http://url/to/img.png)

* What causes a Stack Overflow?

  * A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## [JavaScript Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

* What is a ‘refrence error’?

  * When you use a variable that is not yet declared. Common when useing const and let.

* What is a ‘syntax error’?

  * When you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse

* What is a ‘range error’?

  * Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

* What is a ‘tyep error’?

  * Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

* What is a breakpoint?

  * Can be achieved by putting a debugger statement in your code in the line you want to break. 

* What does the word ‘debugger’ do in your code?

  * You can debug your code using the console or certain VS Code tools. You can also put a debugger statement in your code where you might want it to break. You can run the debugger by pressing F5 or pressing the green play button.

## Additional Readings

* [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

### Some information taken from the websites listed above
