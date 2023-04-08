# IS450 Text Mining and Language Processing Project: Detecting Suicide Ideation on Reddit
### Team 3

This repository contains all the code that was used to build our models, including pre-processing, training, and evaluation scripts.

## Project Overview
The World Health Organization estimates almost 800,000 people die from suicide attempts every year. A multitude of reasons such as burnout from work, suffering from chronic mental illnesses can trigger suicide ideations, that manifest into suicide attempts when ideations are left uncared. Our group aims to build a model that can detect suicide ideations on social media accurately for closer cooperation between and monitoring by mental health agencies, suicide prevention agencies and social media companies. These ideations, which would otherwise likely be glossed over, can be timely  flagged out before a suicide attempt or worst, a completed suicide manifest. 

The two NLP tasks that the team is focusing on are:
- Classificiation Model for Suicide Detection
  - This task involves building a classification model that will be able to automatically identify whether a given text contains indication of suicidal ideation. In order to identify the best model, we built three different models - Naive Bayes, Logistic Regression and Support Vector Machine and we will be evaluating the performance of the models before deciding on the best model.
- Sentiment Analysis using NRCLex and VADER
  - This task involves analyzing the sentiments of text data using lexicon-based sentiment analysis tools like NRCLex and VADER. The sentiment scores are then used as features in our classification model.
