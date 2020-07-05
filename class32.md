[Github](https://batoolalali.github.io/401-Reading-notes/class32)

# Custom React Hooks

Custom Hooks are JavaScript functions whose names are prefixed with the word use. A custom Hook is a normal function but we hold them to a different standard. By adding the word use to the beginning, it lets us know that this function follows the rules of Hooks.

## What are custom hooks?
- Extract duplicated logic from components
- Share common functionality
- Take advantage of useEffect lifecycle


### Extracting a Custom Hook
When we want to share logic between two JavaScript functions, we extract it to a third function. Both components and Hooks are functions, so this works for them too!
- Unlike a React component, a custom Hook doesn’t need to have a specific signature. We can decide what it takes as arguments, and what, if anything, it should return. In other words, it’s just like a normal function.

- Using a Custom Hook
Our stated goal was to remove the duplicated logic.

## Common use cases – make things DRY!
- Handle forms easily
- Pre-fetch API data
- Connect to services (like socket.io, Q, etc)