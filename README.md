This repository contains Jupyter Notebooks implementing a variety of statistical machine learning methods applied to regression and classification problems. 



The work is organized into two main parts:

Problem 1: Statistical approaches to regression (Least Squares, Bayesian inference, Expectation-Maximization, Parzen windows)

Problem 2: Classification using k-Nearest Neighbors (k-NN) and Bayes classifiers under various assumptions

Contents:

* regression.ipynb.

Implemented methods:

Least Squares (2nd, 5th, and 10th-degree polynomial models)

Bayesian Linear Regression with different priors and variances

Expectation-Maximization (EM) to estimate noise and prior variance

Parzen Window Regression with Gaussian kernels (non-parametric)

Evaluation through Monte Carlo experiments and MSE comparison

Problem 2: Classification

Implemented methods:

k-Nearest Neighbors (k-NN) with cross-validation

Bayes classifiers under:

Diagonal covariance with equal variances (shared across features)

Full covariance matrices (non-diagonal)

Naive Bayes with Gaussian marginals

Naive Bayes with Parzen window estimation

Gaussian Mixture Models (GMMs) with EM and BIC-based component selection


Results

Each method is evaluated and visualized, with clear comments and plots comparing model behavior, error, and generalization across different settings (e.g., training set sizes, priors, model complexity).

Feel free to open issues or contribute improvements!
