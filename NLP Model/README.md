# 📚 NLP Text Classification – Naive Bayes Models  

## 🧠 Project by: Rohit Sharma  

---

## 📌 Project Description  

This project applies **Natural Language Processing (NLP)** techniques to classify text data into categories (e.g., spam detection, sentiment analysis). Multiple **Naive Bayes classifiers** were trained and compared to evaluate performance.  

---

## 🎯 Problem Statement  

Text classification is a core task in NLP with applications in spam detection, sentiment analysis, and document categorization. The goal of this project is to:  
- Preprocess raw text into clean, structured input.  
- Convert text into numerical form using **TF-IDF/Word2Vec**.  
- Train **Naive Bayes models** (Bernoulli, Multinomial, Gaussian).  
- Compare performance using metrics like **Precision, Recall, and F1-score**.  

---

## 🧩 Project Overview  

We built text classification models by:  
- Preprocessing text (tokenization, stopword removal, stemming/lemmatization).  
- Converting text into vectorized format using **TF-IDF**.  
- Training Naive Bayes classifiers (**Bernoulli, Multinomial, Gaussian**).  
- Evaluating using **Precision, Recall, F1-score**.  

---

## 🧾 Data Understanding  

- Dataset: Collection of text samples labeled by category (e.g., spam/ham).  
- Features: Preprocessed text tokens converted into vectors.  
- Target: **Text category/class**.  

---

## 🧼 Data Preparation  

- Tokenized sentences into words.  
- Removed stopwords and applied stemming/lemmatization.  
- Used **TF-IDF** to represent text numerically.  
- Prepared training and testing splits for evaluation.  

---

## 🤖 Modeling  

### 🔹 Bernoulli Naive Bayes  
- Works well with binary features (word present/absent).  
- Achieved **99% precision**.  

### 🔹 Multinomial Naive Bayes  
- Suitable for word frequency counts (TF-IDF).  
- Achieved **99% precision**.  

### 🔹 Gaussian Naive Bayes  
- Assumes continuous features.  
- Performed poorly with text data → **48% precision**.  

---

## 📊 Results & Comparisons  

| Model                  | Precision | Recall | F1-Score | Remarks |  
|-------------------------|-----------|--------|----------|---------|  
| Bernoulli Naive Bayes   | 99%       | High   | High     | Best for binary text features |  
| Multinomial Naive Bayes | 99%       | High   | High     | Best for frequency-based text |  
| Gaussian Naive Bayes    | 48%       | Low    | Low      | Not suitable for text data |  

---

## 📍 Insights Derived  

1. **Bernoulli and Multinomial Naive Bayes** both achieved excellent results (**99% precision**).  
2. **Gaussian Naive Bayes** underperformed, confirming it is not ideal for sparse text vectors.  
3. Feature representation (TF-IDF) greatly influenced performance.  

---

## ⚠️ Challenges Faced  

- Choosing the right vectorization technique for text.  
- Handling imbalanced dataset (if one class dominated).  
- Poor generalization of Gaussian Naive Bayes in NLP tasks.  

---

## 🚀 Future Scope  

- Experiment with advanced models (Logistic Regression, SVM, Deep Learning).  
- Use word embeddings (Word2Vec, GloVe, BERT) instead of TF-IDF.  
- Apply to larger and more diverse datasets.  
- Deploy model as an API for real-time text classification.  

---

## ✅ Final Outcome  

- **Bernoulli Naive Bayes** and **Multinomial Naive Bayes** achieved **99% precision**, proving effective for text classification.  
- **Gaussian Naive Bayes** was unsuitable for text-based data.  
- The project highlights the importance of model selection and feature representation in NLP tasks.  

---

📌 Tools Used: **Python, NLTK, scikit-learn, pandas**  

