[[!4.2 Data Structures]]

Key Data Structures

|Data Structure|Description|
|---|---|
|Array|A collection of elements stored at contiguous memory locations.|
|Linked List|A sequence of nodes where each node points to the next node.|
|Stack|A collection of elements with LIFO access.|
|Queue|A collection of elements with FIFO access.|
|Graph|A collection of nodes connected by edges, can represent various relationships.|
|Tree|A hierarchical structure with nodes connected by edges, with a root node and child nodes.|

Key Operations

| Operation | Description                                                    |
| --------- | -------------------------------------------------------------- |
| Push      | Adds an element to the top of the stack.                       |
| Pop       | Removes the top element from the stack.                        |
| Enqueue   | Adds an element to the back of the queue.                      |
| Dequeue   | Removes the front element from the queue.                      |
| Traverse  | Visits each node in a data structure, such as a graph or tree. |

Key Algorithms

- **Breadth-First Search (BFS)**: A graph traversal algorithm that explores all neighbours of a node before moving to the next level.
- **Depth-First Search (DFS)**: A graph traversal algorithm that explores as far as possible along each branch before backtracking.
- **Hash Function**: A function that converts input data into a fixed-size value, used in hash tables to determine the index for storing data.

Key Applications

- **Graphs**: Used in social networks, transport networks, and operating systems.
- **Trees**: Used for managing folder structures, routing tables, and expression parsing.
- **Hash Tables**: Used for fast data retrieval and indexing, especially in databases.

Facts to Memorize

- Hash function: A function that converts an input (or 'key') into a fixed-size string of bytes.
- Collision resolution methods: Linear probing and chaining.
- Binary Search Tree properties: Left child < Parent < Right child.
- Stack operations: push(), pop(), peek(), isEmpty(), isFull().
- Queue operations: enQueue(), deQueue(), peek(), isEmpty(), isFull().

Reference Information

- Time complexity for searching in a hash table: O(1) on average, O(n) in the worst case due to collisions.
- Time complexity for inserting in a binary search tree: O(log n) on average, O(n) in the worst case.
- Depth-First Search (DFS) and Breadth-First Search (BFS) are two common graph traversal algorithms.

Problem-Solving Steps

##### Adding Data to a Binary Search Tree

1. Start with the root node.
2. Compare the value to be inserted with the current node's value.
3. If the value is less, move to the left child; if greater, move to the right child.
4. Repeat until you find an empty spot.
5. Insert the new value at the identified spot.

##### Removing Data from a Binary Search Tree

1. Search for the node containing the value to be removed.
2. If the node is a leaf, remove it directly.
3. If it has one child, replace it with its child.
4. If it has two children, find the in-order successor, replace the node, and delete the successor.

Key Terms/Concepts

- **Array**: An ordered, static set of elements that can only store one data type.
- **Linked List**: A dynamic data structure consisting of nodes, where each node contains data and a pointer to the next node.
- **Stack**: A last in first out (LIFO) data structure where items can only be added or removed from the top.
- **Queue**: A first in first out (FIFO) data structure where items are added to the back and removed from the front.
- **Graph**: A set of vertices connected by edges, which can be directed or undirected, and weighted or unweighted.