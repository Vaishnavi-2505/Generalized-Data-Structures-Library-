# Generalised Data Structures Library

**Project Name:** Created Self Data Structures
**Technology:** C++ Programming
**Author:** Vaishnavi D Shingare

---

## 📌 Project Overview

This project is a **C++ library of generic data structures** that provides object-oriented implementations of both linear and non-linear data structures.

It offers ready-to-use functionalities for fundamental as well as advanced operations. The library is designed using **C++ templates**, making it reusable with different data types.

The implementation follows **Object-Oriented Programming (OOP)** principles such as encapsulation, modularity, and extensibility, making it suitable for both academic learning and real-world application development.

---

## 🚀 Key Features

### 1. Linear Data Structures

* Singly Linear Linked List
* Singly Circular Linked List
* Doubly Linear Linked List
* Doubly Circular Linked List
* Stack (LIFO)
* Queue (FIFO)

### 2. Non-Linear Data Structures

* Binary Search Tree (BST)

  * Insert
  * Delete
  * Search
  * Tree Traversals

### 3. Algorithms

#### Searching

* Linear Search
* Binary Search

#### Sorting

* Bubble Sort
* Optimized Bubble Sort
* Selection Sort
* Insertion Sort

### 4. Generic Implementation

* Uses **C++ Templates** for type independence.
* The same implementation can work with:

  * Integers
  * Floats
  * Strings
  * Custom objects

### 5. Library Format

* Designed as a reusable C++ library.
* Can be linked with client applications.
* Provides modular and reusable implementations.

---

# 🎯 Learning Outcomes

Through this project, I gained practical knowledge of:

* C++ Object-Oriented Programming (OOP)
* Classes and Objects
* Encapsulation
* Generic Programming
* C++ Templates
* Linear Data Structures
* Non-Linear Data Structures
* Searching Algorithms
* Sorting Algorithms
* Reusable Library Design
* Modular Software Development

---

# 💡 Motivation & Problem Statement

Every Computer Science student and software developer needs to understand and use data structures such as linked lists, stacks, queues, trees, and searching and sorting algorithms.

Although C++ provides the **STL (Standard Template Library)**, beginners may find it difficult to understand the internal working of these data structures because the implementation details are hidden behind abstract interfaces.

Therefore, this project focuses on two main purposes:

### 1. Educational Purpose

To help learners understand the **internal working of data structures** by implementing them from scratch using C++.

### 2. Practical Purpose

To provide a **reusable and generic library** that can be integrated with other C++ client applications.

---

# 📚 Implemented Data Structures

## 1. Linear Data Structures

### Singly Linked List

Supports:

* Insertion
* Deletion
* Traversal

### Singly Circular Linked List

* Nodes are connected in a circular manner.
* The last node points back to the first node.

### Doubly Linked List

* Supports forward traversal.
* Supports backward traversal.
* Each node maintains links to both previous and next nodes.

### Doubly Circular Linked List

* Nodes are connected in both directions.
* The list maintains circular connections for efficient navigation.

### Stack

**Principle:** LIFO — Last In, First Out

Implemented using:

* Array
* Linked List

Operations include:

* Push
* Pop
* Display

### Queue

**Principle:** FIFO — First In, First Out

Implemented using:

* Array
* Linked List

Operations include:

* Enqueue
* Dequeue
* Display

---

# 🌳 2. Non-Linear Data Structures

## Binary Search Tree (BST)

The Binary Search Tree implementation supports:

### Insert

Adds a new node to the appropriate position in the tree.

### Delete

Removes a node from the Binary Search Tree.

### Search

Searches for a particular value in the tree.

### Tree Traversals

The following traversal techniques are implemented:

* Inorder
* Preorder
* Postorder
* Level Order

---

# 🔍 Implemented Algorithms

## Searching

### Linear Search

Searches for an element sequentially from the beginning of the collection.

### Binary Search

Searches for an element by repeatedly dividing the search range into two parts.

> Binary Search is applicable to sorted data.

---

# 🔃 Sorting

The following sorting algorithms are implemented:

### Bubble Sort

Repeatedly compares adjacent elements and swaps them when they are in the wrong order.

### Optimized Bubble Sort

An optimized version of Bubble Sort that can stop early when no swaps are required.

### Selection Sort

Selects the minimum element from the unsorted portion and places it in its correct position.

### Insertion Sort

Builds the sorted portion of the collection one element at a time.

---

# 🧩 Generic Programming

The library uses **C++ Templates** to make data structures independent of the data type.

For example:

```cpp
SinglyLL<int> obj1;
SinglyLL<float> obj2;
SinglyLL<string> obj3;
```

The same data structure implementation can therefore be reused with different types.

---

# 🏗️ Project Architecture

```text
Generalised Data Structures Library
│
├── Linear Data Structures
│   ├── Singly Linked List
│   ├── Singly Circular Linked List
│   ├── Doubly Linked List
│   ├── Doubly Circular Linked List
│   ├── Stack
│   └── Queue
│
├── Non-Linear Data Structures
│   └── Binary Search Tree
│
└── Algorithms
    ├── Searching
    │   ├── Linear Search
    │   └── Binary Search
    │
    └── Sorting
        ├── Bubble Sort
        ├── Optimized Bubble Sort
        ├── Selection Sort
        └── Insertion Sort
```

---

# 🛠️ Technologies Used

* **Language:** C++
* **Concepts:** OOP, Templates, Data Structures & Algorithms
* **Programming Paradigm:** Object-Oriented & Generic Programming
* **Library Type:** Reusable C++ Library

---

# ⭐ Project Highlights

* Generic implementation using C++ Templates
* Object-oriented design
* Linear and non-linear data structures
* Searching and sorting algorithms
* Stack and Queue implementations using arrays and linked lists
* Multiple Binary Search Tree traversals
* Reusable library architecture
* Designed for integration with client applications

---

# 👨‍💻 Author

**Sakshi Pankaj Borhade**

**Technology:** C++ Programming

---

## 📌 Summary

The **Generalised Data Structures Library** demonstrates the implementation of fundamental data structures and algorithms from scratch using **C++ OOP and Templates**.

The project combines **educational understanding with practical reusable software design**, providing a foundation for learning data structures, algorithms, generic programming, and object-oriented development.
