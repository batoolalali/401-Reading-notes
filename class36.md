[Github] https://batoolalali.github.io/401-Reading-notes/class36 

# Redux Store
store  is where your application state is, well, stored.
- React uses  reducers  to hold and manage state. Reducers typically manage just one part of the larger application state.

- React applications with Redux dispatch  actions   like an event  with  payload   data . An action creator function as shown below always returns an action object with the action type to perform and the data to perform it with. When your component wants to modify state, it  Dispatches   calls  an action and sends whatever payload  data  it needs to, to the reducer.

- Components subscribe to the store and get to use actions with a bit of boilerplate code.
 - When an action is dispatched, a reducer responds to it, and receives that payload, where it then operates on state using it.