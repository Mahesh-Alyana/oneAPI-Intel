# Sentiment Analysis using LDA and SVR

This project aims to build a predictive model for sentiment analysis using social media data related to a particular brand or product. The model will analyze various features of the social media data, such as the latest news, resources, topic of the media resources, popularity on the social media, to determine consumer sentiment towards the brand or product.

## Problem Statement

The goal of this project is to develop a machine learning model that can predict consumer sentiment based on social media activity. To achieve this, we have used LDA (Latent Dirichlet Allocation) for topic modeling and feature extraction, and SVR (Support Vector Regression) for sentiment score prediction.

## Dataset

The dataset used for this project is provided in the "training_data.csv" file. The dataset consists of the following columns:

- IDLink: Unique ID for each record
- Title: Title of the news article
- Headline: Headline of the news article
- Source: Source of the news article
- Topic: Topic of the news article
- PublishDate: Date on which the news article was published
- Facebook: Number of Facebook shares for the news article
- GooglePlus: Number of Google+ shares for the news article
- LinkedIn: Number of LinkedIn shares for the news article
- SentimentTitle: Sentiment score (from -1 to 1) based on the title of the news article
- SentimentHeadline: Sentiment score (from -1 to 1) based on the headline of the news article

## Model Architecture

The model architecture consists of the following steps:

- Feature extraction using LDA to identify key topics and themes in the social media data.
- Sentiment score prediction using SVR based on the features extracted from LDA.

## Results

The results of the model has be generated for the test data in "submission.csv" file.

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- gensim
- nltk

## Usage

Run all the cells of oneAPI.ipynb to see output

This will preprocess the data, extract features using LDA, train the SVR model, and generate submission file on the test set.

## Conclusion

In conclusion, this project demonstrates how LDA and SVR can be used to build a robust sentiment analysis model that can accurately predict consumer sentiment based on social media activity. The model can be used by marketers and businesses to inform their marketing strategies and improve their sales by tailoring their messaging and advertising to appeal to their target audience.
