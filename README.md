# NLP-ASSIGNMENT

# IMDB Movie Review Sentiment Analysis and Topic Modeling

This project analyzes IMDB movie reviews using NLP techniques, including sentiment analysis, topic modeling, and genre extraction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
  - [1. Data Loading](#1-data-loading)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Data Preprocessing](#3-data-preprocessing)
  - [4. Sentiment Analysis](#4-sentiment-analysis)
    - [Naive Bayes vs Logistic Regression](#naive-bayes-vs-logistic-regression)
  - [5. Topic Modeling](#5-topic-modeling)
  - [6. Genre Extraction](#6-genre-extraction)
  - [7. Sentiment by Genre](#7-sentiment-by-genre)
- [Visualization](#visualization)
- [Results](#results)

## Introduction
This project applies machine learning techniques to classify movie reviews into positive and negative sentiments, identify topics in reviews, and analyze sentiment distribution across genres.

## Dataset
IMDB dataset of 50,000 labeled movie reviews.
```python
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
```

## Usage
1. Load the dataset and run the notebook to perform sentiment analysis, topic modeling, and genre extraction.

## Project Workflow

### 1. Data Loading
Load dataset using Pandas:
```python
df = pd.read_csv('/content/IMDB Dataset.csv')
```

### 2. Exploratory Data Analysis (EDA)
Perform data analysis to explore sentiment distribution and review details.

### 3. Data Preprocessing
Clean and preprocess data using techniques like tokenization, stopword removal, and lemmatization.

### 4. Sentiment Analysis

#### Naive Bayes vs Logistic Regression
Compare the accuracy of Naive Bayes and Logistic Regression models for sentiment classification:

### 5. Topic Modeling
Use Latent Dirichlet Allocation (LDA) to extract topics from reviews.

### 6. Genre Extraction
Genres are identified based on keyword matches in the reviews.

### 7. Sentiment by Genre
Analyze sentiment for each genre, classifying reviews as "Best," "Neutral," or "Worst."

## Visualization
Generate word clouds, topic distributions, and sentiment heatmaps.

## Results
The project compares sentiment analysis models, evaluates topic coherence, and provides insights on sentiment distribution across genres.

## File Link
```python
https://github.com/Mahrukh-Baig/NLP-ASSIGNMENT/blob/main/NLP_ASSIGNMENT_1%20(1).ipynb
```
