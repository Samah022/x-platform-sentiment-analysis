# Sentiment Analysis on 𝕏 (Twitter) Platform 📊

## Overview 🌟

This project focuses on performing sentiment analysis on tweets from the 𝕏 (Twitter) platform. The primary objective is to preprocess the textual data, apply various machine learning algorithms, and evaluate their performance in predicting the sentiment of the tweets.

## Key Components 🔑

### 1. Data Preprocessing 🧹
- **Data Loading**: Tweets are loaded from a CSV file.
- **Text Cleaning**: Includes lowercasing, removing URLs, special characters, and numbers.
- **Tokenization**: Splitting text into tokens.
- **Stop Words Removal and Stemming**: Using NLTK to remove stop words and stem tokens.
- **Output**: Cleaned tweets are saved to a new CSV file.

### 2. Sentiment Labeling 🏷️
- **Sentiment Assignment**: Tweets are labeled as positive, negative, or neutral and mapped to numerical values (1, -1, 0).
- **Output**: Labeled data is saved to another CSV file.

### 3. Machine Learning Algorithms 🤖
- **Model Training**: Various ML algorithms are trained, including:
  - Term Frequency-Inverse Document Frequency (TF-IDF)
  - Support Vector Machines (SVM)
  - Random Forest (RF)
  - K-Nearest Neighbors (KNN)
  - VADER
  - Naive Bayes (NB)
  - AdaBoost
  - Maximum Entropy

### 4. Evaluation 📈
  - Models are evaluated based on accuracy and other metrics.

## Results 🏆
The project demonstrates an effective pipeline for sentiment analysis on 𝕏 (Twitter) data, with the Maximum Entropy model achieving an accuracy of 0.807.

## Authors ✍️
- Sana Shamma
- Salwa Shamma
- Samah Shamma
