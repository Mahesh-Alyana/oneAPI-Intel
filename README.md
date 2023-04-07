# Sentiment Analysis using LDA and SVR
This project(prototype) was devloped as a solution for the Intel One API challenge-2K23.

This project aims to build a predictive model for sentiment analysis using social media data related to a particular brand or product. The model will analyze various features of the social media data, such as the latest news, resources, topic of the media resources, popularity on the social media, to determine consumer sentiment towards the brand or product.

## Problem Statement

The goal of this project is to develop a machine learning model that can predict consumer sentiment based on social media activity. 
To achieve this, we have used LDA (Latent Dirichlet Allocation) for topic modeling and feature extraction, and SVR (Support Vector Regression) for sentiment score prediction.

## Dataset

The dataset used for this project is provided in the "training_data.csv" file.
#Metadata

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
# Note this is only a Prototype version, we can develop the whole model in the coming month


- Feature extraction & then used LDA to classify datapoints into respective topics and themes in the social media data.
- It is notiable that  
- Sentiment score prediction using SVR based on the features extracted from LDA.

## Results

The results of the model has be generated for the test data in "submission.csv" file.
These are the results obtained by using the prototype model.

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- gensim
- nltk

## Usage

Run all the cells of oneAPI.ipynb to see output(this Ipynb file was run on the Intel DevCloud and using the Scikit Learn extentsion by Intel, our team admits that  results obtained by using the Intel Extension were so fast that, the ML algorithm felt like it was a normal graph algorithm on our local basic programming laptop).

This will preprocess the data, extract features using LDA, train the SVR model, and generate submission file on the test set.

## Conclusion

In conclusion, this project demonstrates how LDA and SVR can be used to build a robust sentiment analysis model that can accurately predict consumer sentiment based on social media activity. The model can be used by marketers and businesses to inform their marketing strategies and improve their sales by tailoring their messaging and advertising to appeal to their target audience.
#Contact us at
-20211a6645@bvrit.ac.in
-20211a6604@bvrit.ac.in
-20211a6644@bvrit.ac.in
-20211a6616@bvrit.ac.in
-20211a6602@bvrit.ac.in
