# Sentiment-Analysis-from-Financial-News
This repository contains the code for detecting sentiments from financial news articles. Three sentiments: positive, negative and neutral can be detected by the machine learning and deep learning models.

## Introduction
Financial News is closely monitored by all parties involved in the stock market, directly or indirectly. Sentiment analysis of news, can aid in market forecasting.  If there is a positive mood about a company, for example, the price of its products or shares will continue to rise or remain constant. Financial Sentiment Indicators are critical in predicting how the finance sector will perform in the future.

## Methodology
### Dataset
The dataset for the project is taken from the paper “Good debt or bad debt: Detecting semantic orientations in economic texts”. It consists of 4837 news headlines. Out of the 4857 news headlines, 59% are for neutral sentiment, 28% are for the positive sentiment and 13% are for the negative sentiment.

### Preprocessing
The raw data needs to be pre-processed using different techniques like removing punctuations, correcting words, lemmatization, stop words removal and so on. This ensures that the data which is fed to the model is fit for training purposes.

### Feature Engineering
In this step, features are derived from the data using 2 approaches: using N-gram and TFIDF.

### Models
For implementation, machine learning and deep learning models are used. These models will be
trained on the features extracted in the previous step. Models like Decision Tree, Random Forest Classifier and GRU with word embeddings have been implemented.
