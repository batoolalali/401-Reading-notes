# Linked Lists
- A Linked List is a sequence of Nodes that are connected/linked to each other.
- there are A Singly linked list, Doubly - Doubly, Node - Nodes, Next - Each node, Head - The Head and Current - The Current.

- Traversal
When traversing a linked list, you are not able to use a foreach or for loop. 
The best way to approach a traversal is through the use of a while() loop.

- Big O Notation is a way of evaluating the performance of an algorithm.

- Adding a Node
Adding O(1)
Order of operations is extremely important when it comes to working with a Linked List. 

- PS
1. When making your Node class, consider requiring a value to be passed in to require that each node has a value.
2. When making a Linked List, you may want to require that at least one node gets passed in upon instantiation. This first node is what your Head and Current will point too.

- Memory management
    - The biggest differentiator between arrays and linked lists is the way that they use memory in our machines.
    - when a linked list is born, it doesn’t need 7 bytes of memory all in one place. 
    - One byte could live somewhere, while the next byte could be stored in another place in memory altogether! 
    - Linked lists don’t need to take up a single block of memory; instead, the memory that they use can be scattered throughout.
- Growing a linked list
1. First, we find the head node of the linked list.
2. Next, we’ll make our new node, and set its pointer to the current first node of the list.
3. Lastly, we rearrange our head node’s pointer to point at our new node.