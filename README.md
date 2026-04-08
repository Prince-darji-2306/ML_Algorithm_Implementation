# 🤖 Machine Learning From Scratch

A comprehensive collection of fundamental Machine Learning algorithms implemented from scratch using Python, NumPy, and Pandas. This project follows a structured "Proper Manner" approach to ensure clarity, reproducibility, and visual intuition.

---

## 🚀 Project Philosophy

1.  **From Scratch**: Every algorithm is implemented without high-level ML libraries like scikit-learn for the core logic.
2.  **Proper Manner**: Each notebook is strictly organized into:
    - **Data Generation**: Creating synthetic, complex datasets.
    - **Implementation**: Clean, logic-focused classes (student-friendly).
    - **Training**: Direct model fitting and evaluation.
    - **Visualization**: Rich, visual decision boundaries and metrics.
3.  **Visual Excellence**: Premium visualizations using Matplotlib and Seaborn to intuitively explain model behavior.
4.  **Simplicity**: Refined code that is "not complex yet perfect."

---

## 📂 Project Structure

```text
Machine Learning/
├── Supervised/
│   ├── Support Vector Machine/
│   │   ├── support_vector_classification.ipynb (Primal Gradient Descent)
│   │   └── support_vector_regression.ipynb (Primal Gradient Descent)
│   ├── Linear Regression/
│   ├── Logistic Regression/
│   ├── Decision Tree/
│   ├── Naive Bayes/
│   ├── K Nearest Neighbour/
│   └── Random Forest/
├── Unsupervised/
│   ├── Clustering/
│   │   ├── kmeans.ipynb (K-Means++)
│   │   ├── agglomerative.ipynb
│   │   ├── divisive.ipynb
│   │   ├── dbscan.ipynb
│   │   └── hdbscan.ipynb
│   └── Dimensionality Reduction/
└── LDA.ipynb
```

---

## 🧪 Key Implementations

### Supervised Learning
- **Support Vector Machines**: Refactored to use **Primal Gradient Descent** for maximum code simplicity while maintaining robust decision boundaries.
- **Tree-based Models**: Custom implementations of Decision Trees and Random Forests.

### Unsupervised Learning (Clustering)
- **Advanced Centroids**: K-Means with **K-Means++** probabilistic initialization.
- **Hierarchical**: Both **Agglomerative** (bottom-up) and **Divisive** (top-down) strategies.
- **Density-Based**: **DBSCAN** and **HDBSCAN** for non-spherical clusters found in complex datasets.

---

## 📈 Performance Evaluation

We don't just train; we measure quality:
- **Accuracy & MSE**: Standard metrics for classification and regression.
- **Silhouette Score**: Integrated into all clustering algorithms to quantitatively assess cluster separation.
- **Decision Boundaries**: Visualized contour plots for all classifiers.

---

## 🛠️ Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn (Used only for metric calculations and data conversion)

---

## 👨‍💻 Usage

Simply open any `.` file in a Jupyter environment (VS Code, JupyterLab, etc.) and run the cells sequentially. Each notebook is self-contained with its own data generation logic.
