[Github](https://batoolalali.github.io/401-Reading-notes/class39)

# Redux Toolkit in Action
- The makers of Redux have recognized that Redux is complicated and have introduced a “Batteries Included, Highly Opinionated” framework for making stores called the Redux Toolkit.

This toolkit specifies a few different means of building a reducer and action set that work well together and are easier to understand and integrate

- we can replace the plain Redux createStore function with RTK's configureStore. This will automatically set up the Redux DevTools Extension for us.

- we start by copying the Redux "todos" source code to a fresh Create-React-App project, and adding Prettier to the project to help make sure the code is formatted consistently. 