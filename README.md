# Fake-News-Detection-NLP
Fake News Detection model using text preprocessing, TF-IDF and classical ML techniques.

## Overview
Fake news has become a major challenge in the digital age, spreading misinformation rapidly through online platforms. This project focuses on building an AI/ML-based Natural Language Processing (NLP) system to automatically classify news articles as Fake or Real based on their textual content.

The model leverages text preprocessing techniques, TF-IDF feature extraction, and machine learning algorithms to achieve high classification accuracy.

## Objectives
- To understand and apply NLP techniques on real-world text data
- To build a machine learning classifier for fake news detection
- To compare different ML models and evaluate their performance
- To gain hands-on experience with AI/ML pipelines

## Dataset
- Source: Kaggle – Fake and Real News Dataset
- Size: ~40,000 news articles
- Labels: FAKE, REAL
- Features: Title, Text, Subject, Date

## Methodology

### 1. Data Preprocessing (NLP)

- Text cleaning (lowercasing, punctuation & URL removal)
- Stopword removal
- Lemmatization
- Combining title and article text

### 2. Feature Extraction

#### TF-IDF Vectorization
- Highlights important words
- Reduces impact of frequently occurring terms

### 3. Machine Learning Models

- Logistic Regression
- Multinomial Naive Bayes

### 4. Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix

### Results

- Achieved ~98% accuracy using Logistic Regression with TF-IDF features
- Logistic Regression performed better than Naive Bayes in terms of F1-score
- The model effectively distinguishes fake and real news based on textual patterns

### Technologies Used

- Programming Language: Python

#### Libraries:
- Pandas, NumPy
- NLTK / spaCy
- Scikit-learn
- Matplotlib / Seaborn

#### Concepts: 
AI, Machine Learning, NLP, Text Classification

### Future Enhancements

- Implement deep learning models like LSTM or BERT
- Deploy the model as a web application using Streamlit
- Add real-time news scraping and prediction

### Conclusion

This project demonstrates the practical application of AI/ML and NLP techniques in solving real-world problems like misinformation detection. It provides a strong foundation in text preprocessing, feature engineering, and machine learning model evaluation.