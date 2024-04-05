# Fake News Detection

## Introduction
This Python project aims to detect fake news using a dataset called news.csv. The dataset has a shape of 7796×4, with the first column identifying the news, the second and third containing the title and text, and the fourth column denoting whether the news is REAL or FAKE.

## Installation
To run this project, you'll need to install the following libraries using pip:
```
pip install numpy pandas sklearn
```

## Usage
1. Initialize a TfidfVectorizer with English stop words and a maximum document frequency of 0.7.
2. Fit and transform the vectorizer on the train set and transform the vectorizer on the test set.
3. Initialize a PassiveAggressiveClassifier.
4. Fit the classifier on tfidf_train and y_train.
5. Predict on the test set using the TfidfVectorizer.
6. Calculate the accuracy using accuracy_score() from sklearn.metrics.

## Model Performance
With the implemented model, we achieved an accuracy of 92.82%.

## Conclusion
In this project, we learned to detect fake news using Python. We utilized a political dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and trained our model. The final accuracy obtained was 92.82%. 
