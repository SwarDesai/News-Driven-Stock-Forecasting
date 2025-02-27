# News-Driven Stock Forecasting

## Overview:
This project aims to predict stock movement (up or down) based on the top 25 news headlines about a company. Using machine learning classifiers, the model analyzes news sentiment and determines its impact on stock prices.

## Features:
  * Text Preprocessing: Cleans and processes news headlines for better feature extraction.
  * TF-IDF Vectorization: Converts text into numerical feature vectors for model training.
  * Multiple Classifiers: Implements Logistic Regression, Random Forest, and Naïve Bayes for classification.
  * Stock Movement Prediction: Classifies whether the stock price will rise or fall based on the news.

## Methodology:
1. Data Preprocessing:
  * Tokenization, stopword removal, stemming/lemmatization.
  * TF-IDF Vectorization to convert news headlines into numerical features.
2. Model Training:
  * Trains Logistic Regression, Random Forest, and Naïve Bayes classifiers.
  * Evaluates models using accuracy, precision, recall, and F1-score.
3. Stock Prediction:
  * Uses trained models to predict whether stock prices will increase or decrease based on the latest news.

## Dependencies:
  * Python 3.x
  * Scikit-learn
  * Pandas
  * NumPy
  * NLTK
  * Matplotlib

## Results:
  * Achieved highest accuracy of 84.92% using Logistic Regression.
  * Precision: 0.78, Recall: 0.99, demonstrating strong predictive capability.
  * Identified key influential words affecting stock price movement.

## Future Improvements:
  * Implement deep learning models (LSTMs, Transformers) for enhanced accuracy.
  * Use sentiment analysis techniques to improve feature extraction.
  * Integrate real-time news streams for live stock predictions.

