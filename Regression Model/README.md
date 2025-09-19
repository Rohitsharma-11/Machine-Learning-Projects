# 🤖 House Price Prediction – Regression Models  

## 🧠 Project by: Rohit Sharma  

---

## 📌 Project Description  

This project focuses on building and evaluating regression models to predict a continuous variable (house prices). Multiple machine learning algorithms were implemented and compared to identify the best-performing model.  

---

## 🎯 Problem Statement  

Predicting house prices accurately is crucial for real estate businesses, buyers, and sellers. This project aims to:  
- Build predictive models using different ML algorithms.  
- Compare performance using regression metrics.  
- Recommend the most accurate model for practical use.  

---

## 🧩 Project Overview  

We implemented machine learning regression models to:  
- Split data into training and testing sets.  
- Train and evaluate multiple algorithms (Linear Regression, Decision Tree, Random Forest).  
- Measure performance using **Mean Squared Error (MSE)** and **R-squared (R²)**.  

---

## 🧾 Data Understanding  

- Dataset includes features such as:  
  - Square footage, number of bedrooms, number of bathrooms.  
  - Location-based features.  
  - Other property characteristics.  
- Target variable: **House Price (continuous value).**  

---

## 🧼 Data Preparation  

- Removed missing/duplicate values.  
- Feature scaling and encoding categorical variables.  
- Split dataset into **80% training** and **20% testing** sets.  

---

## 🤖 Modeling  

### 🔹 Linear Regression  
- Simple baseline model.  
- Accuracy: **70% (R² score).**  

### 🌳 Decision Tree Regressor  
- Captures non-linear relationships.  
- Accuracy: **82% (R² score).**  

### 🌲 Random Forest Regressor  
- Ensemble of multiple decision trees.  
- Accuracy: **90% (R² score).**  

---

## 📊 Results & Comparisons  

| Model              | Accuracy (R²) | Remarks                        |  
|--------------------|---------------|--------------------------------|  
| Linear Regression  | 70%           | Good baseline, underfits data. |  
| Decision Tree      | 82%           | Better, but prone to overfitting. |  
| Random Forest      | 90%           | Best performance, balanced model. |  

---

## 📍 Insights Derived  

1. **Linear Regression** served as a baseline but struggled with complex patterns.  
2. **Decision Trees** performed well but had overfitting issues.  
3. **Random Forest** provided the best balance between accuracy and generalization.  

---

## ⚠️ Challenges Faced  

- Handling missing data and feature scaling.  
- Avoiding overfitting in tree-based models.  
- Balancing interpretability and accuracy.  

---

## 🚀 Future Scope  

- Experiment with advanced models (Gradient Boosting, XGBoost, Neural Networks).  
- Hyperparameter tuning to further optimize performance.  
- Deploy model as a web app for real-world predictions.  

---

## ✅ Final Outcome  

The **Random Forest Regressor** outperformed other models with **90% accuracy**, making it the most reliable choice for predicting house prices.  

---

📌 Tools Used: **Python, scikit-learn, pandas, matplotlib**  
