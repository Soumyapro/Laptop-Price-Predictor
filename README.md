# 💻 Laptop Price Predictor

[Laptop Price]!(https://img.freepik.com/free-photo/woman-checking-out-free-design-resources-website_53876-138963.jpg?t=st=1743318618~exp=1743322218~hmac=c5fb2afaf736acf1e416160c7cda14c1b68f3535c51945fc8e8b29c00c999bfd&w=826)

A machine learning project that predicts laptop prices based on their specifications using various regression models. This end-to-end pipeline includes data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 📊 Project Overview

This project explores a dataset of laptops and their specifications to predict prices using multiple regression techniques. The best-performing model is deployed through a pipeline that includes preprocessing and prediction steps.

---

## 🔧 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Dataset

The dataset `laptop_data.csv` includes the following features:

- Company (Brand)
- Type (Notebook, Ultrabook, etc.)
- RAM, Weight, Screen Size
- Processor, GPU, Operating System
- Memory (HDD, SSD, etc.)
- Target Variable: **Price**

---

## 🧪 Models Implemented

- Linear Regression
- Ridge & Lasso Regression
- Decision Tree Regressor
- K-Nearest Neighbors Regressor
- Random Forest Regressor ✅ *(Best Performance)*
- Gradient Boosting, AdaBoost, Extra Trees
- XGBoost
- Support Vector Regressor (SVR)

---

## 🏆 Best Model Performance

**Model:** Random Forest Regressor  
**Hyperparameters:**  
- `n_estimators = 100`  
- `max_depth = 15`  
- `max_samples = 0.5`  
- `max_features = 0.75`  

**Evaluation Metrics:**

| Metric | Value |
|--------|-------|
| R² Score | **0.88** |
| MAE | **0.15** (after scaling) |

