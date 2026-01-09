# amazon-sentiment-analysis
End-to-end sentiment analysis on Amazon product reviews using NLP and machine learning. Performed text preprocessing, TF-IDF feature extraction, and trained Logistic Regression to classify reviews as positive, neutral, or negative. Evaluated with accuracy, F1-score, and confusion matrix, and deployed as a Streamlit web app for real-time prediction.
# Amazon Product Review Sentiment Analysis

## 📌 Project Overview
This project builds an end-to-end sentiment analysis system to classify Amazon product reviews into **Positive**, **Neutral**, or **Negative** sentiments using Natural Language Processing (NLP) and Machine Learning techniques. The solution helps businesses understand customer feedback at scale.

---

## 🎯 Objectives
- Clean and preprocess raw customer review text
- Convert text data into numerical features using TF-IDF
- Train and evaluate machine learning models
- Deploy the trained model as a web application

---

## 🧠 Dataset
- **Source:** Amazon Fine Food Reviews Dataset
- **Key Columns Used:**
  - `Text` → Review content
  - `Score` → Rating (1–5)

### Sentiment Mapping
| Rating | Sentiment |
|------|----------|
| 4–5 | Positive |
| 3 | Neutral |
| 1–2 | Negative |

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- NLTK (text preprocessing)  
- Scikit-learn  
- TF-IDF Vectorizer  
- Logistic Regression  
- Streamlit  

---

## 🔄 Project Workflow
1. Data loading and exploration  
2. Text cleaning and preprocessing  
3. Sentiment label creation  
4. Feature extraction using TF-IDF  
5. Model training (Naive Bayes & Logistic Regression)  
6. Model evaluation and comparison  
7. Deployment using Streamlit  

---

## 📊 Model Performance
- **Naive Bayes Accuracy:** ~82%
- **Logistic Regression Accuracy:** ~87%
- Logistic Regression was selected as the final model based on superior performance.

---

#
