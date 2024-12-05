#DA 231o Data Engineering at scale

## Project Title
Sentiment Analysis of Yelp Restaurant Reviews

## Team Members
- Atharva Hemant Malandkar
- Barath Karthi R K
- Harikrishnan C
- Shunmuga Janani A

## Problem Statement
The Yelp Open Dataset offers a comprehensive set of data related to businesses, user reviews, and other attributes associated with restaurants. Analyzing restaurant reviews can provide valuable insights into customer sentiment, business performance, and operational areas requiring improvement.
The problem at hand is to automatically classify the sentiment of Yelp restaurant reviews. Specifically, the goal is to determine whether a review expresses a positive, negative, or neutral sentiment based on the content of the review. This classification helps restaurant owners, customers, and other stakeholders to gain quick insights into the overall sentiment surrounding a particular restaurant.

## Dataset Summary
The Yelp dataset is an open-source dataset available on the Yelp website. This dataset has no restrictions as long as the usage is limited to academic purposes. The dataset has a collection of reviews that is available in json format.
Data Set: https://www.yelp.com/dataset

## Dataset Files
Download the dataset from the Yelp UI and upload the json files - Reviews & Business in MongoDB using Atlas.

## Notebooks
The complete project is divided into below steps.
The input , output  and description is provided for all the notebooks.
Please make sure the notebooks are run sequentially .

| **Notebook**                  | **Discription**     |
| ------------------- | ------------------ |
| [Archival Notebook](https://github.com/JananiAbhinav/YelpReviewsSentimentAnalysis/tree/main/Archival)   | Has the archival logic notebook to be executed in ADF pipeline on a monthly basis to archive the MongoDB data to cold tier |
| [Data Warehousing](https://github.com/JananiAbhinav/YelpReviewsSentimentAnalysis/tree/main/Data%20Warehousing)   | Has notebooks to transform the data & maintain a proper data warehouse architecture.  |
| [Kafka Streaming ](https://github.com/JananiAbhinav/YelpReviewsSentimentAnalysis/tree/main/Kafka%20Streaming)   |Has the Kafka Producer & consumer setup notebooks |
| [ML Model notebook](https://github.com/JananiAbhinav/YelpReviewsSentimentAnalysis/tree/main/ML%20model%20notebook)  | Sentiment analysis of review data through ML models & NLP techniques for vectorization|

## Models implemented:​
Logistic Regression
Naive Bayes
MultiLayerPerceptron Classifier - Deep Learning

## Future Enhancement
Aspect-Based Sentiment Analysis:
Identify sentiments for specific aspects like service, food, or ambience.

Transfer Learning:​
- Transfer learning from pre-trained models (e.g., BERT,GPTs for natural language processing) could be used to improve the handling of textual data better than word embeddings.
