# Generalised Data Structures Library

## ProjectName : Created self data structures.
## Technology: C++ Programming
## Author: Vaishnavi D Shingare

A reusable and generic **C++ Data Structures Library** that provides object-oriented implementations of linear and non-linear data structures, along with searching and sorting algorithms.

The library is designed using **C++ Templates**, allowing the same data structure implementation to work with different data types such as `int`, `float`, `double`, `char`, `string`, and custom objects.

---

## 📌 Project Overview

The **Generalised Data Structures Library** is developed using **C++ and Object-Oriented Programming (OOP)** principles.

It provides ready-to-use implementations of:

* Linear Data Structures
* Non-Linear Data Structures
* Searching Algorithms
* Sorting Algorithms
* Generic Programming using Templates

The main goal of this project is to create a **modular, reusable, and extensible library** that can be integrated with different C++ client applications.

---

## 🚀 Key Features

### 1. Linear Data Structures

The library provides implementations of:

* Singly Linear Linked List
* Singly Circular Linked List
* Doubly Linear Linked List
* Doubly Circular Linked List
* Stack
* Queue

### 2. Non-Linear Data Structures

#### Binary Search Tree (BST)

Supports operations such as:

* Insert
* Delete
* Search
* Inorder Traversal
* Preorder Traversal
* Postorder Traversal

### 3. Searching Algorithms

The library supports searching techniques such as:

* Linear Search
* Binary Search

### 4. Sorting Algorithms

The library provides sorting techniques such as:

* Bubble Sort
* Selection Sort
* Insertion Sort

### 5. Generic Programming

The library uses **C++ Templates** so that the same implementation can work with different data types.

For example:

```cpp
LinkedList<int> obj1;
LinkedList<float> obj2;
LinkedList<string> obj3;
```

This avoids writing separate implementations for every data type.

---

# 🛠️ Technologies Used

| Technology      | Purpose                             |
| --------------- | ----------------------------------- |
| C++             | Core programming language           |
| OOP             | Object-oriented design              |
| Templates       | Generic programming                 |
| Data Structures | Data organization                   |
| Algorithms      | Searching and sorting               |
| Git & GitHub    | Version control and project hosting |

---

# 📂 Project Structure

A recommended project structure is:

```text
Generalised-Data-Structures-Library/
│
├── README.md
│
├── Header/
│   ├── SinglyLL.h
│   ├── SinglyCLL.h
│   ├── DoublyLL.h
│   ├── DoublyCLL.h
│   ├── Stack.h
│   ├── Queue.h
│   └── BST.h
│
├── Source/
│   ├── SinglyLL.cpp
│   ├── SinglyCLL.cpp
│   ├── DoublyLL.cpp
│   ├── DoublyCLL.cpp
│   ├── Stack.cpp
│   ├── Queue.cpp
│   └── BST.cpp
│
├── Algorithms/
│   ├── Searching.h
│   └── Sorting.h
│
└── Client/
    └── main.cpp
```

> If your actual project has a different folder structure, replace the above structure with your actual files.

---

# 💻 Generic Syntax

The basic syntax used in the library is:

```cpp
template <class T>
class ClassName
{
    // Data members
    // Member functions
};
```

Here, `T` represents a generic data type.

---

# 🔗 Linked List Syntax

Example:

```cpp
template <class T>
class SinglyLL
{
public:
    void InsertFirst(T No);
    void InsertLast(T No);
    void DeleteFirst();
    void DeleteLast();
    void Display();
};
```

### Creating an Object

For integers:

```cpp
SinglyLL<int> obj;
```

For floating-point values:

```cpp
SinglyLL<float> obj;
```

For strings:

```cpp
SinglyLL<string> obj;
```

### Using Operations

```cpp
SinglyLL<int> obj;

obj.InsertFirst(10);
obj.InsertLast(20);
obj.InsertLast(30);

obj.Display();

obj.DeleteFirst();
obj.DeleteLast();
```

---

# 🔄 Circular Linked List Syntax

Example:

```cpp
SinglyCLL<int> obj;

obj.InsertFirst(10);
obj.InsertLast(20);
obj.InsertLast(30);

obj.Display();

obj.DeleteFirst();
obj.DeleteLast();
```

---

# ↔️ Doubly Linked List Syntax

Example:

```cpp
DoublyLL<int> obj;

obj.InsertFirst(10);
obj.InsertLast(20);

obj.Display();

obj.DeleteFirst();
obj.DeleteLast();
```

---

# 📚 Stack Syntax

Stack follows the **LIFO (Last In, First Out)** principle.

Example:

```cpp
Stack<int> obj;

obj.Push(10);
obj.Push(20);
obj.Push(30);

obj.Display();

obj.Pop();
```

Concept:

```text
Push → Add element
Pop  → Remove top element
```

---

# 🚶 Queue Syntax

Queue follows the **FIFO (First In, First Out)** principle.

Example:

```cpp
Queue<int> obj;

obj.Enqueue(10);
obj.Enqueue(20);
obj.Enqueue(30);

obj.Display();

obj.Dequeue();
```

Concept:

```text
Enqueue → Add element
Dequeue → Remove element
```

---

# 🌳 Binary Search Tree Syntax

Example:

```cpp
BST<int> obj;

obj.Insert(50);
obj.Insert(30);
obj.Insert(70);
obj.Insert(20);
obj.Insert(40);

obj.Inorder();
```

Possible tree:

