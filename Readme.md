# Sentiment Analysis with Fine-Tuned BERT

## Project Overview
This project fine-tunes a pre-trained BERT model to classify IMDb movie reviews as either positive or negative. The model is optimized using PyTorch and Hugging Face's `transformers` library, achieving high accuracy on the binary sentiment analysis task.

## Features
- **Dataset**: IMDb dataset (50,000 movie reviews).
- **Model**: Pre-trained `bert-base-uncased` model fine-tuned for classification.
- **Performance**: High accuracy on a subset of 10,000 training and 2,000 test samples.
- **Techniques**:
  - Tokenization with `AutoTokenizer`.
  - Data preprocessing for compatibility with PyTorch.
  - Model evaluation using accuracy metrics.

## Dependencies
- Python 3.8+
- transformers
- datasets
- torch
- evaluate
- scikit-learn

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/username/sentiment-analysis-bert.git
   cd sentiment-analysis-bert
