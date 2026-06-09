# Fake News Detection using Machine Learning

## Overview

This project detects whether a news article is Real or Fake using Natural Language Processing (NLP) and Machine Learning techniques. The model is trained on a labeled news dataset and uses TF-IDF vectorization with Logistic Regression for classification.

## Features

* Text preprocessing and cleaning
* Stopword removal and stemming
* TF-IDF feature extraction
* Logistic Regression classifier
* News classification as Real or Fake
* Model performance evaluation using accuracy score

## Technologies Used

* Python
* NumPy
* Pandas
* NLTK
* Scikit-learn

## Dataset

The dataset used for this project is provided in compressed format (`train.zip`).

Extract the dataset before running the notebook.

## Project Workflow

1. Load and preprocess the dataset
2. Remove stopwords and perform stemming
3. Convert text into numerical features using TF-IDF
4. Split data into training and testing sets
5. Train the Logistic Regression model
6. Evaluate model performance
7. Predict whether a news article is Real or Fake

## Requirements

Install the required libraries:

pip install -r requirements.txt

## Results

The model achieved approximately 94% accuracy on the test dataset.

## Author

Sunil S
