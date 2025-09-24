# Regression & Classification with Statistical ML 

This repository contains Jupyter notebooks implementing a variety of **statistical machine learning methods** applied to regression and classification problems. Each method is explained, visualized, and compared across different assumptions.

---

## Contents

### 1. `regression.ipynb`
Implemented methods:
- **Least Squares** – polynomial regression (2nd, 5th, and 10th-degree models)  
- **Full Bayesian Inference** – with different priors and variances  
- **Expectation-Maximization (EM)** – estimating noise and prior variance  
- **Parzen Window Regression** – non-parametric, Gaussian kernels  
- **Evaluation** – repeated sampling, MSE comparison, visualization  

### 2. `classification.ipynb`
Implemented methods:
- **k-Nearest Neighbors (k-NN)** with cross-validation  
- **Bayes Classifiers** under multiple assumptions:  
  - Diagonal covariance with equal variances  
  - Full covariance matrices  
  - Naive Bayes with Gaussian marginals  
  - Naive Bayes with Parzen window estimation  
- **Gaussian Mixture Models (GMMs)** with EM and BIC-based component selection  

The `data/` folder includes the dataset used in the classification experiments.

---

## Purpose
- Provide a **hands-on implementation** of classic statistical ML methods  
- Show clear **visual comparisons** of model predictions, errors, and generalization  
- Build intuition for the **fundamentals of machine learning** by exploring the strengths and limitations of different approaches  
