# 🐍 Python Fundamentals & Scientific Computing Track (6-Part Series)
[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/Library-NumPy-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Library-Seaborn-blueviolet.svg)](https://seaborn.pydata.org/)
[![Status](https://img.shields.io/badge/Curriculum-Complete-brightgreen.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)
A hands-on, 6-part foundational curriculum mastering **Python Programming** and the **Core Scientific Computing Stack**. 
This track establishes the programming architecture, algorithmic thinking, data wrangling, and statistical visualization skills required for production data science, machine learning, and software engineering.
---
## 🗺️ Curriculum Learning Roadmap
```text
                     [ THE 6 FOUNDATIONAL PILLARS ]
      ┌────────────────────────────────────────────────────────┐
      │             PHASE 1: CORE PYTHON MASTERY               │
      └────────────────────────────────────────────────────────┘
                                 │
     ┌───────────────────────────┼───────────────────────────┐
     ▼                           ▼                           ▼
[01. Control Flow & Loops]  [02. Functions & Scope]  [03. Object-Oriented Prog.]
 • for / while loops        • def, *args, **kwargs   • Classes & Instances
 • break, continue, pass    • Scopes (LEGB rule)     • Encapsulation & State
 • Algorithmic iteration    • Lambdas & Decorators   • Inheritance & Polymorphism
                                 │
                                 ▼
      ┌────────────────────────────────────────────────────────┐
      │         PHASE 2: THE SCIENTIFIC COMPUTING STACK        │
      └────────────────────────────────────────────────────────┘
                                 │
     ┌───────────────────────────┼───────────────────────────┐
     ▼                           ▼                           ▼
[04. NumPy Computing]       [05. Pandas Wrangling]   [06. Statistical Visuals]
 • N-D Tensor Arrays        • Series & DataFrames    • Matplotlib Core Figures
 • Vectorization & Strides  • Indexing (.loc, .iloc) • Seaborn Categoricals
 • Linear Algebra & Math    • GroupBy & Aggregations • Heatmaps & Distributions

  

  
📚 Deep Dive: The 6 Core Projects

  
1️⃣ Project 1: Control Flow, Loops & Algorithmic Iteration

  

  
Focus: Procedural flow control, iterative algorithms, and boundary conditions.

  
Key Topics:
  
  

  
for loops across sequence types (list, str, tuple, dict).

  
while loops with sentinel termination and safety invariants.

  
Dynamic execution control with break, continue, and loop else blocks.

  
Practical algorithms: Prime number generation, Fibonacci sequences, and 2D matrix coordinate traversal.

  

  

  

  
2️⃣ Project 2: Functions, Scope & Modular Code

  

  
Focus: Writing reusable, testable, and maintainable functional software.

  
Key Topics:
  
  

  
Formal parameters, positional-only, keyword-only, and default arguments.

  
Variable-length arguments (*args for tuples, **kwargs for dictionaries).

  
Scope resolution mechanics under Python's LEGB rule (Local, Enclosing, Global, Built-in).

  
Functional paradigms: Anonymous lambda expressions, map(), filter(), closures, and custom decorators.

  

  

  

  
3️⃣ Project 3: Object-Oriented Programming (OOP) & Domain Modeling

  

  
Focus: Large-scale software design, state encapsulation, and polymorphic architectures.

  
Key Topics:
  
  

  
Class definitions, constructor mechanics with __init__, and instance attribute binding.

  
Distinguishing class-level constants/counters from instance-specific states.

  
Single and multi-level inheritance hierarchies using super().

  
Polymorphism and method overriding.

  
Real-World Case Studies: Banking transaction ledger (with overdraft validation), library checkout catalog, and student record GPA management system.

  

  

  

  
4️⃣ Project 4: Numerical Computing & Vectorization with NumPy

  

  
Focus: High-performance multi-dimensional array processing and linear algebra.

  
Key Topics:
  
  

  
ndarray memory allocation, shape manipulation, transpositions, and stride slicing.

  
Eliminating computationally expensive Python loops via vectorized operations.

  
Dimension alignment using NumPy's broadcasting rules.

  
Boolean mask indexing (arr[arr > threshold]).

  
Matrix dot products (@ / np.dot), matrix inversions, and multi-axis statistical reductions (sum, mean, std).

  

  

  

  
5️⃣ Project 5: Tabular Data Wrangling & Manipulation with Pandas

  

  
Focus: Production data extraction, schema cleaning, and relational grouping.

  
Key Topics:
  
  

  
pd.Series and pd.DataFrame internal architectures.

  
Explicit label slicing (.loc[]) vs. implicit integer coordinate indexing (.iloc[]).

  
Data sanitization: Null detection (.isna()), dropping records (.dropna()), and statistical imputation (.fillna()).

  
Relational grouping: .groupby() workflows with multi-column aggregations (.agg()).

  
Reshaping tables, sorting values, and merging disparate datasets.

  

  

  

  
6️⃣ Project 6: Statistical Data Visualization with Matplotlib & Seaborn

  

  
Focus: Visual storytelling, exploratory distributions, and publication-quality aesthetics.

  
Key Topics:
  
  

  
Matplotlib's Figure and Axes object hierarchy for multi-panel dashboards (plt.subplots).

  
Continuous feature diagnostics: Histograms, Kernel Density Estimation (KDE), and cumulative plots.

  
Categorical comparisons: Bar charts, count plots, box plots, and violin plots.

  
Multivariate collinearity: Annotated Pearson correlation heatmaps with divergent color ramps (coolwarm, viridis).

  

  

  

  
📊 Summary Comparison Matrix

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
Project	Primary Focus	Practical Skill Acquired	Key Tools Used
01	Control Flow & Loops	Algorithmic logic & sequence iteration	Vanilla Python
02	Functions & Modularity	DRY design, closures & clean interfaces	Functions, Closures, Decorators
03	Object-Oriented (OOP)	Domain modeling & stateful software systems	Classes, Inheritance, super()
04	NumPy Computing	High-speed vectorized mathematics	numpy, Vectorized Arrays
05	Pandas Wrangling	Production tabular cleaning & aggregation	pandas DataFrames & Series
06	Data Visualization	Exploratory data analysis & figure styling	matplotlib, seaborn

  

  
📁 Repository Directory Structure

  
text
python-fundamentals-track/
│
├── 01-control-flow-and-loops/
│   ├── README.md
│   └── control_flow_and_loops.ipynb
│
├── 02-functions-and-modular-programming/
│   ├── README.md
│   └── functions_and_modular_programming.ipynb
│
├── 03-object-oriented-programming/
│   ├── README.md
│   └── object_oriented_programming.ipynb
│
├── 04-numpy-numerical-computing/
│   ├── README.md
│   └── numpy_numerical_computing.ipynb
│
├── 05-pandas-data-manipulation/
│   ├── README.md
│   └── pandas_data_manipulation.ipynb
│
├── 06-data-visualization-matplotlib-seaborn/
│   ├── README.md
│   └── data_visualization_matplotlib_seaborn.ipynb
│
├── requirements.txt
└── README.md                                  <-- Track Master Documentation

  

  
🚀 Getting Started

  
1. Clone the Track Repository

  
bash
git clone https://github.com/<your-username>/python-fundamentals-track.git
cd python-fundamentals-track

  
2. Configure Environment & Install Dependencies

  
bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS / Linux:
source venv/bin/activate
pip install -r requirements.txt

  
requirements.txt

  
text
numpy>=1.22.0
pandas>=1.5.0
matplotlib>=3.6.0
seaborn>=0.12.0
jupyter>=1.0.0

  
3. Launch the Interactive Labs

  
bash
jupyter notebook

  

Navigate to any of the 6 numbered directories and open the respective .ipynb file to run the code.


  

  
🎯 Intended Audience & Prerequisites

  

  
Prerequisites: Basic computer literacy. No prior programming experience required; the track begins with introductory loops and progresses to advanced object modeling and scientific computing.

  
Outcome: Preparedness for advanced Machine Learning algorithms, Deep Learning frameworks (PyTorch/TensorFlow), and Data Engineering workflows.
