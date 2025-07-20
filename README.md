# IMDB Movie Reviews Sentiment Analysis

## Project Overview

This project performs sentiment analysis on the IMDB movie reviews dataset using Recurrent Neural Networks (RNN), specifically LSTM layers. The goal is to classify movie reviews as **positive** or **negative** based on the text content.

We explore different model architectures and hyperparameters, including embedding dimensions, LSTM units, dropout rates, optimizers, and batch sizes. Hyperparameter tuning is automated using **Keras Tuner** to find the best performing model.

---

## Dataset

- Contains 50,000 movie reviews labeled as **positive** or **negative**.
- Source: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Format: CSV file with columns `review` (text) and `sentiment` (label).


