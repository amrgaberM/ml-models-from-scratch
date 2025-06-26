🧠 ML Models from Scratch
A professional-grade implementation of core Machine Learning algorithms from first principles — in pure Python and NumPy.
This repository is a foundational engineering exercise: each model is built from scratch to demonstrate mathematical understanding, implementation skill, and production-readiness — without relying on high-level libraries like scikit-learn or TensorFlow.

🎯 Project Objectives

✅ Reinforce theoretical and mathematical foundations of ML
✅ Translate theory into production-ready Python code
✅ Improve debugging, testing, and numerical reasoning skills
✅ Build a portfolio that demonstrates deep understanding of algorithms


📦 Algorithms Implemented



Model
Type
Core .py
Demo Notebook
Unit Tests



Linear Regression
Supervised
✅
✅
✅


Logistic Regression
Supervised
✅
✅
✅


K-Nearest Neighbors (KNN)
Supervised
✅
✅
✅


Decision Tree
Supervised
✅
✅
✅


Support Vector Machine (SVM)
Supervised
✅
✅
✅


Naive Bayes
Supervised
⏳
✅
—


K-Means Clustering
Unsupervised
✅
✅
—


Principal Component Analysis (PCA)
Unsupervised
✅
✅
—


Each implementation includes:

Clean, modular code with inline documentation
Jupyter notebook walkthrough and interactive demo
(Optional) Unit tests to verify behavior and correctness


🗂️ Repository Structure
ml-models-from-scratch/
│
├── 01_linear_regression/
│   ├── linear_regression.py
│   ├── test_linear_regression.py
│   └── notebook_demo.ipynb
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
│   ├── metrics.py          # Common evaluation metrics
│   └── data_generators.py  # Toy datasets for testing
│
├── references/
│   ├── math_notes.md       # Derivations & formulas
│   └── algorithm_diagrams/ # Optional visualizations
│
├── requirements.txt
└── README.md


🧪 Testing & Reliability
Some models include lightweight unit tests that verify:

Correctness of outputs
Basic numerical behavior (e.g., convergence, prediction shape)
No runtime exceptions on minimal inputs

Tests are written to be run manually or integrated later with pytest or CI tools.

🛠️ Tech Stack

Language: Python 3.10+
Core Library: NumPy
Visualization: Matplotlib
Notebook Environment: Jupyter

No ML libraries like scikit-learn or TensorFlow are used — this project is about raw logic, not API usage.

🔍 Learning Approach
Each model is built with the following layered approach:

Mathematical FoundationCovers gradients, loss functions, entropy, distance metrics, matrix operations, etc.

From-Scratch ImplementationEncapsulated Python classes or functions — just NumPy and raw Python.

Interactive DemoJupyter Notebooks that:

Walk through toy datasets
Visualize results and convergence
Include markdown explanations




📈 Example Use Case: Linear Regression
Location: 01_linear_regression/
Includes:

linear_regression.py: Class with gradient descent logic
test_linear_regression.py: Checks for correct predictions and training
notebook_demo.ipynb: Generates data, trains model, plots fit


📚 References

Géron, Aurélien – Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow
Nield, Thomas – Essential Math for Data Science
Ng, Andrew – Machine Learning (Coursera)
Stanford CS229, MIT 6.036, and CMU 10-701
Introduction to Statistical Learning (ISLR)
Scholarly papers, open-source implementations, and visual blogs


📜 License
This project is released under the MIT License.You are free to use, adapt, and build upon it for educational or personal projects.

👤 Author & Intent
This repository is part of a larger journey to become a Machine Learning Engineer with strong mathematical foundations and production-level skills.
It reflects:

Consistent engineering habits
Applied mathematics and algorithms
A deep understanding of how models actually work

For feedback, collaboration, or hiring inquiries — feel free to connect.
