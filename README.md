# NLP Sentiment Classification

This is a personal NLP project based on the IMDB movie review dataset. The aim is to classify movie reviews as positive or negative using different machine learning models.

I started this project while learning about natural language processing and wanted to try applying what I had learnt to a real dataset.

**Dataset:** [IMDB Dataset of 50K Movie Reviews (Kaggle)](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## What I Did

The project mainly consists of three parts:

**1. Text Preprocessing**

I used Python and NLTK to clean the reviews, remove stopwords, and apply stemming and lemmatisation. I also included some basic word frequency analysis.

**2. Feature Extraction**

Since machine learning models cannot directly process raw text, I used Bag-of-Words and TF-IDF to convert the reviews into numerical features. I also experimented with PCA for dimensionality reduction.

**3. Model Training**

I implemented three classification models:

- Random Forest
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

I used GridSearchCV to search for suitable hyperparameters and evaluated the models using precision, recall and F1-score.

## Code

The project contains two main Python files:

- `Maincode.py` – the main script for running the analysis and training the models.
- `Package_IMDB.py` – contains the functions for text preprocessing, feature extraction and model training.

The code uses Python with libraries including Pandas, NLTK and Scikit-learn.

## About This Project

This was one of my earlier machine learning projects. At the time, I was particularly interested in NLP and wanted to understand how a complete text classification process worked, from preparing the data to training and evaluating models.

I have since revisited the code and uploaded it to GitHub as a record of what I learnt.
