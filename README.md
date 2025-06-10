# 📊 Mathematical Modeling in Banking – Term Project (Summer Semester 2024/25)

This repository contains a two-part project for the *Mathematical Modeling in Banking* course at University at Wroclaw, focusing on building a classification model using **XGBoost** to predict whether a bank client will subscribe to a term deposit based on demographic and marketing data.

## 🗂 Project Overview

- **Topic**: Application of Mathematical Modeling in Banking
- **Goal**: Build and evaluate a classification model using XGBoost.

---

## 📌 Task Description

The goal of this project is to construct a **classification model** using **XGBoost** to predict whether a client will subscribe to a term deposit based on:
- **Demographic characteristics**
- **Marketing contact data**

---

## 📁 Project Structure

- `raport_czesc_1.ipynb`:  
  Includes:
  - Data loading and cleaning (`dane_list2.csv`)
  - Feature engineering and preprocessing
  - Exploratory Data Analysis (EDA)
  - Outlier and missing value treatment
  - Variable encoding and binary target creation
  - Correlation analysis

- `raport_czesc_2.ipynb`:  
  Includes:
  - Initial model training with default parameters
  - Performance evaluation using the **GINI coefficient**
  - Hyperparameter tuning (e.g. Bayesian optimization)
  - Feature importance and selection analysis
  - Comparison of dummy variable encoding effects
  - Final model ("champion") selection and evaluation
  - Model interpretation using **SHAP**, **Permutation Importance**, and more
  - Optional: Cross-validation and custom cut-off threshold

---

## 🧪 Tools & Technologies

- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `xgboost`
- `scikit-learn`
- `shap` (for interpretability)

---

## 📈 Key Results

- Identification of the most predictive variables
- Evaluation of model performance on training and test sets
- Interpretation of model behavior and insights into customer decisions
- Comparative analysis of different modeling choices



