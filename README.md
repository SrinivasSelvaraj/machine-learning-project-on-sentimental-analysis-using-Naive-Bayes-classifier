# Sentiment Analysis with Naive Bayes Classifier

## Overview
This project demonstrates sentiment analysis using a Naive Bayes classifier on the NLTK movie_reviews dataset. The classifier is trained to predict whether a movie review is positive or negative based on its text.

## Requirements
- Python 3.x
- NLTK library (`pip install nltk`)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/SrinivasSelvaraj/machine-learning-project-on-sentimental-analysis-using-Naive-Bayes-classifier
   ```
2. Install the required dependencies:
   ```bash
   pip install nltk
   ```
3. Download the NLTK movie_reviews dataset:
   ```python
   import nltk
   nltk.download('movie_reviews')
   ```

## Usage
1. Run the `sentiment_analysis.py` file to train the classifier and perform sentiment analysis on new reviews.
   ```bash
   python sentiment_analysis.py
   ```

## Results
- The accuracy of the classifier on the test set is displayed.
- The most informative features used by the classifier are shown.
- Sentiment predictions for new reviews are displayed.
