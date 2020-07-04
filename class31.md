[Github](https://batoolalali.github.io/401-Reading-notes/class31)

# Hooks
- React hooks allow to to easily create and manage state in a functional component.
-  A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.
- Hooks are JavaScript functions, but they impose additional rules:
Hooks must be named with a use prefix.
Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.

- useState()
Returns a stateVariable and setterFunction for you to use to manage state in a functional component

### What does calling useState do? 
It declares a “state variable”. Our variable is called count but we could call it anything else, like banana. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.

- The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API. 