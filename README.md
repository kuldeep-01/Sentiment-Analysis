# Sentiment Analysis Using Logistic Regression

## Overview

This project implements a **sentiment analysis model** using **logistic regression**. It processes a dataset of tweets, extracts features using the **Bag-of-Words** method, and trains a classifier to predict whether a tweet has a **positive** or **negative** sentiment.

## Features

- **Data Preprocessing**: Cleans tweets by removing punctuation, URLs, and stopwords.
- **Feature Extraction**: Uses a Bag-of-Words approach to convert text into numerical vectors.
- **Logistic Regression Implementation**: Implements gradient descent to optimize model parameters.
- **Prediction**: Classifies new user-input sentences as **positive** or **negative**.
- **Model Evaluation**: Computes accuracy on the training dataset.

## Requirements

Make sure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib nltk
