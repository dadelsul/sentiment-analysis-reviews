# Sentiment Analysis on Amazon Alexa Reviews

## 📌 Overview
This project applies Natural Language Processing (NLP) to classify **Amazon Alexa product reviews** into positive or negative sentiments.  
It combines **traditional Machine Learning models** with **Deep Learning (BiLSTM)** to improve sentiment detection and provide accurate predictions.

## ⚙️ Features
- Preprocessing: cleaning text, handling emojis, removing stopwords, tokenization, and lemmatization.  
- Handling imbalanced dataset with oversampling and undersampling techniques.  
- Implemented models:  
  - **Support Vector Machine (SVM)**  
  - **Random Forest**  
  - **Logistic Regression**  
  - **Naïve Bayes**  
  - **Bidirectional LSTM (BiLSTM)**  

## 📊 Results
- **Random Forest** → Accuracy: 93%, F1-score: 0.93, AUC: 0.96  
- **BiLSTM** → Accuracy: 98%, strong performance in handling sequential and emoji-based text.
