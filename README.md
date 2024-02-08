# Sentiment analysis on movie reviews
## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Results](#Result/Findings)


## Project Overview

This project is a sentiment analysis model that predicts the sentiment of movie reviews. The goal of this project is to classify a movie review as either positive or negative based on the text of the review.

## Project Description

In the world of movie marketing, audience sentiment can often be the key difference between a box office hit or a flop. Understanding audience sentiment towards a movie based on their reviews can provide valuable insights for movie makers and marketers. This project aims to leverage the power of Natural Language Processing (NLP) and Machine Learning to predict the sentiment of a movie review.

The dataset used for this project is sourced from Kaggle and contains a large number of movie reviews. Each review in the dataset is labeled as either 'positive' or 'negative', representing the sentiment of the reviewer.

The model built in this project can be a valuable tool for movie makers and marketers, enabling them to gauge audience sentiment and adjust their strategies accordingly.

Stay tuned for more updates on the model's performance and the techniques used in building it!

Please note that this is a work in progress and any contributions or suggestions are welcome.

## Data Sources
The main dataset used in this project were provided during kaggle competition,the dataset conatined :
* movies.csv - the file with metadata on movies.
* train.csv - the training set containing the review sentiment   along with other features.
* test.csv - the test set, has review features, but no sentiment column, since it is the target.

- [Link to the dataset](https://drive.google.com/file/d/1zfGniGAI4j9JVwd463pubJw1PwNMfxbn/view?usp=sharing)



## Result/Findings

- Top critic reviews affected sentiment prediction in case of alot of movie reviews.

- Sarcastic reviews labeled as positive due to 2:1 imbalance in training dataset.
(will update results after tackling these complexities)

- Two models, Logistic Regression and Linear SVM, were trained for sentiment prediction.

Logistic Regression achieved an F1 score of 0.83.
Linear SVM performed slightly better with an F1 score of 0.84.

