[GitHub](https://batoolalali.github.io/401-Reading-notes/class17)

# TCP Servers

### Event Queues
Much of the NodeJS architecture is built around the use of events >>> All objects that emit events in NodeJS are instances of the EventEmitter constructor >>> EventEmitter’s are a great way to handle controlling asynchronous events. 
Functions can be registered as listeners for an event on instances of the EventEmitter class >>> These instances can emit events and pass the listener’s data.

### OSI Model
Open Systems Interconnection was developed as a seven layer model. This seven layer OSI model has continued to accurately describe the different processes in computer networking.

##### Layer architecture
- Layer 1: Physical Layer (USB, Bluetooth, Ethernet physical layer, SMB, Telephone network modem)
- Layer 2: Data Link Layer (Ethernet and IEEE 802.11 wireless LAN)
- Layer 3: Network Layer (IP and ICMP)
- Layer 4: Transport Layer  (TCP and UDP)
- Layer 5: Session Layer (NetBios and Remote Procedure Protocol (RPC)
- Layer 6: Presentation Layer (Strings encoded with null terminated strings vs Strings defined by an Integer Length)
- Layer 7: Application Layer ( HTTP, IMAP, POP, SSH)

##### Internet Protocol Suite
The Internet Protocol Suite is the conceptual model for the protocols used by the internet. It is often referred to as TCP/IP because the IP and TCP were the original protocols in the suite. The Internet Protocol Suite is described using four layers - Link, Internet, Transport, and Application. 

##### TCP
The Transmission Control Protocol is widely used by application layer protocols in the Internet Protocol Suite. TCP creates a two way communication between two hosts and provides 
- reliable
- ordered
- error checked byte streams between the applications.
