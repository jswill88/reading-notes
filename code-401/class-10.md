# Stacks and Queues
### Stacks
* A stack consists of nodes that reference the next node in the stack but not the previous
* Nodes put on the stack are pushed, and nodes taken off the stack are popped
* When you peek, you see the top value of the stack
* `IsEmpty` will return `true` if the stack is empty
* Stacks are First In Last Out (FILO)/Last In First Out (LIFO)
* The topmost item is called the `top`, and when you pop the top, you set the next top as top.next
* When you push a new top (O(1)) you set the new node as the new top, and it's next as the old top
* To pop, check if the stack is empty.
* Then make a reference to the same node that `top` points to
* Then reassign top to next.
* To peek, return top.value
* If top is NULL, isEmpty is true

### Queue
* Enqueue - nodes that are added to the queue
* Dequeue - nodes that are removed from the queue
* Front is the first node of the queue
* Rear is the last node of the queue
* Peek to view the front node in the queue
* isEmpty is true when the queue is empty
* Queues are FIFO
* Enqueue by adding to the end of the queue - change rear.next to be the new node, and make the new node the rear
* Check isEmpty before dequeueing
* Dequeueing is similar to taking a node off a stack
* Return the value after dequeueing

