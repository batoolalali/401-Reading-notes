https://batoolalali.github.io/401-Reading-notes/class07

## Express Routing

- Event driven system
When a get event happens in our server, on route, run the function…

- The Request Object

- The Response Object
Responsible for sending data back to the browser
Has methods like send() and status() that Express uses to format the output to the browser

- Express Middleware
    - A series of functions that the request “goes through”
    - Each function receives request, response and next as parameters
    - Types of middleware: 
        - Application
        - Route

- Application Middleware: Error Handling, Bringing in other routes, Applies Defaults, JSON, Body and Form Parsing and Runs on every request.

- CRUD Operations with REST and Express
    - CREATE: app.post('/resource')
    - READ: app.get('/resource')
    - UPDATE: app.put('/resource/:id')
    - DESTROY: app.get('/resource/:id')

- Server Testing
export your server as a module in a library

- Test Pyramid
Server Testing crosses boundaries
  - Units: Server Internal Functions
  - Integration: How it connects to other services
  - Acceptance