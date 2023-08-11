# Sentiment_Analysis Using Natural Language Processing

This repository contains a comprehensive analysis of sentiment in text data using Natural Language Processing (NLP) techniques. The project aims to perform sentiment classification on textual data and gain insights from the sentiment distribution, word usage, and common phrases in different sentiment categories.

## Introduction

The primary objective of this project is to understand and analyze sentiment patterns in textual data. The analysis involves preprocessing the text data, performing sentiment classification using machine learning models, and exploring insights from the sentiment distribution, word usage, and common phrases.

## Data

The dataset used in this analysis includes text data with associated sentiments, sources, timestamps, user IDs, locations, and confidence scores.

## Analysis Steps

1. **Data Preprocessing**: The text data is loaded and preprocessed. This includes handling null values, duplicates, and transforming text to lowercase.

2. **Sentiment Analysis**: Sentiment analysis involves classifying text data into different sentiment categories, such as positive and negative. Various NLP techniques are applied, including TF-IDF vectorization, preprocessing (lowercasing, punctuation removal, stopword removal, stemming), and transformation.

3. **Exploratory Data Analysis (EDA)**: The analysis explores the sentiment distribution, sentiment distribution by source, location, confidence score, month, day, and hour. Additionally, KDE plots are used to visualize the distribution of total words and total characters.

4. **WordCloud Visualization**: WordClouds are generated to visualize the most common words associated with negative and positive sentiments.

5. **Common Words Analysis**: The most common words are counted and visualized for both negative and positive sentiments.

6. **Model Training and Evaluation**: Naive Bayes and Random Forest models are trained and evaluated for sentiment classification. Metrics such as accuracy, precision, recall, and confusion matrix are used for evaluation.

## Results

The analysis provides insights into sentiment distribution, common words associated with different sentiments, and the performance of machine learning models for sentiment classification.

## Conclusion

Sentiment analysis using NLP techniques offers valuable insights into text data. By understanding sentiment patterns, organizations can gain a deeper understanding of user opinions and feedback.

