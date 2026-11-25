# Data Structures & Algorithms – Checkpoint

## 1. Introduction

This checkpoint focuses on understanding fundamental data structures and sorting algorithms used in computer science and software development.

To complete this activity, I used [**VisuAlgo**](https://visualgo.net/en), an interactive platform that provides visual representations of data structures and algorithms.

I explored eight data structures and six sorting algorithms, observing how they work, how data is organized, and how different operations are performed.

The main objective was to develop a better understanding of data organization, algorithm execution, and problem-solving techniques.

---

## 2. Data Structures

Data structures are methods of organizing and storing data to make it easier to access, manage, and modify.

During this checkpoint, I explored the following eight data structures.

### 2.1 Array

An Array is a collection of elements stored in an ordered structure.

**Key concepts:**

- Elements are accessed using indexes.
- Indexing generally starts at 0.
- Elements can be accessed directly using their positions.

**What I learned:** How to access elements, understand indexes, and navigate an array.

### 2.2 Linked List

A Linked List is a collection of nodes connected through references or pointers.

**Key concepts:**

- Each node contains data and a reference to the next node.
- Nodes are connected sequentially.
- Traversal starts from the head of the list.

**What I learned:** How nodes are connected and how to navigate a linked list.

### 2.3 Stack

A Stack follows the LIFO principle (Last In, First Out).

**Key concepts:**

- Push: adds an element.
- Pop: removes the top element.
- The last element added is the first one removed.

**What I learned:** How stack operations work and how elements are managed using LIFO.

### 2.4 Queue

A Queue follows the FIFO principle (First In, First Out).

**Key concepts:**

- Enqueue: adds an element.
- Dequeue: removes the first element.
- The first element added is the first one removed.

**What I learned:** How queues manage elements in their order of arrival.

### 2.5 Hash Table

A Hash Table stores data using key-value pairs.

**Key concepts:**

- Uses a hash function to calculate storage positions.
- Allows efficient data retrieval in typical situations.
- Collisions occur when different keys map to the same position.

**What I learned:** How keys and values are organized and how hashing supports data retrieval.

### 2.6 Binary Search Tree (BST)

A Binary Search Tree is a hierarchical data structure.

**Key concepts:**

- Smaller values are placed on the left.
- Larger values are placed on the right.
- Each node can have up to two children.

**What I learned:** How data is organized in a tree and how searching can be performed.

### 2.7 Heap

A Heap is a tree-based data structure used to manage priorities.

**Key concepts:**

- Max Heap: the largest value is at the root.
- Min Heap: the smallest value is at the root.
- Elements follow specific heap-ordering rules.

**What I learned:** How heaps organize elements according to their priorities.

### 2.8 Graph

A Graph represents relationships and connections between different elements.

**Key concepts:**

- Vertices represent elements.
- Edges represent connections.
- Graphs can be directed or undirected.

**What I learned:** How graphs represent relationships between connected elements.

---

## 3. Sorting Algorithms

Sorting algorithms are techniques used to arrange data in a particular order, such as ascending or descending order.

I explored six sorting algorithms using VisuAlgo.

### 3.1 Bubble Sort

Bubble Sort compares adjacent elements and swaps them when they are in the wrong order.

**Main principle:** Repeated comparison and swapping of neighboring elements.

### 3.2 Selection Sort

Selection Sort repeatedly identifies the smallest element and places it in its correct position.

**Main principle:** Selecting the minimum value during each iteration.

### 3.3 Insertion Sort

Insertion Sort builds a sorted section by inserting each new element into its appropriate position.

**Main principle:** Inserting elements into their correct positions.

### 3.4 Merge Sort

Merge Sort uses the divide-and-conquer technique.

**Main principle:**

1. Divide the array into smaller parts.
2. Sort each part.
3. Merge the sorted parts.

### 3.5 Quick Sort

Quick Sort also uses the divide-and-conquer technique.

**Main principle:**

1. Select a pivot.
2. Partition elements around the pivot.
3. Sort the resulting partitions.

### 3.6 Counting Sort

Counting Sort organizes elements by counting the frequency of each value.

**Main principle:** Using frequency counts to sort data instead of comparing elements directly.

---

## 4. Algorithm Complexity

Understanding algorithm complexity helps evaluate the efficiency of different sorting techniques.

| Sorting Algorithm | Average Time Complexity |
| ----------------- | ----------------------- |
| Bubble Sort       | O(n²)                   |
| Selection Sort    | O(n²)                   |
| Insertion Sort    | O(n²)                   |
| Merge Sort        | O(n log n)              |
| Quick Sort        | O(n log n)              |
| Counting Sort     | O(n + k)                |

Note: Quick Sort has a worst-case time complexity of O(n²). Counting Sort depends on the number of elements (n) and the value range (k).

---

## 5. Practical Exploration with VisuAlgo

I used VisuAlgo to explore and visualize the different data structures and sorting algorithms.

During this exploration, I focused on:

- Observing how elements are inserted, accessed, removed, and organized.
- Understanding how nodes connect in linked lists, trees, and graphs.
- Following the execution of stack and queue operations.
- Observing how sorting algorithms compare, move, and rearrange elements.
- Understanding the differences between sorting techniques.

The visual demonstrations helped me understand the execution process of each concept and connect theoretical explanations with practical representations.

---

## 6. Concepts to Improve Further

Although I understand the fundamental principles of the concepts explored, I recognize that understanding their theory is different from implementing them independently.

The following areas require additional practice:

 Concept             Area for Improvement                          

 Linked List         Insertion, deletion, and traversal operations 
 Hash Table          Hash functions and collision handling         
 Binary Search Tree  Insertion, deletion, and traversal            
 Heap                Heap insertion, deletion, and reorganization  
 Merge Sort          Understanding the complete merging process    
 Quick Sort          Pivot selection and partitioning              

I need more programming exercises to strengthen my implementation skills and become more confident in applying these concepts to real-world problems.

---

## 7. Learning Outcomes

This checkpoint helped me develop a better understanding of:

- Different methods of organizing and storing data.
- The differences between linear and non-linear data structures.
- The LIFO and FIFO principles.
- How trees and graphs represent hierarchical and connected data.
- How different sorting algorithms operate.
- The importance of time complexity when choosing an algorithm.
- The relationship between theoretical concepts and practical implementation.

It also helped improve my analytical thinking and my ability to follow algorithmic processes step by step.

---

## 8. Resources

The following resource was used during this checkpoint:

- **VisuAlgo:** www.visualgo.net

VisuAlgo provided interactive visualizations that helped me explore and understand the behavior of data structures and algorithms.

---

## 9. Conclusion

This checkpoint provided an opportunity to explore fundamental concepts in Data Structures and Algorithms through interactive visualization.

By studying eight data structures and six sorting algorithms, I developed a better understanding of how data is organized, accessed, manipulated, and sorted.

The use of VisuAlgo made it easier to visualize algorithm execution and understand the differences between various techniques.

However, I recognize that continuous practice is necessary to improve my programming skills, algorithm implementation, and problem-solving abilities.

I intend to continue practicing these concepts through coding exercises and practical projects to strengthen my technical foundations as a software developer.
