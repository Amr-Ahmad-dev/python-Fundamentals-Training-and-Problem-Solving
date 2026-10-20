# 🏛️ Object-Oriented Programming (OOP) in Python

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Paradigm](https://img.shields.io/badge/Paradigm-Object--Oriented-darkgreen.svg)](#)
[![Complexity](https://img.shields.io/badge/Complexity-Intermediate--Advanced-brightgreen.svg)](#)

## 📌 Project Overview
A complete hands-on guide to mastering Object-Oriented Programming (OOP) design patterns in Python. With 28 cells and over 250 lines of robust code, this notebook demonstrates how to design maintainable, modular, and extensible object architectures.

---

## 🧱 Architectural Components
```
                    +--------------------+
                    |    Base Class      |
                    | (e.g., BankAccount)|
                    +---------+----------+
                              |
                     Inheritance / super()
                              |
                    +---------v----------+
                    |   Derived Class    |
                    |  (SavingsAccount)  |
                    +--------------------+
                              |
                    +---------v----------+
                    | Polymorphic Output |
                    +--------------------+
```

### 1. Class Construction & Initialization
- Constructor semantics with `__init__`.
- Binding instance variables to the self reference.
- Distinguishing between class-level constants and instance-level state.

### 2. Method Implementation & Data Encapsulation
- Defining instance methods that mutate state safely.
- Input validation patterns inside setter routines.
- Formatting string representations of complex objects.

### 3. Inheritance & Method Overriding
- Subclassing base classes to extend domain behavior.
- Utilizing `super()` to chain initialization and parent methods.
- Dynamic dispatch and polymorphic behavior.

### 4. Real-World Case Studies
- **Banking Ledger**: Validated deposit, withdrawal, balance integrity checking.
- **Library Catalog**: Entity status tracking (checked in vs checked out).
- **Student Information System**: GPA calculation, course enrollments, and academic reports.

---

## 💻 Code Structure
- **Notebook**: [`object_oriented_programming.ipynb`](./object_oriented_programming.ipynb)
- **Cell Count**: 28 cells (13 code cells, 15 markdown cells)
- **Total Code Lines**: 258 lines of cleanly commented OOP Python.

---

## 🚀 How to Run
```bash
jupyter notebook object_oriented_programming.ipynb
```
