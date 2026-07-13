# IMDB Movie Review Sentiment Analysis using Machine Learning

## VORTEXTECH AI & ML Internship - Week 4 Task

## Project Overview

This project builds a **Sentiment Analysis Model** using Machine Learning to classify IMDB movie reviews into two categories: **Positive** and **Negative**. The model uses Natural Language Processing (NLP) techniques to preprocess text data, extract features using TF-IDF, train a classification model, and evaluate its performance.

## Dataset

**Dataset Name:** IMDB Dataset of 50K Movie Reviews  
**Source:** Kaggle  
**Dataset ID:** `lakshmi25npathi/imdb-dataset-of-50k-movie-reviews`

The dataset contains **50,000 movie reviews** with two sentiment classes:
- Positive Reviews
- Negative Reviews

The dataset is balanced with an equal number of positive and negative reviews.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- KaggleHub

## Workflow

1. Downloaded and loaded the IMDB movie review dataset.
2. Explored the dataset and checked sentiment distribution.
3. Cleaned review text by:
   - Converting text to lowercase
   - Removing HTML tags
   - Removing punctuation and special characters
   - Removing stopwords
4. Converted text into numerical features using **TF-IDF Vectorization** with 5000 features.
5. Split the dataset into training (80%) and testing (20%) sets.
6. Trained a **Logistic Regression** classification model.
7. Evaluated the model using Accuracy, F1-score, Classification Report, and Confusion Matrix.
8. Tested the model on custom movie review sentences.

## Model Performance

The Logistic Regression model achieved approximately:

- **Accuracy:** ~89%
- **F1 Score:** ~89%

The model successfully classified IMDB movie reviews as positive or negative based on learned text patterns.

## Limitations

The model may struggle with:
- Sarcasm and complex expressions
- Understanding deeper context and emotions
- Sentences with meanings that depend on real-world knowledge

## Future Improvements

- Implement deep learning models such as LSTM or GRU.
- Use transformer models like BERT for better language understanding.
- Deploy the model as a web application.


