
## Data structures:
- Data structures are essential for organizing and storing data efficiently in computer memory.
- They enable efficient data management, organization, and abstraction, leading to improved performance and ease of access.

## Classification:
- Data structures are classified into linear and non-linear types.
- Linear data structures include arrays, linked lists, stacks, and queues, storing data sequentially.
- Non-linear data structures include trees, graphs, and hash tables, allowing for more complex relationships between data elements.

## Types:
### Linear Data Structures:
- **Arrays:** Collection of elements of the same type stored in contiguous memory.
- **Linked Lists:** Elements linked together by pointers, enabling dynamic insertion and deletion.
- **Queues:** FIFO structure for adding and removing elements.
- **Stack:** LIFO structure for adding and removing elements.

### Non-Linear Data Structures:
- **Tree:** Hierarchical structure with nodes having multiple child nodes.
- **Graph:** Nodes connected by edges representing relationships.
- **Hash Table:** Maps keys to values using a hash function for fast lookup and insertion.

## Applications:
- Widely used in database management, operating systems, compiler design, artificial intelligence, graphics, and multimedia.
- Essential for efficient algorithm design and optimization.

## Popular Examples:
- Arrays, matrices, linked lists, stacks, queues, trees, graphs, and hash tables.
- Detailed explanations and examples provided for each data structure.

## Advanced Data Structures:
- Includes advanced lists, segment trees, tries, binary indexed trees, suffix arrays, AVL trees, splay trees, B trees, red-black trees, and k-dimensional trees.
- Each data structure addresses specific requirements for efficient data storage, retrieval, and manipulation.

  ---
  # Linked List

## What is Linked List?

- **Node Structure:** Each node consists of:
  - Data: Holds the value associated with the node.
  - Next Pointer: Stores the memory address of the next node.
- **Head and Tail:** Head points to the first node, while the tail points to NULL, indicating the end of the list.

## Why Linked List?

- **Dynamic Data Structure:** Memory allocation can be adjusted at runtime.
- **Ease of Insertion/Deletion:** No need to shift elements, just update pointers.
- **Efficient Memory Utilization:** Size adjusts as needed, avoiding memory wastage.
- **Implementation:** Can be used for various data structures like stacks, queues, graphs, hash maps, etc.

### Example:
- Sorted list in an array `[1000, 1010, 1050, 2000, 2040]`.
- Inserting a new ID `1005` requires shifting elements after `1000`, affecting efficiency.

## Types of Linked Lists:

1. **Single-linked list:** Nodes have a reference to the next node.
2. **Double-linked list:** Nodes have references to both next and previous nodes.
3. **Circular linked list:** Last node points back to the head, forming a circular structure.

## Operations on Linked Lists:

- **Insertion:** Adjust pointers to maintain sequence.
- **Deletion:** Adjust pointers to bridge the gap.
- **Searching:** Traverse from head until the value is found or end of the list.

## Complexity Analysis:

- **Time Complexity:** O(n)
- **Auxiliary Space:** O(n)

## Advantages:

- **Dynamic Size:** Grows or shrinks dynamically.
- **Insertion/Deletion:** Efficient for large lists.
- **Flexibility:** Easily reorganized without contiguous memory.

## Disadvantages:

- **Random Access:** No direct access to elements by index.
- **Extra Memory:** Requires additional memory for pointers.


