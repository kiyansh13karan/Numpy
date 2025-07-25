# 🚀 NumPy: A Beginner-to-Advanced Journey

<div align="center">

![NumPy Logo](https://numpy.org/images/logo.svg)

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-1.21+-orange.svg)](https://numpy.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/kiyansh13karan/Numpy?style=social)](https://github.com/kiyansh13karan/Numpy)

*Master NumPy from basics to advanced concepts with hands-on examples and real-world applications*

</div>

## 📖 About This Repository

Welcome to my comprehensive NumPy learning journey! This repository contains all the code, examples, and projects I've worked on while mastering NumPy - from basic array operations to advanced mathematical computations and data manipulation techniques.

## 📊 Jupyter Notebook Journey

### 📋 **Phase-wise Learning Structure**

| Phase | Notebook | Topics Covered | Key Concepts |
|-------|----------|----------------|--------------|
| **Phase 1** | `phase-1.ipynb` | NumPy Foundation, Array creation & methods | `np.array()`, `shape`, `dtype`, basic operations |
| **Phase 2** | `phase-2.ipynb` | Intermediate concepts, advanced operations | Indexing, slicing, broadcasting, ufuncs |
| **Phase 3** | `phase-3.ipynb` | Advanced topics, complex manipulations | Linear algebra, advanced indexing, optimization |
| **Phase 4** | `phase-4.ipynb` | Real-world applications, practical implementations | Data analysis, file I/O, performance tuning |

### 💾 **Array Data Files**
- **`arr1.npy`**: Basic array examples and demonstrations
- **`arr2.npy`**: Intermediate array structures and operations
- **`arr3.npy`**: Advanced array configurations and use cases

### 📚 Course Structure

```
📦 NumPy Journey - Phase by Phase Learning
├── 📚 Phase 1 (phase-1.ipynb)
│   ├── NumPy Foundation
│   ├── Array Creation & Methods
│   └── Basic Data Types
├── 🔥 Phase 2 (phase-2.ipynb)
│   ├── Array Indexing & Slicing
│   ├── Broadcasting & Vectorization
│   └── Mathematical Operations
├── 🚀 Phase 3 (phase-3.ipynb)
│   ├── Advanced Array Manipulations
│   ├── Linear Algebra Operations
│   └── Performance Optimization
└── 💼 Phase 4 (phase-4.ipynb)
    ├── Real-world Applications
    ├── Data Analysis Examples
    └── Advanced Use Cases
```

## 🏆 Topics Covered

### 🔰 **Beginner Level**
- ✅ **Array Fundamentals**: Understanding N-dimensional arrays
- ✅ **Array Creation**: zeros(), ones(), arange(), linspace()
- ✅ **Data Types**: int, float, complex, boolean arrays
- ✅ **Basic Operations**: Addition, subtraction, multiplication, division
- ✅ **Array Properties**: Shape, size, ndim, dtype

### 🔥 **Intermediate Level**
- ✅ **Indexing & Slicing**: Accessing and modifying array elements
- ✅ **Boolean Indexing**: Conditional data selection
- ✅ **Array Reshaping**: reshape(), flatten(), transpose()
- ✅ **Broadcasting**: Operating on arrays with different shapes
- ✅ **Universal Functions (ufuncs)**: Element-wise operations
- ✅ **Array Concatenation**: hstack(), vstack(), concatenate()

### 🚀 **Advanced Level**
- ✅ **Linear Algebra**: Matrix multiplication, eigenvalues, SVD
- ✅ **Statistical Operations**: Mean, median, std, correlation
- ✅ **Advanced Indexing**: Fancy indexing, multi-dimensional indexing
- ✅ **Performance Optimization**: Vectorization techniques
- ✅ **Memory Management**: Views vs copies, memory layout
- ✅ **File I/O**: Loading/saving arrays with different formats

## 🛠️ Key Features Explored

| Feature | Description | Code Examples |
|---------|-------------|---------------|
| **Array Broadcasting** | Performing operations on arrays with different shapes | `array_2d + array_1d` |
| **Vectorization** | Replacing loops with array operations for better performance | `np.sum(array, axis=0)` |
| **Boolean Masking** | Filtering data based on conditions | `array[array > threshold]` |
| **Linear Algebra** | Matrix operations and decompositions | `np.linalg.inv(matrix)` |
| **Statistical Analysis** | Descriptive statistics and data analysis | `np.corrcoef(data)` |

## 📊 Practical Applications

### 🎯 **Real-World Projects**
1. **📈 Data Analysis Pipeline**: Complete workflow for analyzing datasets
2. **🖼️ Image Processing**: Basic image manipulation using NumPy arrays
3. **📊 Statistical Modeling**: Implementing statistical functions from scratch
4. **🧮 Mathematical Simulations**: Monte Carlo simulations and numerical methods
5. **⚡ Performance Benchmarking**: Comparing NumPy vs pure Python performance

## 🚀 Getting Started

### Prerequisites
```bash
# Ensure you have Python 3.7+ installed
python --version

# Install required packages
pip install numpy matplotlib jupyter
```

### Quick Start
```python
import numpy as np

# Create your first NumPy array
arr = np.array([1, 2, 3, 4, 5])
print(f"Array: {arr}")
print(f"Shape: {arr.shape}")
print(f"Data type: {arr.dtype}")

# Basic operations
result = arr * 2
print(f"Array doubled: {result}")
```

## 📁 Repository Structure

```
NumPy/
├── .venv/                          # Virtual environment for project dependencies
├── .gitignore                      # Git ignore file for Python projects
├── README.md                       # This comprehensive guide
├── arr1.npy                       # NumPy array data file - saved array examples
├── arr2.npy                       # NumPy array data file - more array examples  
├── arr3.npy                       # NumPy array data file - advanced array structures
├── phase-1.ipynb                  # 📚 NumPy Foundation - Array creation & basic methods
├── phase-2.ipynb                  # 🔥 Intermediate Concepts - Advanced operations
├── phase-3.ipynb                  # 🚀 Advanced Topics - Complex array manipulations
└── phase-4.ipynb                  # 💼 Real-world Applications - Practical implementations
```

## 🎓 Learning Path

```mermaid
graph TD
    A[NumPy Basics] --> B[Array Operations]
    B --> C[Indexing & Slicing]
    C --> D[Broadcasting]
    D --> E[Mathematical Functions]
    E --> F[Linear Algebra]
    F --> G[Advanced Topics]
    G --> H[Real Projects]
    H --> I[NumPy Expert! 🎉]
```

## 💡 Key Takeaways

- **🚀 Performance**: NumPy operations are 10-100x faster than pure Python
- **🎯 Vectorization**: Think in arrays, not loops
- **🧠 Broadcasting**: Powerful feature for working with different shaped arrays
- **📊 Data Science Ready**: Foundation for pandas, scikit-learn, and more
- **🔧 Versatile**: From simple calculations to complex scientific computing

## 🔧 Technologies Used

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

## 📈 Progress Tracker

- [x] **Week 1**: Array Fundamentals & Basic Operations
- [x] **Week 2**: Indexing, Slicing & Array Manipulation
- [x] **Week 3**: Broadcasting & Vectorization
- [x] **Week 4**: Mathematical & Statistical Operations
- [x] **Week 5**: Linear Algebra & Advanced Topics
- [x] **Week 6**: Real-world Projects & Applications

## 🤝 Contributing

Feel free to:
- ⭐ Star this repository if you found it helpful
- 🍴 Fork it for your own learning journey
- 🐛 Report any issues or bugs
- 💡 Suggest improvements or additional examples

## 📚 Additional Resources

- 📖 [Official NumPy Documentation](https://numpy.org/doc/stable/)
- 🎥 [NumPy Tutorials on YouTube](https://www.youtube.com/results?search_query=numpy+tutorial)
- 📝 [NumPy Cheat Sheet](https://numpy.org/devdocs/user/quickstart.html)
- 🏆 [NumPy Exercises for Practice](https://github.com/rougier/numpy-100)

## 📞 Connect With Me

- 🐙 GitHub: [@kiyansh13karan](https://github.com/kiyansh13karan)
- 💼 LinkedIn: [Karan Nayal](https://www.linkedin.com/in/karan-nayal-054981286/)
- 📧 Email: [karannayalkannu1982@gmail.com]

---

<div align="center">

**⭐ If this repository helped you learn NumPy, please give it a star! ⭐**

*Happy Coding! 🚀*

</div>

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

> **Note**: This repository represents my personal learning journey with NumPy. The code examples are based on various tutorials, documentation, and hands-on practice. Feel free to use this as a reference for your own NumPy learning adventure!