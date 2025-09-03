# Spam Detection with Naive Bayes

A simple yet effective spam detection system that classifies text messages as **spam** or **ham** (non-spam) using NLP and Machine Learning.

## Features
- Text preprocessing with **TF-IDF vectorization**
- **Multinomial Naive Bayes** classifier
- Model evaluation with accuracy and classification reports
- Easy API for predicting new messages

## Installation

pip install -r requirements.txt
Usage

Run the Jupyter notebook:

jupyter notebook spam_detection.ipynb


Example prediction:

new_messages = ["Congratulations! You won a prize!", "Hey, are we meeting tomorrow?"]
# Output: ['spam', 'ham']

Model Performance

Achieves high accuracy on sample dataset

For production, consider:

Larger & diverse dataset

Advanced preprocessing

Alternative models (SVM, Neural Nets)

Hyperparameter tuning
