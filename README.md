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
│ ├── linear_regression.py
│ ├── test_linear_regression.py
│ └── notebook_demo.ipynb
│
├── 02_logistic_regression/
├── 03_knn/
├── 04_decision_tree/
├── 05_svm/
├── 06_naive_bayes/
├── 07_k_means/
├── 08_pca/
│
├── utils/
│ ├── metrics.py # Common evaluation metrics
│ └── data_generators.py # Toy datasets for testing
│
├── references/
│ ├── math_notes.md # Derivations & formulas
│ └── algorithm_diagrams/ # Visualizations
│
├── requirements.txt
└── README.md
