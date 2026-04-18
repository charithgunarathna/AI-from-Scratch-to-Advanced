# 🏛️ Module 01: Foundations of AI (Mathematics & Python)

![Level](https://img.shields.io/badge/Level-Beginner-brightgreen)
![Maintained By](https://img.shields.io/badge/Maintained%20By-Charith%20Gunarathna-orange)
![Focus](https://img.shields.io/badge/Focus-Math_%26_Programming-blue)

Welcome to the foundation of Artificial Intelligence. To build world-class AI models, you must first master the language of machines: Mathematics and Python. This module provides a comprehensive deep dive into the absolute prerequisites for machine learning and data science.

---

## 🧮 The Mathematical Pillar

Artificial Intelligence is essentially "Applied Mathematics." A strong grasp of these concepts separates a true AI Engineer from someone who simply copies and pastes code.

### 1. Linear Algebra (The Data Representation)
Linear algebra dictates how we represent data and network weights in multi-dimensional space.
* **Scalars, Vectors, Matrices, and Tensors:** Understanding dimensions. (e.g., A colored image is a 3D Tensor: Height × Width × RGB channels).
* **Matrix Multiplication (Dot Product):** The core mathematical operation powering forward propagation in neural networks.
* **Eigenvalues, Eigenvectors & SVD:** Crucial for dimensionality reduction techniques like PCA (Principal Component Analysis).

### 2. Calculus (The Engine of Learning)
Calculus tells our AI how to improve its predictions by minimizing errors over time.
* **Derivatives & Partial Derivatives:** Measuring exactly how a tiny change in a specific weight affects the overall error of the model.
* **The Chain Rule:** The mathematical foundation of **Backpropagation** (how neural networks learn from their mistakes).
* **Gradients:** Vectors of partial derivatives pointing in the direction of the steepest ascent. We use "Gradient Descent" to move in the opposite direction to find the minimum error.

### 3. Probability & Statistics (Handling Uncertainty)
AI models do not give absolute answers; they give probabilistic predictions.
* **Probability Distributions:** Normal (Gaussian), Binomial, and Poisson distributions.
* **Bayes' Theorem:** Updating the probability of a hypothesis as more evidence/data becomes available.
* **Statistical Significance:** Z-scores, P-values, A/B testing, and hypothesis testing.

---

## 🐍 Python for Data Science: The Industry Standard

Python is the undisputed king of AI. You must master its core data science stack before building models:

| Library | Core Functionality | Essential Skills to Master |
| :--- | :--- | :--- |
| **NumPy** | High-performance numerical computing. | Vectorization, Broadcasting, Tensor manipulation, memory efficiency. |
| **Pandas** | Data manipulation and analysis. | DataFrames, handling missing values, GroupBy operations, Merging. |
| **Matplotlib & Seaborn** | Data visualization. | Histograms, Scatter plots, Correlation heatmaps, Box plots for outliers. |
| **Scikit-Learn** | Basic machine learning tools. | Train/test splitting, Preprocessing pipelines, Metrics. |

---

## 🔄 The Data Preprocessing Pipeline

Real-world data is messy. Before feeding data into an AI model, it must be rigorously cleaned and transformed.

```mermaid
graph LR;
    A[Raw Data Collection] --> B[Data Cleaning & Imputation];
    B --> C[Feature Engineering];
    C --> D[Normalization / Scaling];
    D --> E[Ready for ML Models];
    
    style A fill:#2b2d42,color:#fff
    style C fill:#ef233c,color:#fff
    style E fill:#2a9d8f,color:#fff
