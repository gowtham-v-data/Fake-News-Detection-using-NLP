# 📰 Fake News Detection using NLP

## 📌 Overview
This project detects whether a news article is **Real or Fake** using Natural Language Processing (NLP) and Machine Learning techniques. It processes text data, extracts features, and classifies news content accurately.

---

## 🎯 Objectives
- Detect fake news using NLP techniques  
- Convert text data into numerical form  
- Train a machine learning model for classification  
- Understand real-world NLP applications  

---

## 🗂️ Dataset
Dataset used from Kaggle:
- Fake.csv → Fake news  
- True.csv → Real news  

---

## ⚙️ Tech Stack
- Python  
- NLTK  
- Scikit-learn  
- Gensim (Word2Vec)  
- Jupyter Notebook  

---

## 🔍 NLP Techniques Used
- Text Preprocessing (Cleaning, Lowercasing)  
- Tokenization  
- Stopword Removal  
- Lemmatization  
- Feature Extraction:
  - TF-IDF  
  - Word2Vec  

---

## 🧠 Model Used
- Logistic Regression  

---

## 🚀 Project Workflow
1. Load dataset  
2. Clean and preprocess text  
3. Tokenize and remove stopwords  
4. Apply lemmatization  
5. Convert text using TF-IDF / Word2Vec  
6. Split data into training and testing  
7. Train the model  
8. Evaluate performance  
9. Predict new input  

---

## 📊 Results
- Achieved good accuracy  
- Word2Vec improves semantic understanding  
- Model performs well on unseen data  

---

## 🧪 Example
```python
predict_news("Government announces new policy to improve economy")
