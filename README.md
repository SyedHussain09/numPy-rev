# NumPy Revision Notebook

This repository contains a comprehensive NumPy revision notebook covering essential concepts with practical examples.

## 📒 Contents

### 🔢 **Basics of NumPy**
- What is NumPy and why use it?
- Creating arrays with `np.array()`
- Key properties: `ndim`, `shape`, `size`, `dtype`
- Special arrays: `zeros()`, `ones()`, `full()`, `arange()`, `linspace()`

### 📊 **Array Operations**
- Mathematical operations (addition, subtraction, multiplication, division)
- Broadcasting concept
- Vectorized operations (faster than loops)
- Practice: Adding 10% tax to prices

### 📈 **Statistics & Aggregation**
- Sum, mean, min, max, standard deviation
- 2D aggregation with axis parameter
- Boolean indexing for filtering data

### 🔄 **Shape Manipulation**
- Reshaping arrays
- Flattening vs Ravel
- Stacking (`vstack`, `hstack`) and splitting arrays

### 🎲 **Random Numbers**
- Generating random integers and normal distributions
- Setting seeds for reproducibility

### ➗ **Linear Algebra**
- Matrix multiplication
- Matrix inverse and determinant
- Using `np.linalg` module

### 💾 **File Operations**
- Saving arrays to `.npy` files
- Loading saved arrays

### ⚡ **Performance Tips**
- Views vs Copies (memory efficiency)
- Why NumPy is faster than Python lists

## 🚀 Quick Start

1. **Install NumPy:**
```bash
pip install numpy
```

2. **Import in Python:**
```python
import numpy as np
```

3. **Basic usage:**
```python
# Create an array
arr = np.array([1, 2, 3, 4, 5])

# Vectorized operation (fast!)
result = arr * 2
```

## 📁 Files

- `numPy.ipynb` - Main Jupyter notebook with all examples
- `data.npy` - Sample saved NumPy array

## 💡 Key Takeaways

- **NumPy arrays are fixed-size and homogeneous** - makes them faster than Python lists
- **Vectorization** - operations applied to entire arrays without loops
- **Broadcasting** - operations on different-shaped arrays
- **Memory efficient** - views instead of copies when possible

## 👨‍💻 Author

**Syed Sajjad Hussain** - Complete NumPy revision with practical examples.

## 📚 Use Cases

- Data Science & Machine Learning
- Scientific Computing
- Financial Analysis
- Image Processing
- Any numerical computation in Python

---

*Perfect for beginners learning NumPy or experienced developers needing a quick refresher!*
