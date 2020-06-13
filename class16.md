[GitHub](https://batoolalali.github.io/401-Reading-notes/class16)

# Event Driven Applications

- Everything in JS is an object
- Most actions in JS are event driven
    - UI Events
    - Express Routes
    
### Emitting Events
- Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.

- Much of the Node.js core API is built around an idiomatic asynchronous event-driven architecture in which certain kinds of objects called **emitters** emit named events that cause Function objects **listeners** to be called.

- Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away. 