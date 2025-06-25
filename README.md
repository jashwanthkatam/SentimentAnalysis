## Sentiment Analysis 

This project involves building a machine learning model to perform sentiment analysis on textual data,
aiming to determine the emotional tone (positive, negative, or neutral) behind a body of text. 
The core objective is to extract meaningful insights from text data, commonly applied in areas
like product reviews, social media analysis, and customer feedback systems.

## Context
This dataset consists of reviews of fine foods from amazon.
The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. 
Reviews include product and user information, ratings, and a plain text review. 
It also includes reviews from all other Amazon categories.

## Contents
Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite
database.sqlite: Contains the table 'Reviews'

## Data includes:

Reviews from Oct 1999 - Oct 2012
568,454 reviews
256,059 users
74,258 products
260 users with > 50 reviews

-> kaggle dataset (https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## Data Collection:
Gathered textual datasets from sources like Twitter,
IMDB reviews, or Amazon product reviews.

## Data Preprocessing: 
Cleaned and normalized data using NLP techniques such as tokenization,
stop-word removal, stemming, and lemmatization.

## Feature Extraction: 
Utilized techniques like TF-IDF, Bag of Words,
or Word Embeddings (e.g., Word2Vec, GloVe) to convert text into numerical vectors.

## Acknowledgements
See this SQLite query for a quick sample of the dataset.

If you publish articles based on this dataset, please cite the following paper:

J. McAuley and J. Leskovec. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013.

## Tools & Technologies:

 -> Programming Languages: Python

 -> Libraries/Frameworks: NLTK, spaCy, Scikit-learn, TensorFlow/Keras, Pandas, Matplotlib, Seaborn

 -> Deployment (optional): Flask or Streamlit for creating a simple web interface

## kaggle notebook:
https://www.kaggle.com/code/jashwanthreddykatam/sentimentanalysis
