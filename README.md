# APIs, NLP, and Classification
Team: Bird Jr., Gun (First Jobber)

---
## Corpus
The corpus we gathered in reddit which subreddit Civil Engineering and Acrhitecture for use develop our models.
### Data Dictionary
Features|Meaning|
---|---|
subreddit| subreddit category|
title| thread title in reddit| 

---
## Executive Summary

False constrcution Inc. is new start-up construction company. Company want to reduce human work loads and decided to use machine learning for assisting coordinators work. <br>
In early state of False construction Inc., Civil engineer and architects receive large work loads. They decided to hire a part-time data scientist to set up an actionable and explainable model to classify the work for civil engineers and architects. <br>
**Goal**
- Is model score higher than 53%? (baseline score) <br>

**Model Development**<br>
We have developed models by using Civil Engineer and Architecture corpus and used exploratory data analysis(EDA) for features selection, stop words for reduce features and accuracy score from models for selecting final model.<br>
Final model is Logistic Regression which fed by stop words removal and lemmatized words, model testing accuracy is 79% which higher than baseline score 26%.<br> 
**Summary**<br>
For summary we developed actionable and explainable Logistic Regrssion model. this model are developed for assisting coordinators work and reduce human work loads in False construction Inc., Futhermore this model might adapt for other work in the company such as classify the research of Civil Enginnering and Achitecture.

**Limitation**
For the future, it should be taken in consideration that our corpus might need documents that contanied more quailty and specific for training models and also another for consideration, other complex models such as Nerual Network, Bert might perform better in classify Cilvil Engineer and Architecture.