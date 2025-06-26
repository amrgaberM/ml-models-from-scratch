# 🧠 ML Models from Scratch

A professional-grade implementation of core Machine Learning algorithms **from first principles** — in pure Python and NumPy. This repository demonstrates mathematical understanding, implementation skill, and production-readiness without relying on high-level ML libraries.

## 🎯 Project Objectives
- ✅ Reinforce theoretical and mathematical foundations of ML  
- ✅ Translate theory into production-ready Python code  
- ✅ Improve debugging, testing, and numerical reasoning skills  
- ✅ Build a portfolio demonstrating deep algorithm understanding  

---

## 📦 Implemented Algorithms

| Model                  | Type        | Core `.py` | Demo Notebook | Unit Tests |
|------------------------|-------------|------------|---------------|------------|
| Linear Regression      | Supervised  | ✅         | ✅            | ✅         |
| Logistic Regression    | Supervised  | ✅         | ✅            | ✅         |
| K-Nearest Neighbors    | Supervised  | ✅         | ✅            | ✅         |
| Decision Tree          | Supervised  | ✅         | ✅            | ✅         |
| Support Vector Machine | Supervised  | ✅         | ✅            | ✅         |
| Naive Bayes            | Supervised  | ⏳         | ✅            | —          |
| K-Means Clustering     | Unsupervised| ✅         | ✅            | —          |
| Principal Component Analysis | Unsupervised| ✅     | ✅            | —          |

**Each implementation includes:**
- Clean, modular code with inline documentation  
- Jupyter notebook walkthrough and interactive demo  
- (Optional) Unit tests for behavior verification  

---

## 🗂️ Repository Structure
ml-models-from-scratch/
│
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
│   ├── metrics.py          # accuracy, mse, log-loss, etc.
│   └── data_generators.py  # create toy datasets
│
├── references/
│   ├── math_notes.md       # derivations, key formulas
│   └── algorithm_diagrams/ # optional images for notebooks
│
├── requirements.txt
└── README.md
