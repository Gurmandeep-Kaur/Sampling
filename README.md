# Sampling

This repository studies how different sampling techniques affect the performance of machine learning models on an imbalanced dataset. The Credit Card Fraud dataset is used, where fraudulent transactions form a very small portion of the total data. To handle this imbalance, multiple sampling strategies are applied and their impact on various classifiers is analyzed.

---

## Overview

Real-world datasets are often imbalanced, which can cause machine learning models to perform poorly on minority classes. In this project, the original imbalanced dataset is first balanced and then five different sampling techniques are applied. Each sampled dataset is used to train five machine learning models. The models are evaluated using accuracy, and the results are compared in a tabular format.

The goal is to observe how different sampling methods influence model performance and to identify which sampling technique works best for each model.

---

## Dataset

The dataset used is Creditcard_data.csv.
- Target column: Class
- Class 0 represents normal transactions
- Class 1 represents fraudulent transactions

Initially, the dataset is highly imbalanced. A balanced version of the dataset is created before applying further sampling techniques.

---

## Sampling Techniques

Five sampling approaches are used:
- Random Over Sampling
- SMOTE (Synthetic Minority Over-sampling Technique)
- Random Under Sampling
- SMOTEENN (SMOTE + Edited Nearest Neighbors)
- Stratified Split Sampling

Each method produces a different version of the dataset, which is then used for model training.

---

## Machine Learning Models

The following classification models are trained and evaluated:
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- K-Nearest Neighbors
- Support Vector Machine

The dataset is split into training and testing sets using an 80–20 ratio for each sampling method.

---

## Results

A comparison table is generated showing accuracy scores for all combinations of sampling techniques and models. From this table, the best-performing sampling method for each model is identified using the maximum accuracy value.

The results demonstrate that different models respond differently to sampling strategies, and no single sampling technique is universally optimal for all models.

---

## Author

Gurmandeep Kaur

---
