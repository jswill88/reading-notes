# Linked Lists

### [Linked Lists Code Fellows](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
* A Linked List is a sequence of `Nodes` connected to each other. Each node references the next.
* __Singly__ linked lists refer to the next node in the list, and __Doubly__ link to the next and previous nodes.
* __Next__ is the property that references the next node in the list
* The __Head__ is the first node in the list
* __Current__ is the node that is being looked at
* It is best to use a while loop to traverse a Linked List
* Big O for time for traversing is O(n)

### [What's A Linked List Anyway? Part 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
* Linked lists are an example of a __linear data structure__, meaning it can be traversed sequentially
* An array needs bytes of memory all in the same spot. An array with a length of 10 would need 10 bytes next to each other
* The memory a linked list uses can be scattered, which allows it to grow and change shape without being moved
* The end of a linked list points to null
* Each node only contains its data and the reference to the next node
* A circular linked list does not end with null. The last node points back to the beginning of the linked list

### [What's A Linked List Anyway? Part 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
* Big O Notation is a way of evaluating the performance of an algorithm by considering its runtime and how much memory it needs
* This is important, because programs use large amounts of data
* An O(1) function will take the same amount of time no matter how many elements are involved
* An O(n) function grows linearly in relation to the size of the input
* An O(n<sup>2</sup>) function grows exponentially in relation to the size of the input
* You are more likely to run out of space when you use an array
* Linked lists are good for adding something to the beginning of a list, as the big O will just be O(1)
