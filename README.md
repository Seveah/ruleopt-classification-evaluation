# Interpretable Machine Learning: Evaluating RUG for Credit Risk Classification

This repository contains the code and materials for my Bachelor thesis on interpretable machine learning. The project evaluates the Rule Generation for Classification (RUG) method and compares it with two interpretable models: CORELS and SLIM.

The study focuses on binary credit risk classification using the German Credit dataset.

## Research Objective

Many machine learning models achieve high predictive performance but lack interpretability. This project investigates interpretable alternatives by comparing three glass-box classification models:

- RUG (Rule Generation for Classification)
- CORELS (Certifiably Optimal Rule Lists)
- SLIM (Supersparse Linear Integer Models)

The goal is to evaluate their predictive performance and interpretability in a credit scoring task.

## Dataset

German Credit Dataset  
UCI Machine Learning Repository

- 1000 observations  
- 20 features  
- Binary classification (good credit vs bad credit)

Categorical variables are one-hot encoded before modeling.

## Methodology

- Train-test split: 80% training, 20% testing
- 5-fold cross-validation for hyperparameter tuning
- Evaluation on unseen test data

Performance metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

Interpretability metrics:

- number of rules
- rule length

## Models Compared

### RUG
Rule-based classification using optimization and 
column generation.

### CORELS
Ordered rule list model with optimality guarantees.

### SLIM
Sparse linear scoring model using integer coefficients.


## Technologies

Python  
ruleopt  
pandas  
numpy  
scikit-learn  
matplotlib



