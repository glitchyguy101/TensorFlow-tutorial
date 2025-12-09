# TensorFlow Practice: Fashion MNIST & IMDB Reviews

This repository contains practice implementations of deep learning
models built using TensorFlow and Keras. The project explores two key
areas of machine learning:

- Computer Vision: Image classification using the Fashion MNIST dataset
- Natural Language Processing: Sentiment analysis using the IMDB movie
  reviews dataset

Both tasks demonstrate essentials such as data preprocessing, model
building, training, evaluation, and visualization.


## Project Overview

### 1. Fashion MNIST Classification

- Goal: Classify images of clothing items into 10 categories such as
  T-shirt, Trouser, Sneaker, etc.
- Dataset: Fashion MNIST
  - 60,000 training images
  - 10,000 test images
  - 28×28 grayscale
- Model Approaches:
  - Dense Neural Network (DNN)
  - Convolutional Neural Network (CNN)

### 2. IMDB Movie Review Sentiment Analysis

- Goal: Classify movie reviews as Positive or Negative.
- Dataset: IMDB Large Movie Review Dataset
  - 25,000 training reviews
  - 25,000 test reviews
- Model Approach:
  - Text vectorization
  - Embedding layers
  - Global Average Pooling classifier

## Features

- Clean and simple TensorFlow training workflows
- Clear model architectures for beginners
- Accuracy/loss visualization using Matplotlib
- Example predictions for both text and images
- Easy-to-modify code structure

## Tech Stack & Dependencies

- Python 3.x
- TensorFlow / Keras (2.x)
- NumPy
- Matplotlib
- Pandas
