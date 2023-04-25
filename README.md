# Nodes-in-linked-list
# introduction
a linked list is a linear data structure where elements, called nodes, are connected through pointers or references to form a sequence. Each node in a linked list contains two parts: a data field that stores the element's value, and a pointer or reference that points to the next node in the sequence.

The first node in the linked list is called the head node, and the last node is called the tail node. The tail node's pointer or reference points to a null value to indicate the end of the list.

Linked lists are commonly used to implement dynamic data structures, such as stacks, queues, and hash tables. They can also be used to implement other abstract data types, such as graphs and trees.

The advantage of using linked lists over arrays is that linked lists can dynamically adjust their size, whereas arrays have a fixed size that must be declared before the program runs. However, linked lists require more memory overhead because they store pointers or references to the next node in addition to the data value.
# Algoritm 
1. Create a structure named "node" that has two members, an integer "data" and a pointer to the next node "next".
2. Create a pointer variable named "start" that points to the first node of the list.
3. Implement three functions to add a node at the end, add a node at the beginning and display the elements of the list.
4. In the "addatend" function, allocate memory for a new node, assign the data to it, and traverse the list to find the last node. Set the "next" pointer of the last node to the newly created node.
5. In the "addatstart" function, allocate memory for a new node, assign the data to it, and set its "next" pointer to the current start node. Set the "start" pointer to the newly created node.
6. In the "display" function, traverse the list and print the data and next address of each node.
7. In the main function, create a new node and assign it to the "start" pointer. Then add nodes at the end and beginning of the list and display the final list.
# Applications:
1. Stacks and queues: A singly linked list can be used to implement both stacks and queues.
2. Hash tables: A singly linked list is used to implement a hash table, where each element of the table is a linked list.
3. Symbol tables: A singly linked list is used to implement a symbol table
# Screenshot
![p1](https://user-images.githubusercontent.com/126184012/234283000-09224512-549f-4c19-a642-fffd72ffa9eb.png)
