# 🚲 Capital Bikeshare - Machine Learning (Supervised Learning)

This project presents a supervised learning approach using the **Capital Bikeshare** dataset for predictive modeling and model evaluation. It covers the application of regression, classification, and model validation techniques through a structured data science pipeline.

## 📂 Dataset
The dataset used in this project comes from [Capital Bikeshare System Data](https://ride.capitalbikeshare.com/system-data), specifically focusing on trip data from March and October 2024.

## 🧠 Problem Statement
The objective is to explore and model bike-sharing patterns using:
- **Regression models** to predict continuous outcomes such as pollutant concentration levels (`PU_ct`, `DO_ct`)
- **Classification models** to predict categorical outcomes
- **Regularization & Cross-Validation techniques** to improve model generalization and select optimal model complexity

## 📊 Techniques Applied

### ✅ 1. Regression Modeling
- Multiple Linear Regression
- Lasso and Ridge Regression
- Evaluation using **Mean Squared Error (MSE)** and **R² score**

### ✅ 2. Classification Tasks
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Classifiers (Linear and RBF kernel)
- Model comparison based on **accuracy scores**

### ✅ 3. Model Regularization and Cross Validation
- Applied **Lasso Regression** with:
  - Coefficient path visualization
  - GridSearchCV and LassoCV for best hyperparameter (`alpha`) selection
  - Cross-validated performance metrics
- Out-of-sample MSE evaluation for model robustness

## 📈 Highlights
- Feature scaling and dummy encoding handled appropriately
- Lasso Regularization helped identify the most impactful predictors
- Hyperparameter tuning using cross-validation ensured optimal model performance
- Visualized how regularization affects feature selection

## 📁 File Structure
- `ML_Supervised.ipynb` - Main Jupyter notebook with all analysis
- `README.md` - Project overview

## 📌 Conclusion
This project showcases a complete supervised machine learning workflow from data preprocessing, model building, hyperparameter tuning to model evaluation using real-world data. It demonstrates strong foundations in regression, classification, and regularization using Python and Scikit-learn.

---

Feel free to clone or fork this repository for learning or practice!

