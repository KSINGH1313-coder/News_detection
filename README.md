# 📰 Real and Fake News Detection System

The **Fake News Detection System** is a machine learning web application that classifies whether a given news article is **real** or **fake**. It leverages Natural Language Processing (NLP) techniques to analyze and classify news content, helping users, journalists, and platforms fight misinformation.

## ✅ Features

- Classifies news articles as **Real** or **Fake**
- Uses NLP and ML models (e.g., Logistic Regression, Naive Bayes, XGBoost)
- Clean and interactive web interface built using Flask
- Accepts user input as raw news text or headline
- Real-time prediction with high accuracy

## 🧠 ML/NLP Model Overview

The model uses the following pipeline:

- Text Preprocessing: Tokenization, Lowercasing, Stopword Removal
- Vectorization: **TF-IDF**
- Classification: **Logistic Regression** (best-performing), with optional **PassiveAggressive**, **XGBoost**, etc.

Dataset used: **Fake and Real News Dataset** from Kaggle.

## 📊 Model Accuracy

| Model                | Accuracy  |
|---------------------|-----------|
| Logistic Regression | ~96%      |
| XGBoost Classifier  | ~95%      |
| Naive Bayes         | ~92%      |
| PassiveAggressive   | ~94%      |

## 🖥️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **ML/NLP**: Scikit-learn, Pandas, NLTK, TF-IDF
- **Deployment**: Localhost / Render / Heroku (optional)

