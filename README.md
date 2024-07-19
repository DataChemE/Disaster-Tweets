# Disaster Tweets Prediction using Neural Networks

## Project Overview

This project tackles the Kaggle Disaster Tweets challenge, where the goal is to predict whether a tweet is about a real disaster or not. I have employed various Neural Network architectures to classify tweets, with a focus on LSTM (Long Short-Term Memory) models.

## Dataset

The dataset consists of 10,000 tweets that have been hand-classified. Key features include:

- id: A unique identifier for each tweet
- text: The text of the tweet
- location: The location the tweet was sent from (may be blank)
- keyword: A particular keyword from the tweet (may be blank)
- target: 1 if the tweet is about a real disaster, 0 otherwise

## Approach

My approach involves several steps:

1. Data Preprocessing: Cleaning the text data, handling missing values, and tokenization.
2. Word Embedding: Utilizing pre-trained GloVe embeddings.
3. Model Architecture: Implementing LSTM-based models.
4. Hyperparameter Tuning: Using Keras Tuner to optimize model parameters.
5. Model Evaluation: Employing cross-validation and various metrics.

## Models

I have experimented with several model architectures, including:

- Simple LSTM
- Bidirectional LSTM
- GRU Model 
- Tuned Model (using Keras Tuner)

## Files

- `*_submission.csv`: submission file for Kaggle for each model

## Future Work

- Experiment with transformer-based models like BERT
- Incorporate more features from the tweet metadata
- Ensemble different model architectures

## Dependencies

- TensorFlow
- Keras
- Scikit-learn
- Pandas
- NumPy