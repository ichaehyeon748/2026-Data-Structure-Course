# Stack and Queue

## Notion
- Stack: A Stack is a linear data structure that follows the Last In First Out (LIFO) principle, meaning the last element added is the first one to be removed
- Queue: A Queue is a linear data structure that follows the First In First Out (FIFO) principle, where elements are inserted at one end (rear) and removed from the other (front).

## Core explanation
- Stack
    - Basic Operations: The primary operations are push() (adding an item to the top) and pop() (removing the item from the top).
    - Implementation: Stacks can be implemented easily using Python's built-in lists or by using a linked list where the top of the stack is the first node.
    - Applications: Stacks are used in managing recursive function calls, browser history (the back button), and "undo" operations in software.
- Queue
    - Basic Operations: The primary operations are enqueue() (adding an element to the rear) and dequeue() (removing an element from the front).
    - Implementation: While a Python list can be used for a queue, using pop(0) for dequeueing causes overhead because all other elements must shift. A circular linked list is often preferred for more efficient implementation.
    - Applications: Queues are essential for job scheduling, printer management, and handling waiting lines in systems like call centers.

## Lab session
- [Stack_Queue_Lab](6_Stack_Queue)