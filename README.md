# Quantum Machine Learning for Credit Card Fraud Detection

## Overview

This project explores the use of **Quantum Machine Learning (QML)** techniques for binary credit card fraud detection. Specifically, we compare classical classifiers such as Logistic Regression and SVM with quantum models like **Variational Quantum Classifiers (VQC)**. Our goal is to evaluate whether QML approaches offer meaningful performance benefits in fraud detection scenarios.

## Project Goals

- Train and evaluate classical and quantum classifiers on a realistic fraud detection dataset.
- Analyze model performance using **recall**, **F1-score**, **AUPRC**, and **confusion matrices**.
- Assess practical aspects of QML, including training time, circuit depth, and scalability.

## Dataset

We use the **Credit Card Fraud Detection dataset** from Kaggle, which includes:

- 284,807 transactions over a two-day period.
- 492 fraud cases (0.172%).
- Features: 
  - `Time`, `Amount`
  - `V1` to `V28` (PCA-transformed for confidentiality)
  - `Class` (1 = Fraud, 0 = Legitimate)

### How to Get the Dataset

1. Go to the [Kaggle dataset page](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Click **"Download"** (you must be logged in).
3. Extract the downloaded `creditcard.csv` file.
4. Place it in your project directory.

> You may also use the Kaggle API if you're running this in a notebook or server:
```bash
pip install kaggle
