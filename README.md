# Implementation-of-Singly-Linked-List-in-C-
This program implements a singly linked list with a data structure of nodes that are self- referential.

Implementation of Singly Linked List in C++

Description

This program implements a singly linked list with a data structure of nodes that are self- referential.

Explanation of the program:

Data structures that are constructed from self-referential nodes are called singly linked lists. Every node in the list contains both the data and the next list node's reference. In order to access the full linked list, only the first node of the list must be referenced. In other words, this is called the head of the linked list. In the last node of the list, it stores NULL since it points to nothing.

Linked list nodes are formed by structure nodes. 
There is a pointer to the next node of the linked list in the data.
Data is inserted at the beginning of the linked list using the function insert(). 
The new_node is created and the number is inserted into its data field. It is then pointed to by the new_node. 
A linked list begins at the head, which is the new_node.
A linked list is displayed using the display() function. 
Head is the pointer to the first element. 
As it passes from one node to the next, it is printed continuously until all of the node's values are displayed. 
Calling insert() first inserts values into the linked list in the function main(). 
Once the list has been displayed, call insert() again. 

Insert numbers are:

356
1100
718
290
975

Test Case Study (Run Program)

After running the program:

(Output without commas): The linked list is as follows: 975 290 718 1100 356
