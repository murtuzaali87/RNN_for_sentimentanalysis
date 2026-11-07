# RNN Sentiment Analysis

A machine learning project that classifies IMDB movie reviews as **Positive or Negative** using Natural Language Processing (NLP) and PyTorch.

## Project Overview

This project explores sentiment classification using the IMDB movie reviews dataset containing 50,000 reviews.

The workflow includes text preprocessing, feature extraction using TF-IDF, and training a neural network using PyTorch.

## Technologies Used

- Python
- Pandas & NumPy
- NLTK
- Scikit-learn
- PyTorch
- Matplotlib

## Workflow

1. Load the IMDB dataset.
2. Clean and preprocess text data.
3. Remove unnecessary characters and stopwords.
4. Convert text into numerical features using TF-IDF (5,000 features).
5. Split the dataset into training and testing sets.
6. Build and train a PyTorch-based RNN model.
7. Evaluate model performance.

## Model Performance

- Test Accuracy: 85.82%
- Loss Function: Binary Cross Entropy (BCELoss)
- Optimizer: Adam
- Epochs: 10

*Note: This is an initial RNN experiment. The current TF-IDF implementation uses a single timestep rather than a sequence of word embeddings. Improving the sequential architecture is part of the next development stage.*

## Learning Outcomes

- Understanding NLP preprocessing.
- Working with TF-IDF vectorization.
- Learning PyTorch tensors and DataLoaders.
- Understanding neural network training and evaluation.
- Exploring RNN-based sentiment classification.

## Future Improvements

- Implement word embeddings.
- Build a proper sequential RNN architecture.
- Improve text preprocessing.
- Evaluate using precision, recall and F1-score.

---

**Author:** Mohammed Murtuza Ali

**LinkedIn:** https://www.linkedin.com/in/mohammedmurtuzaali/
