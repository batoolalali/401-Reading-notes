[Github](https://batoolalali.github.io/401-Reading-notes/class33)

# Context API

- Context provides a means of passing state down the component tree through a Provider/Consumer relationship.
- At as high a level as makes sense, a “provider” can make it’s state available, along with means of altering it (methods).
- At the lower levels any component can “opt-in” and become a “consumer” and receive this.state from context.

### Two ways to attach to context:
1. Wrap your component with, and use a function to “get” the context object itself.
2. Statically declare a connection to the context provider and then use this.context to connect to state from the context provider

- Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
- Context is primarily used when some data needs to be accessible by many components at different nesting levels.
- Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching `Provider` above it in the tree.
- The contextType property on a class can be assigned a Context object created by `React.createContext()`. 