[GitHub](https://batoolalali.github.io/401-Reading-notes/class19)

# Message Queues
is tasked with routing events and messaging between clients.
- Any connected client can “publish” a message into the server.
- Any connected client can “subscribe” to receive messages by type.

- The Queue server has the ability to see which clients are connected, to which Queues they are attached and further, to which events they are subscribed.

### What is a message?
- A message is a package of information, categorized by queue and event
- queue: Which general bucket does this message belong
- event: What event has happened
- payload: data associated with the event

### Real Time vs Queued Messaging

- **messages** are simply brokered by the server. They come in, are processed and are immediately broadcast out to subscribers
- A true **Queue** will keep track of the delivery status of every event/message. Any broadcast that is not received by a subscriber will remain in the queue until it can be delivered. 