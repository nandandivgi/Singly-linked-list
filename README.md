# Singly-linked-list
Linked List can be defined as collection of objects called nodes that are randomly stored in the memory.
A node contains two fields i.e. data stored at that particular address and the pointer which contains the address of the next node in the memory.
The last node of the list contains pointer to the null.
## Why use linked list over array?
* Better use of Memory: From a memory allocation point of view, linked lists are more efficient than arrays. Unlike arrays, the size for a linked list is not pre-defined, allowing the linked list to increase or decrease in size as the program runs.
* Fast Insertion/Deletion Time: Inserting a new node to the beginning or end of a linked list takes constant time (O(1)) as the only steps are to initialize a new node and then update the pointers. Likewise, if there were a tail pointer (similar to the head pointer) insertion to the end of the linked list would also be O(1). Similarly, deletion of the nodes at the beginning and end of the linked list take constant time while deleting a node in the middle of the linked list takes linear time.
