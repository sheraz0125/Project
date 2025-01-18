Stack and Queue Implementation Using Linked List
Overview
This project demonstrates the implementation of two fundamental data structures—Stack and Queue—using a Linked List. These data structures are essential for various computer science algorithms and are typically implemented using arrays or linked lists. The purpose of this project is to provide hands-on experience with linked lists, their operations, and how they can be used to create Stack and Queue.
Table of Contents
1.	How to Run the Program
2.	Purpose of the Code
3.	Time Complexity
4.	Features
5.	Usage Example
6.	Contributors
7.	License
How to Run the Program
1.	Clone the repository to your local machine:
bash
Copy
git clone https://github.com/yourusername/stack-queue-linkedlist.git
2.	Navigate to the project directory:
bash
Copy
cd stack-queue-linkedlist
3.	Compile and run the program:
o	For Python:
o	Bash
4.	Copy
5.	python stack_queue_linkedlist.py


python stack_queue_linkedlist.py
Purpose of the Code
The purpose of this code is to implement Stack and Queue data structures using Linked Lists. These structures will be used to demonstrate the following concepts:
•	Stack (LIFO): Last-In-First-Out behavior, where elements are added and removed from the same end (top of the stack).
•	Queue (FIFO): First-In-First-Out behavior, where elements are added at the rear and removed from the front.
By implementing these structures using a linked list, the program avoids the limitations of fixed-size arrays and allows for dynamic memory usage.
Features:
•	Stack implementation with operations: push(), pop(), peek(), and isEmpty().
•	Queue implementation with operations: enqueue(), dequeue(), front(), and isEmpty().
Time Complexity
•	Stack Operations:
o	push(): O(1) — Adding an element to the stack is a constant-time operation because it happens at the top of the stack.
o	pop(): O(1) — Removing an element from the stack is also a constant-time operation.
o	peek(): O(1) — Accessing the top element is a constant-time operation.
•	Queue Operations:
o	enqueue(): O(1) — Adding an element to the queue is a constant-time operation when using a linked list.
o	dequeue(): O(1) — Removing an element from the front of the queue is a constant-time operation.
o	front(): O(1) — Accessing the front element is a constant-time operation.
•	Space Complexity: O(n) — Each element requires one node, so the space complexity is proportional to the number of elements stored in the stack or queue.


Usage Example



Stack Example:

python
Copy
# Stack with Linked List
stack = Stack()
stack.push(10)
stack.push(20)
stack.push(30)
print(stack.peek())  # Output: 30
print(stack.pop())   # Output: 30
print(stack.isEmpty())  # Output: False
Queue Example:
python
Copy
# Queue with Linked List
queue = Queue()
queue.enqueue(10)
queue.enqueue(20)
queue.enqueue(30)
print(queue.front())  # Output: 10
print(queue.dequeue())  # Output: 10
print(queue.isEmpty())  # Output: False