```text
        50
       /  \
     30    70
    /  \
   20   40
```

---

# 🔍 Searching Syntax

### Linear Search

Example:

```cpp
int Arr[] = {10, 20, 30, 40, 50};

int Result = LinearSearch(Arr, 5, 30);
```

### Binary Search

```cpp
int Arr[] = {10, 20, 30, 40, 50};

int Result = BinarySearch(Arr, 5, 40);
```

> Binary Search generally requires the data to be sorted.

---

# 🔃 Sorting Syntax

### Bubble Sort

```cpp
int Arr[] = {50, 20, 40, 10, 30};

BubbleSort(Arr, 5);
```

### Selection Sort

```cpp
SelectionSort(Arr, 5);
```

### Insertion Sort

```cpp
InsertionSort(Arr, 5);
```

---

# 🧩 Example Client Program

A client application can use the library like this:

```cpp
#include <iostream>
#include "SinglyLL.h"

using namespace std;

int main()
{
    SinglyLL<int> obj;

    obj.InsertFirst(10);
    obj.InsertLast(20);
    obj.InsertLast(30);

    cout << "Linked List: ";
    obj.Display();

    return 0;
}
```

Output:

```text
Linked List: 10 20 30
```

---

# ⚙️ How to Compile

If your library is implemented using header files, compile the client program using:

```bash
g++ main.cpp -o main
```

Run:

```bash
./main
```

### Windows

```bash
g++ main.cpp -o main.exe
```

Run:

```bash
main.exe
```

---

# 📦 Library Usage

The library follows a reusable design:

```text
             Generalised Data Structures Library
                         │
        ┌────────────────┼────────────────┐
        │                │                │
     Linear           Non-Linear       Algorithms
        │                │                │
   ┌────┴────┐          BST        ┌─────┴─────┐
   │         │                     │           │
Linked    Stack/Queue          Searching    Sorting
 Lists
```

A client application can include the required header and create objects using templates.

---

# 🎯 Learning Outcomes

This project helped develop knowledge of:

* C++ Programming
* Object-Oriented Programming
* Classes and Objects
* Constructors and Destructors
* Templates
* Generic Programming
* Linked Lists
* Stack
* Queue
* Binary Search Tree
* Searching Algorithms
* Sorting Algorithms
* Memory Management
* Reusable Software Design
* Modular Programming

---

# 💡 Why Templates?

Without templates, separate implementations would be required for different data types.

For example:

```cpp
SinglyLLInt
SinglyLLFloat
SinglyLLString
```

Using templates:

```cpp
SinglyLL<int>
SinglyLL<float>
SinglyLL<string>
```

The same class can therefore be reused with different data types.

---

# 🏗️ OOP Concepts Used

The project applies important OOP concepts such as:

### Encapsulation

Data and related operations are grouped inside classes.

### Abstraction

Users can perform operations such as:

```cpp
obj.InsertFirst(10);
obj.DeleteLast();
```

without needing to know the internal implementation.

### Generic Programming

Templates allow the data structures to work with multiple data types.

---

# 📊 Data Structures Covered

| Data Structure              | Type       | Main Operations                   |
| --------------------------- | ---------- | --------------------------------- |
| Singly Linked List          | Linear     | Insert, Delete, Display           |
| Singly Circular Linked List | Linear     | Insert, Delete, Display           |
| Doubly Linked List          | Linear     | Insert, Delete, Display           |
| Doubly Circular Linked List | Linear     | Insert, Delete, Display           |
| Stack                       | Linear     | Push, Pop, Display                |
| Queue                       | Linear     | Enqueue, Dequeue, Display         |
| Binary Search Tree          | Non-Linear | Insert, Delete, Search, Traversal |

---

# 🔎 Algorithms Covered

| Category  | Algorithms     |
| --------- | -------------- |
| Searching | Linear Search  |
| Searching | Binary Search  |
| Sorting   | Bubble Sort    |
| Sorting   | Selection Sort |
| Sorting   | Insertion Sort |

---

# 🌟 Advantages

* Generic and reusable
* Easy to integrate into client applications
* Object-oriented design
* Supports multiple data types
* Modular structure
* Easy to extend
* Useful for learning and interview preparation
* Demonstrates practical knowledge of data structures and algorithms

---

# 🔮 Future Enhancements

Possible future improvements include:

* Merge Sort
* Quick Sort
* Hash Table
* Heap
* AVL Tree
* Graph Data Structure
* Graph Traversal
* Priority Queue
* Exception Handling
* Unit Testing
* Documentation for every API
* CMake build support

---

# 🎤 Interview Explanation

> **"I developed a Generalised Data Structures Library in C++ that provides reusable implementations of linear and non-linear data structures such as linked lists, stacks, queues, and binary search trees, along with searching and sorting algorithms. I used C++ templates to make the implementations generic so they can work with different data types. The project follows object-oriented and modular design principles and can be integrated into client applications as a reusable library. This project strengthened my understanding of C++, OOP, templates, data structures, algorithms, and reusable software design."**

---

# 📌 Project Highlights

**Project:** Generalised Data Structures Library
**Technology:** C++
**Domain:** Data Structures & Algorithms
**Type:** Reusable Library
**Programming Concepts:** OOP, Templates, Generic Programming

---

# 👩‍💻 Author

**Vaishnavi Shingare**

C++ | Java | Data Structures & Algorithms | Web Development

---

# ⭐ If you find this project useful

Give the repository a ⭐ on GitHub.
