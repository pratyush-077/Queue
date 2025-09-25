# Pratyush Saha
# Prn:24070123078
# Experiment-18


# 📘 Queue in C++

This repository contains a simple Queue implementation in C++ using arrays.
It demonstrates the basic enqueue, dequeue, and display operations in a fixed-size queue.




# 🚀 Introduction

A Queue is a linear data structure that follows the FIFO (First In, First Out) principle.

Enqueue → Insert element at the rear.

Dequeue → Remove element from the front.

Display → Print all elements of the queue in order.


Applications of queues include task scheduling, resource management, and handling requests in real-time systems.



# 📂 File in this Repository

Queue.cpp → Contains implementation of a queue using arrays with functions for enqueue, dequeue, and display.
# 🔎 Algorithm

Enqueue (Insert element at rear)

1. Check if the queue is full:

If rear == size - 1, print "Queue is full".



2. If the queue is empty (front == -1), set both front and rear = 0.


3. Else, increment rear and insert the element at ar[rear].




---

Dequeue (Remove element from front)

1. Check if the queue is empty:

If front == -1 or front == rear + 1, print "Queue is empty" and return ERROR.



2. Else, return the element at ar[front].


3. Increment front to point to the next element.




---

Display Queue Elements

1. If queue is empty, print "Queue is empty".


2. Else, iterate from front to rear and print each element.
# 🏁 Conclusion

This program demonstrates the fundamental operations of a queue in C++ using arrays.

It highlights insertion (enqueue), deletion (dequeue), and traversal (display).

While this example uses a fixed-size array, queues can also be implemented dynamically using linked lists or circular arrays for better memory efficiency.


Understanding queues is essential for learning more advanced data structures like priority queues and deques.
