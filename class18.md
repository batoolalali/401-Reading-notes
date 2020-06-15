[GitHub](https://batoolalali.github.io/401-Reading-notes/class18)

# Socket.io
It is a library which enables real-time and full duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface.

### Web Sockets
A communication Protocol which provides bidirectional communication between the Client and the Server over a TCP connection, WebSocket remains open all the time so they allow the real-time data transfer. When clients trigger the request to the Server it does not close the connection on receiving the response, it rather persists and waits for Client or server to terminate the request.

### Messaging
Standard node events are sent with emit() and received with on()
In an event driven node app, the entire app is in memory, and (through a common event pool), all parts of your application can emit and hear events, communicating with each other. However, no outside application can participate in these events natively.

- Not every client will have a listener for every event.
- The server may not have a listener for every event a client sends.

