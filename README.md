# Ridge-and-Lasso-Regression
Ridge and lasso regression on the California Housing dataset, with cross-validation and coefficient comparison

This project explores both the theoretical foundation and practical implementation of regularized regression models using ridge and lasso. The dataset used is the California Housing dataset, and the project compares performance metrics and coefficient shrinkage across methods.

---

## Assignment Prompt

- [Assignment PDF – SML_Task3.pdf](./SML_Task3.pdf)

---

## Project Overview

> This project combines theoretical derivation and real-world application of penalized regression methods. In Q1, we derive the closed-form solution for ridge regression and show how it resolves issues of multicollinearity and non-invertibility in the design matrix. In Q2, we apply ridge and lasso regression to the California Housing dataset, compare their performance using cross-validated hyperparameter tuning, and analyze coefficient shrinkage.

- Derived the closed-form solution for ridge regression
- Showed regularization improves invertibility
- Applied ridge and lasso regression on California Housing dataset
- Standardized features and tuned alpha (λ) via cross-validation
- Evaluated model performance using:
  - Mean Squared Error (MSE)
- Compared coefficients from ridge vs lasso

---

## Contents

- [`SMLq3a.ipynb`](./SMLq3a.ipynb) – Ridge regression derivation (theory)  
- [`SMLq3b.ipynb`](./SMLq3b.ipynb) – Ridge vs Lasso implementation  
- [`SML_Task3.pdf`](./SML_Task3.pdf) – Assignment description

---

## Tools Used

- Python 3  
- `scikit-learn`, `numpy`, `pandas`, `matplotlib`, `seaborn`

---

## Background

This project was developed during my graduate studies in Data Analytics for Economics and Finance at the University of Glasgow.

---

## 👨‍💻 Author

Ditep Nantap Rejoice  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nantap-ditep-00490b231)
