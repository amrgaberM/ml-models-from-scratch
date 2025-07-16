# ML Models from Scratch

**A professional, first-principles implementation of core Machine Learning algorithms using only Python and NumPy.**

This repository is a foundational engineering exercise designed to build a deep understanding of machine learning by re-implementing key algorithms without relying on high-level libraries like Scikit-learn or TensorFlow. Each algorithm is developed from scratch to reinforce theory, numerical reasoning, and production-grade Python practices.

## Project Goals

* Strengthen core ML theory and mathematical intuition
* Translate algorithms into clean, vectorized Python code
* Improve implementation, debugging, and testing skills
* Build a project portfolio that reflects deep algorithmic understanding

## Algorithms Implemented

We focus on both **supervised** and **unsupervised** algorithms essential to ML engineers.

### Supervised Learning
* Linear Regression
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Support Vector Machine (SVM)
* Naive Bayes Classifier

### Unsupervised Learning
* K-Means Clustering
* Principal Component Analysis (PCA)

## Repository Structure

```
.
├── 01_linear_regression/
│   ├── linear_regression.py
│   ├── test_linear_regression.py
│   └── notebook_demo.ipynb
│
├── 02_logistic_regression/
│   ├── logistic_regression.py
│   ├── test_logistic_regression.py
│   └── notebook_demo.ipynb
│
├── 03_knn/
│   ├── knn.py
│   ├── test_knn.py
│   └── notebook_demo.ipynb
│
├── 04_decision_tree/
│   ├── decision_tree.py
│   ├── test_decision_tree.py
│   └── notebook_demo.ipynb
│
├── 05_svm/
│   ├── svm.py
│   ├── test_svm.py
│   └── notebook_demo.ipynb
│
├── 06_naive_bayes/
│   └── notebook_demo.ipynb
│
├── 07_k_means/
│   ├── kmeans.py
│   └── notebook_demo.ipynb
│
├── 08_pca/
│   ├── pca.py
│   └── notebook_demo.ipynb
│
├── utils/
│   ├── metrics.py
│   └── data_generators.py
│
├── references/
│   ├── math_notes.md
│   └── algorithm_diagrams/
│
├── requirements.txt
└── README.md
```

## Key Features

* No ML frameworks used (no scikit-learn, no TensorFlow)
* Clear code structure for readability and reusability
* Jupyter notebooks for visual demos and intuition
* Lightweight unit tests for correctness
* Utility functions for metrics and data generation

## Testing & Quality

Basic unit tests are included with each algorithm to verify implementation correctness. These can be extended with `pytest` or integrated into CI pipelines for production workflows.

## Tech Stack

* Python 3.10+
* NumPy
* Matplotlib
* Jupyter Notebooks

## Learning Philosophy

"Understand it. Build it. Explain it."

Each model is:
1. Derived from its mathematical formulation
2. Implemented with clean, idiomatic NumPy code
3. Visualized and explained through a demo notebook

This repo favors **understanding over abstraction** — no shortcuts, no magic methods.
