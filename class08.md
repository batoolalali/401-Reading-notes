- index.js: `$npm init` sets the main entry point of the module to index.js so they end up naming their main entry point index.js It means *there's one less thing to do*.

- server.js: If your node package is not going to be consumed by another package, but rather is a stand-alone app, then if you call your main entry point server.js, then you can issue `$ npm start` and start your app. `$npm start` will run your the server.js file by default. 

- server model is a distributed application structure that partitions tasks or workloads between the providers of a resource or service, a web server serves web pages.

- Routing refers to how an application’s endpoints (URIs) respond to client requests.

- Route handlers
You can provide multiple callback functions that behave like middleware to handle a request. The only exception is that these callbacks might invoke next('route') to bypass the remaining route callbacks.
- Route middleware in Express is a way to do something before a request is processed.

- When a request comes in to the server, it loops through each handler in the order it was added until it finds one that can handle the request.
