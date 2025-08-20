# 📧 SMS Spam Detection using Naive Bayes 

This project implements a **machine learning model** to classify SMS messages as **Spam** or **Ham** (Not Spam).  
We use the **Naïve Bayes algorithm** along with **text preprocessing techniques** and **feature extraction** (CountVectorizer & TF-IDF).  

---

## 🚀 Project Workflow  

### 1️⃣ Dataset  
- Source: `spam.csv` (UCI SMS Spam Collection dataset)  
- Size: ~5,500 SMS messages  
- Labels:  
  - `ham` → Not spam  
  - `spam` → Spam  

---

## Modules Covered
  - Data Cleaning
  - Text Preprocessing
  - Feature Extraction
  - Model Training
  - Model Evaluation

---

## 📊 Results  

- Naive Bayes + TF-IDF achieved **97.9% accuracy**  
- Rare spam words get **higher weight** in TF-IDF, improving classification  
