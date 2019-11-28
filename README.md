# Identify-the-Sentiments
Provided with tweet data to predict sentiment on electronic products of netizens.

## About Problem: Identify the Sentiments
Sentiment analysis is contextual mining of text which identifies and extracts subjective information in source material, and helping a business to understand the social sentiment of their brand, product or service while monitoring online conversations. Brands can use this data to measure the success of their products in an objective manner. In this challenge, you are provided with tweet data to predict sentiment on electronic products of netizens.

### Resources :-
- Get started with NLP and text classification with our latest offering  ‘Natural Language Processing (NLP) using Python’ course
- Refer this comprehensive guide that exhaustively covers text classification techniques using different libraries and its implementation in python.
- You can also refer this guide that covers multiple techniques including TF-IDF, Word2Vec etc. to tackle problems related to Sentiment Analysis.

## Problem Statement
Sentiment analysis remains one of the key problems that has seen extensive application of natural language processing. This time around, given the tweets from customers about various tech firms who manufacture and sell mobiles, computers, laptops, etc, the task is to identify if the tweets have a negative sentiment towards such companies or products.

 

## Evaluation Metric
The metric used for evaluating the performance of classification model would be weighted F1-Score.

 

## Public and Private Split
Note that the test data is further randomly divided into Public (35%) and Private (65%) data. Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.

### Data
- train.csv - For training the models, we provide a labelled dataset of 7920 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.

- test.csv - The test data file contains only tweet ids and the tweet text with each tweet in a new line.

- sample_submission.csv - The exact format for a valid submission

**Note :-** Most profane and vulgar terms in the tweets have been replaced with “$&@*#”. However, please note that the dataset still might contain text that may be considered profane, vulgar, or offensive.
