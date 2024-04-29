# Sentiment Analysis on Twitter Data
### Overview
This project aims to perform sentiment analysis on Twitter data using Convolutional Neural Networks (CNNs). Sentiment analysis, also known as opinion mining, involves determining the sentiment expressed in a piece of text, whether it's positive, negative, or neutral. By analyzing tweets, we aim to understand the sentiments expressed by users on various topics and events.

### Dataset
The dataset used for this project is the Sentiment140 dataset, which consists of 1.6 million tweets labeled with sentiment polarity. The dataset contains tweets collected from Twitter and annotated with sentiment labels ranging from 0 to 4, representing negative, neutral, and positive sentiments. Each tweet is associated with metadata such as the timestamp, user ID, and tweet text.
The dataset can be downloaded from Kaggle in this link :https://www.kaggle.com/datasets/kazanova/sentiment140/data.

### Approach
##### Data Preprocessing: 
Clean the tweet text by removing noise, such as URLs, special characters, and stopwords. Tokenize the text and perform stemming or lemmatization.
##### Model Training:
Implement CNN models for sentiment analysis using TensorFlow/Keras. Experiment with different architectures, hyperparameters, and training strategies to optimize performance.
##### Model Evaluation:
Evaluate the trained models on a separate test dataset to assess their accuracy and performance metrics. Fine-tune the models based on evaluation results.
