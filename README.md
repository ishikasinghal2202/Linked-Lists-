
# Linked List in C++

## Aim
To study and implement the concept of Linked Lists in C++.

## Apparatus
- Software: Visual Studio Code / Code::Blocks / Turbo C++
- Hardware: A computer system with C++ compiler installed.

## Objectives
- Understand the concept of dynamic memory allocation in C++.
- Learn how to create, traverse, insert, and delete nodes in a linked list.
- Explore the advantages of linked lists over arrays.
- Implement basic operations on a singly linked list.

## Theory
A **linked list** is a linear data structure where elements (nodes) are connected using pointers.  
Each node contains:
1. **Data** – The actual value stored in the node.
2. **Pointer (next)** – The address of the next node.

Types of Linked Lists:
- **Singly Linked List** – Each node points to the next node, last node points to NULL.
- **Doubly Linked List** – Each node has pointers to both previous and next nodes.
- **Circular Linked List** – Last node points back to the first node, forming a circle.

Linked lists are dynamic in nature and allow efficient insertion and deletion compared to arrays.

### Difference b/w array & linked list
| Feature            | Array                               | Linked List                        |
| ------------------ | ----------------------------------- | ---------------------------------- |
| Memory Allocation  | Static (fixed size)                 | Dynamic (grows/shrinks at runtime) |
| Access Time        | O(1) (direct indexing)              | O(n) (sequential traversal)        |
| Insertion/Deletion | Costly (shifting elements required) | Efficient (change pointers only)   |
| Memory Utilization | May waste memory                    | Uses memory as needed              |


## Algorithm
### To Insert a Node at the End:
1. Start.
2. Create a new node using dynamic memory allocation.
3. Assign data to the new node.
4. If the list is empty:
   - Make the new node as head.
5. Else:
   - Traverse the list until the last node.
   - Make the last node’s `next` point to the new node.
6. End.

### To Traverse a Linked List:
1. Start with the head node.
2. While the current node is not NULL:
   - Print the data of the current node.
   - Move to the next node.
3. End.

## Conclusion
The implementation of linked lists in C++ provides an understanding of dynamic data structures and memory management.  
Unlike arrays, linked lists allow efficient insertions and deletions at any position, making them a flexible alternative for handling dynamic datasets.
*/

