# Sentiment Analysis with RNN on IMDB Data

## Introduction

This project implements a simple Recurrent Neural Network (RNN) for sentiment analysis on IMDB movie reviews. Leveraging deep learning techniques, the model classifies reviews as positive or negative, providing valuable insights into public opinion.

## Project Highlights

- **Data Source:** The IMDB dataset is downloaded from Keras and preprocessed for efficient training.
- **Preprocessing Steps:**
  - Tokenization: `tokenizer.fit_on_texts`
  - Sequencing: `tokenizer.texts_to_sequences`
  - Padding: Ensuring uniform input length
- **Model Architecture:**
  - Sequential Model with an Embedding Layer
  - Input dimension: 25,000, Output dimension: 2
  - Dense Layer with Sigmoid Activation Function
  - Compiled with Adam Optimizer and Accuracy Metrics
- **Training & Prediction:**
  - Fitting the model on preprocessed data
  - Predicting sentiment (positive if >0.5, else negative)

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Keras

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PrajapatiAvinash/Sentimate-Analysis-with-RNN-on-the-imdb-data.git
