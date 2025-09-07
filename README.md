# Algorithm Efficiency Mini Project

## 📌 Overview
This repository contains my **Lab Assignment 1** for *Design & Analysis of Algorithms*.  
The project implements multiple algorithms, measures their performance (time & memory), and compares them with theoretical complexities.  

All experiments are implemented and executed using **Google Colab (Python)**.

---

## 🛠️ Implemented Algorithms
### Fibonacci Numbers
- **Naive Recursive Fibonacci**
- **Dynamic Programming Fibonacci (Iterative)**

### Sorting Algorithms
- **Merge Sort**
- **Quick Sort** (random pivot)
- **Insertion Sort**
- **Bubble Sort**
- **Selection Sort**

### Searching Algorithm
- **Binary Search**

---

## 📊 Profiling & Experiments
For each algorithm:
- **Execution Time** measured using `time.perf_counter`
- **Memory Usage** measured using `tracemalloc`
- **Recursion Depth** tracked for recursive algorithms
- **Input Variations** tested with:
  - Random arrays
  - Sorted arrays
  - Reversed arrays
- **Plots** generated using `matplotlib` (Time vs Input Size)
