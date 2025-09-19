# 🔍 Classification Models – Logistic Regression & Random Forest  

## 🧠 Project by: Rohit Sharma  

---

## 📌 Project Description  

This project focuses on building and evaluating classification models to predict categorical outcomes. Logistic Regression and Random Forest were implemented and compared, both achieving excellent performance.  

---

## 🎯 Problem Statement  

Accurate classification is critical for decision-making in domains like healthcare, finance, and customer analytics. This project aims to:  
- Build a **Logistic Regression model** for classification tasks.  
- Compare performance with **Random Forest**.  
- Evaluate models using classification metrics beyond simple accuracy.  

---

## 🧩 Project Overview  

We implemented classification models to:  
- Preprocess data (handle categorical variables, scale features).  
- Train and evaluate **Logistic Regression** and **Random Forest**.  
- Compare results using metrics like **Accuracy, Precision, Recall, F1-score, and ROC-AUC**.  

---

## 🧾 Data Understanding  

- Dataset contains:
  - Numerical and categorical features.
  - Target variable: Categorical outcome with 3 classes (Class 0, Class 1, Class 2).
- Goal: Predict whether a sample belongs to Class 0, Class 1, or Class 2.

---

## 🧼 Data Preparation  

- Handled missing values and categorical encoding.  
- Applied feature scaling for Logistic Regression.  
- Split dataset into **Training (80%)** and **Testing (20%)** sets.  

---

## 🤖 Modeling  

### 🔹 Logistic Regression  
- Simple, interpretable model.  
- Evaluated with **accuracy, precision, recall, ROC-AUC**.  
- Achieved **100% accuracy** on test data.  

### 🌲 Random Forest Classifier  
- Ensemble-based model.  
- Evaluated with the same metrics.  
- Also achieved **100% accuracy** on test data.  

---

## 📊 Results & Comparisons  

| Model                | Accuracy | Precision | Recall | F1-Score | ROC-AUC | Remarks |  
|-----------------------|----------|-----------|--------|----------|---------|---------|  
| Logistic Regression   | 100%     | 100%      | 100%   | 100%     | 1.0     | Perfect classification |  
| Random Forest         | 100%     | 100%      | 100%   | 100%     | 1.0     | Perfect classification |  

---

## 📍 Insights Derived  

1. Both models achieved **100% accuracy**, showing the dataset was highly separable.  
2. Logistic Regression provides interpretability, while Random Forest adds robustness.  
3. Model selection can depend on **scalability and explainability** rather than accuracy alone.  

---

## ⚠️ Challenges Faced  

- Risk of **overfitting** with perfect scores – needs validation on unseen data.  
- Balancing interpretability (Logistic Regression) vs. power (Random Forest).  
- Ensuring categorical feature encoding was consistent.  

---

## 🚀 Future Scope  

- Test on larger and more complex datasets.  
- Add other classifiers like **SVM, Gradient Boosting**.  
- Perform **hyperparameter tuning** to ensure generalization.  
- Deploy as a classification API for real-world use cases.  

---

## ✅ Final Outcome  

Both **Logistic Regression** and **Random Forest** achieved **100% accuracy**, with strong precision, recall, and AUC scores. This shows the dataset was highly separable, and both models performed exceptionally well.  

---

📌 Tools Used: **Python, scikit-learn, pandas, matplotlib**  
