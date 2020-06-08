[GitHub](https://batoolalali.github.io/401-Reading-notes/class15)

# Trees

## Common Terminology
- Node - A node is the individual item/data that makes up the data structure
- Root - The root is the first/top Node in the tree
- Left Child - The node that is positioned to the left of a root or node
- Right Child - The node that is positioned to the right of a root or node
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not contain any children
- Height - The height of a tree is determined by the number of edges from the root to the bottommost node

## Traversals
- Depth First: is where we prioritize going through the depth (height) of the tree first.methods for depth first traversal:
 - Pre-order: `root >> left >> right`
 - In-order: `left >> root >> right`
 - Post-order: `left >> right >> root`

- Breadth First: iterates through the tree by going through each level of the tree node-by-node.

## Binary Trees
restrict the number of children to two

- Big O
 - The Big O time complexity for inserting a new node is O(n). 
 - The Big O space complexity for a node insertion using breadth first insertion will be O(w), where w is the largest width of the tree.

A “perfect” binary tree is one where every non-leaf node has exactly two children. 
The maximum width for a perfect binary tree, is 2^(h-1), where h is the height of the tree. Height can be calculated as log n, where n is the number of nodes.

## Binary Search Trees
A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

- Big O
 - The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), h: height.
 - The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.