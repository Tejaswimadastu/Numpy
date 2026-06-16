# NumPy Fundamentals for Data Science

## Overview

This repository contains practical examples, exercises, and demonstrations of NumPy, one of the most essential Python libraries for scientific computing and data analysis.

The notebook covers fundamental NumPy concepts including array creation, indexing, slicing, mathematical operations, statistical functions, reshaping, and performance optimization. It serves as a beginner-friendly resource for students and aspiring data scientists to build a strong foundation in numerical computing with Python.

---

## Objectives

- Learn the fundamentals of NumPy
- Understand multidimensional arrays
- Perform mathematical and statistical operations
- Explore array indexing and slicing
- Practice reshaping and manipulating data
- Build a foundation for Data Science and Machine Learning

---

## Repository Structure

```text
NumPy/
│
├── Numpy.ipynb
├── README.md
```

---

## What is NumPy?

NumPy (Numerical Python) is an open-source Python library used for:

- Numerical Computation
- Array Processing
- Mathematical Operations
- Linear Algebra
- Scientific Computing
- Data Analysis

NumPy provides powerful N-dimensional array objects and tools for working efficiently with large datasets.

---

## Topics Covered

### 1. Creating Arrays

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])
print(arr)
```

### 2. Array Dimensions

```python
arr.ndim
arr.shape
arr.size
```

### 3. Indexing and Slicing

```python
arr[0]
arr[1:4]
```

### 4. Mathematical Operations

```python
arr + 10
arr * 2
arr / 5
```

### 5. Statistical Functions

```python
np.mean(arr)
np.median(arr)
np.std(arr)
np.max(arr)
np.min(arr)
```

### 6. Reshaping Arrays

```python
arr.reshape(2, 3)
```

### 7. Random Number Generation

```python
np.random.rand(5)
np.random.randint(1, 100, 10)
```

### 8. Linear Algebra Operations

```python
np.dot(a, b)
np.transpose(a)
```

---

## Key Concepts Demonstrated

- NumPy Arrays
- Array Attributes
- Array Indexing
- Array Slicing
- Broadcasting
- Universal Functions (ufuncs)
- Aggregation Functions
- Random Module
- Matrix Operations
- Array Reshaping

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Tejaswimadastu/Numpy.git
cd Numpy
```

### Install NumPy

```bash
pip install numpy
```

---

## Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Numpy.ipynb
```

and execute the cells to explore NumPy concepts interactively.

---

## Learning Outcomes

By completing this notebook, you will learn:

- Efficient numerical computation in Python
- Array manipulation techniques
- Data preprocessing fundamentals
- Statistical analysis using NumPy
- Mathematical operations for Machine Learning
- Performance benefits of vectorized computations

---

## Applications of NumPy

- Data Science
- Machine Learning
- Artificial Intelligence
- Scientific Computing
- Data Analysis
- Computer Vision
- Deep Learning
- Financial Analytics

---

## Why NumPy?

### Traditional Python List

```python
numbers = [1, 2, 3, 4, 5]
```

### NumPy Array

```python
numbers = np.array([1, 2, 3, 4, 5])
```

NumPy arrays are:
- Faster
- Memory Efficient
- Easier to Process
- Optimized for Numerical Operations

---

## Future Enhancements

- Advanced NumPy Operations
- Matrix Decomposition
- Linear Algebra Applications
- Performance Benchmarking
- Integration with Pandas and Matplotlib
- Machine Learning Examples

---

## Author

**Tejaswi Madastu**

GitHub: https://github.com/Tejaswimadastu

---

## License

This repository is created for educational and learning purposes.
