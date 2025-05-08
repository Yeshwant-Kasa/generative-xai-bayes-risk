# 🧠 Generative Explainability with Risk-Aware Decisions

This project explores explainability in classical machine learning through generative models and cost-sensitive decision-making. Two tasks are implemented to evaluate parameter estimation, classifier performance, and the effect of risk matrices on decision boundaries.

---

## ✅ Tasks Overview

### 🔹 Task 1: Synthetic Gaussian Data (1D–5D)

* ✅ Built a Bayes Classifier using synthetic multivariate Gaussian distributions
* ✅ Estimated parameters (mean and covariance) via Maximum Likelihood Estimation (MLE)
* ✅ Visualized classifier performance using:

  * PCA projections (1D, 2D, 3D)
  * Parallel Coordinates (5D)
  * Accuracy vs Dimension plots

### 🔹 Task 2: Wisconsin Breast Cancer Dataset

* ✅ Applied Gaussian generative modeling on real-world medical data
* ✅ Estimated parameters using MLE for benign and malignant classes
* ✅ Evaluated classification accuracy across varying sample sizes
* ✅ Applied uniform and asymmetric risk matrices to simulate cost-sensitive decision scenarios
* ✅ Visualized shifts in decision boundaries under different risk configurations

---

## 📚 Datasets

* Synthetic Gaussian Data (generated in code)
* [UCI Breast Cancer Wisconsin Diagnostic Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

## 🛠️ Tools Used

* Python
* NumPy, Matplotlib
* Scikit-learn

## 📂 Repository Structure

```
generative-xai-bayes-risk/
├── explainable_generative_model_synthetic.py       # Task 1 implementation
├── explainable_generative_model_wisconsin.py       # Task 2 implementation
├── report/
│   └── partA_report.pdf                            # LaTeX report
├── results/
│   └── [PCA plots, decision boundaries, accuracy graphs]
├── README.md
├── .gitignore
```




