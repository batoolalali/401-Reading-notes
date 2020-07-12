[Github](https://batoolalali.github.io/401-Reading-notes/class37)

# Redux - Combined Reducers
- Combined Reducers
Combined reducers is nothing more than pulling in more than one reducer from source and creating a keyed object from them.
Once done, any component can reach into the store and get either one, both, or all 

- What’s the point?
Obey the Single Responsibility Principle
Each reducer really should have only 1 part of state to manage

- Each reducer technically has it’s own actions and creators.
However, they can cross over and both be dispatched.
In this example, if an action of type ‘RESET’ is ever dispatched by any action creator, both of the reducers would actually respond.
This can be` very powerful, as often times actions are valid for multiple reducers, but this behavior needs to be well understood or it’ll cause unintended consequences.