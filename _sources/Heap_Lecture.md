# Heap

## Notion
A heap is a complete binary tree that satisfies the Heap Property, ensuring the value of each node is either greater than or equal to (Max Heap) or less than or equal to (Min Heap) its children.

## Core explanation
- Properties: In a Max Heap, the root always contains the maximum value, while in a Min Heap, it contains the minimum, allowing constant-time access to the extremal element.
- Index Relations: For a node at index i, its parent is at (i−1)//2, its left child at 2i+1, and its right child at 2i+2.
- Operations: Basic operations include insertion (adding an element and moving it up) and deleteMax (removing the root and moving the last element down), both utilizing the heapify process to maintain the heap property.
- Applications: Heaps are primarily used for implementing priority queues and the Heap Sort algorithm.