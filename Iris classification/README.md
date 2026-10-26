# Datheon_Machine_Learning_-_Data_Science_Internship
# Iris Species Classification

A machine learning project built with Scikit-Learn to classify Iris flower species (*Setosa*, *Versicolor*, *Virginica*) using feature measurements and comparative model evaluation.

---

## Overview

This project explores the classic Iris dataset, performs feature scaling and data preprocessing, and compares the classification performance of **Logistic Regression** and **Decision Tree Classifier**.

Key aspects covered:
- Exploratory Data Analysis (EDA) using statistical summaries and pairplots.
- Feature scaling with `StandardScaler`.
- Model training and multi-class classification.
- Evaluation via accuracy metrics, classification reports, and confusion matrix heatmaps.

---

## Dataset

The dataset consists of 150 samples across 3 classes (50 samples per species) with 4 features:
- `sepal_length` (cm)
- `sepal_width` (cm)
- `petal_length` (cm)
- `petal_width` (cm)
- `species` (Target: *Iris-setosa*, *Iris-versicolor*, *Iris-virginica*)

---

## Project Workflow

1. **Exploratory Data Analysis (EDA):**
   - Statistical distribution analysis using Pandas (`info()`, `describe()`).
   - Pairwise relationship visualization using Seaborn's `pairplot`.
2. **Data Preprocessing:**
   - Feature-target separation (`X` and `y`).
   - Train-test split (80% training, 20% testing with `random_state=42`).
   - Feature standardization using `StandardScaler`.
3. **Model Training:**
   - **Logistic Regression** (baseline linear model).
   - **Decision Tree Classifier** (non-linear baseline).
4. **Evaluation:**
   - Multi-class Accuracy score calculation.
   - Confusion matrix visualization using Seaborn heatmaps.

---

## Results

| Model | Test Accuracy |
| :--- | :---: |
| **Logistic Regression** | **96.67%** |
| **Decision Tree** | Evaluated |

---
