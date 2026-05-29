# Recursion

## Notion
Recursion is an algorithmic technique where a function calls itself, directly or indirectly, to solve a problem by breaking it down into smaller subproblems of the same type.

## Core explanation
- Base Condition: Every recursive function must have a "stop condition" known as the base condition; without it, the function will call itself infinitely and cause a stack overflow error.
- Memory Usage: Recursion typically uses more memory than iteration because every function call is added to the system's LIFO stack, keeping values there until the call is finished.
- Efficiency: Some recursive solutions, like the Fibonacci series, can be highly inefficient (O(2^n)) because they perform many duplicate computations.

## Lab session
- [Recursion_Lab](3_Recursion_Lab)