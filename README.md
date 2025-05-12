# Quantum Machine Learning for Credit Card Fraud Detection
final product video walkthrough: https://www.youtube.com/watch?v=TSL_RbNKyI8&ab_channel=ryanWang

## Overview

This project compares classical models (Logistic Regression, SVM) with quantum approaches, particularly the **Variational Quantum Classifier (VQC)**, for binary fraud detection. We aim to evaluate whether quantum models can match or exceed classical performance on realistic financial data.

## Goals

- Train classical and quantum classifiers on real-world data.
- Evaluate using **recall**, **F1-score**, and **AUPRC**.
- Analyze quantum-specific constraints like circuit depth and qubit limits.

## Dataset

We use the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle, containing:

- 284,807 transactions (492 fraud)
- Features: `Time`, `Amount`, `V1`–`V28` (PCA), and `Class` (1 = fraud)

### 📥 Download Instructions

1. Sign in at Kaggle and go to the [dataset page](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Click **Download**, unzip it, and place `creditcard.csv` in your project folder.

**Alternatively (via Kaggle API):**
```bash
pip install kaggle
kaggle datasets download -d mlg-ulb/creditcardfraud
unzip creditcardfraud.zip

