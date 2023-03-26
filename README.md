# Sentiment Analysis on Movie Reviews Challenge

This repository contains the code and solution for the "Sentiment Analysis on Movie Reviews" challenge available on Kaggle.

## Problem Description

The challenge involves predicting the sentiment of movie reviews as either positive or negative. The dataset consists of 25,000 training samples and 25,000 testing samples, each of which is labeled with the corresponding sentiment.

## Approach

I used a combination of Natural Language Processing (NLP) techniques and machine learning algorithms to build our model. The approach involved the following steps:

1. Data pre-processing: Converting all the phrase in train data to lowercase, removing punctuations, stopwords, stemming and lemmatizing

2. Feature Extraction: I used a Bag of Words model to extract features from the pre-processed text data. This model creates a vocabulary of all unique words in the text corpus and then represents each document as a vector of word frequencies.

3. Model Training: I trained 4 machine learning algorithms, they are, Naive Bayes, Support Vector Machine, Desicion Tree and K-nearest Neighboure on the training data to predict the sentiment of the movie reviews. Furthermore I trained 1 deep learning algorithms, LSTM, on the training data to predict the sentiment of the movie reviews.

4. Model Evaluation: I evaluated the performance of our models using various metrics such as accuracy, precision, recall, and F1-score.

## Results

Our best performing model was the LSTM, which achieved an accuracy of 66.03% on the testing data. 


## License

This project is licensed under the MIT License. Feel free to use, distribute, and modify the code for your own purposes.
