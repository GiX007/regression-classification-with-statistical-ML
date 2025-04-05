This repository contains Jupyter Notebooks implementing a variety of statistical machine learning methods applied to regression and classification problems. 

Contents:

  1. regression.ipynb. Implemented methods:
     * Least Squares (2nd, 5th, and 10th-degree polynomial models).
     * Full Bayesian Inference with different priors and variances.
     * Expectation-Maximization (EM) to estimate noise and prior variance.
     * Parzen Window Regression with Gaussian kernels (non-parametric).
     * Evaluation through different repeated samples and MSE comparison.
       
  2. classification.ipynb. Implemented methods:
     * k-Nearest Neighbors (k-NN) with cross-validation.
     * Bayes classifiers under:
       * Diagonal covariance with equal variances (shared across features).
       * Full covariance matrices (non-diagonal).
       * Naive Bayes with Gaussian marginals.
       * Naive Bayes with Parzen window estimation.
       * Gaussian Mixture Models (GMMs) with EM and BIC-based component selection.

Each method is thoroughly evaluated and visualized, with clear comments and plots that compare model behavior, prediction errors, and generalization across different settings and assumptions. The data/ folder contains the dataset used for the classification experiments. Feel free to open issues or contribute improvements!
