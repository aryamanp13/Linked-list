# Linked-list

# Aim: To perform programs using notes

## Theory:

Definition:
A linked list is a fundamental data structure used to store a collection of elements. Unlike arrays, where elements are stored in contiguous memory locations, linked lists store elements in nodes scattered throughout memory.

Each node contains two parts:

Data: The actual value of the element.

Pointer (or Reference): A reference (or pointer) to the next node in the list.

Types of Linked Lists

Singly Linked List: Each node points to the next node in the sequence, and the last node points to NULL.

Doubly Linked List: Each node points to both the next and the previous node. This allows traversal in both directions.

Circular Linked List: The last node points back to the first node, forming a circle. It can be singly or doubly linked.

Basic Operations
1. Insertion: Adding elements to the list
At the beginning: Insert a node at the head of the list.
At the end: Traverse the list and insert a node at the tail.
At a specific position: Insert a node at a given position.
2. Deletion: Removing elements from the list
From the beginning: Remove the head node.
From the end: Traverse to the second-last node and set its next pointer to NULL.
From a specific position: Remove the node at a given index.
4. Traversal: Visit each node in the list to process or display its data.
5. Searching: Find an element in the list by comparing the value of each node’s data.
6. Reversing: Reverse the order of nodes in the list.

 ## Algorithm:
 Algorithm for implementation of linked list
 
 Step 1: Define a Class for the Node
Create a class Link to represent a node of the linked list.

Inside the class:
Declare an integer data to store the value of the node.
Declare a pointer next of type Link* to store the address of the next node.

Step 2: Define the Constructor
Create a constructor Link(int num) that takes an integer parameter:
Set data equal to num (the value passed during object creation).
Initialize next to NULL, meaning that the current node doesn’t point to any other node.

Step 3: Create a Node in Main Function
In the main function:
Declare a pointer l1 of type Link* and dynamically allocate memory for it using new.
Initialize the node with the value 6 by calling the constructor.

Step 4: Print Node Data and Pointer to Next Node
Use cout to print the value of the node (l1->data).
Print the address stored in next using l1->next, which should be NULL for this node.

Step 5: End the Program
Return 0 to indicate successful completion of the program.
