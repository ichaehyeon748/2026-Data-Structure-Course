# Linked List

## Notion
A Linked List is a collection of Nodes, where each node contains both data and a reference (pointer) to the next node in the sequence.

## Core explanation
- Dynamic Structure: Unlike arrays, linked lists are dynamic; they do not have a fixed size and elements are not stored in contiguous memory.
- Trade-offs: They allow for easier insertion and deletion (O(1) if the position is known) because no elements need to be shifted
. However, accessing a specific element is slow (O(n)) because you must traverse the list from the head.
- Types: Common types include Singly Linked Lists (one-way), Circular Linked Lists (the last node points back to the head), and Double Linked Lists (pointers to both next and previous nodes).