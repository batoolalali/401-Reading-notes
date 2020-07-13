[Github](https://batoolalali.github.io/401-Reading-notes/class38)

# Redux - Asynchronous Actions
- Using Redux actions to connect to remote APIs via Thunk Middleware
Normally, action generators return a function

- you may need to get something from a remote api, you’ll need your actions to do some asynchronous action before you dispatch it to the reducer. we want to set it up like this, where the action you dispatch from your React App returns a function, not an actual action object, which is what Redux `expects` and `requires`

-  implement special redux middleware, called “thunk”, which inspects every dispatched action and then either lets it go through

- With a plain basic Redux store, you can only do simple synchronous updates by dispatching an action. Middleware extend the store's abilities, and let you write async logic that interacts with the store.

- Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

- What’s a thunk?!
A thunk is a function that wraps an expression to delay its evaluation.