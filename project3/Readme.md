# 🩺 Medical Text Classification Project
This project demonstrates the implementation of different machine learning models (Logistic Regression, Decision Tree, Random Forest, and XGBoost) for **classifying medical transcripts** into four categories.  
The goal is to analyze model performance on training, validation, and test datasets, and to compare two text representations: **Binary Bag-of-Words (BBoW)** and **Frequency Bag-of-Words (FBoW)**.

---

🔹 **Project Overview**
- Load datasets (train, valid, test)  
- Preprocess text (lowercasing, punctuation removal, stopword removal, lemmatization)  
- Build vocabulary (top 10,000 most frequent words)  
- Implement vectorization methods:  
  - **BBoW (Binary Bag-of-Words)**  
  - **FBoW (Frequency Bag-of-Words)**  
- Train four models: Logistic Regression, Decision Tree, Random Forest, XGBoost  
- Compute **Macro F1-score** to compare training, validation, and test performance  
- Visualize hyperparameter effects on underfitting and overfitting  

---

🛠️ **Technologies Used**
- Python  
- NumPy  
- Pandas  
- scikit-learn  
- XGBoost  
- NLTK  
- Matplotlib  

---

📂 **Project Structure**
- `Medical_Text_Classification.ipynb` → Jupyter Notebook with implementation  
- `train.csv` → Training dataset  
- `valid.csv` → Validation dataset  
- `test.csv` → Test dataset  
- `vocab.txt` → Vocabulary file (word, ID, frequency)  

---

📊 **Results**

🔹 **Binary Bag-of-Words (BBoW)**
- Logistic Regression → Train F1 ≈ 0.82, Test F1 ≈ 0.50  
- Decision Tree → Train F1 ≈ 0.82, Test F1 ≈ 0.47  
- Random Forest → Train F1 ≈ 0.82, Test F1 ≈ 0.27  
- XGBoost → Train F1 ≈ 0.82, Test F1 ≈ 0.57  

👉 **Observation:** All models achieve similar performance on training (~0.82) but drop on test. XGBoost generalizes best, Random Forest performs worst.  

🔹 **Frequency Bag-of-Words (FBoW)**
- Expected to perform better because frequency information is preserved.  
- Captures richer semantics compared to BBoW.  

---

🎯 **Learning Objectives**
- Understand text preprocessing for NLP tasks  
- Learn how to build a vocabulary and vectorize text data (BBoW vs FBoW)  
- Compare classical machine learning models for text classification  
- Analyze underfitting and overfitting via hyperparameter tuning  
- Practice evaluating models using **Macro F1-score**  

---
