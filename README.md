# Plagiarism Detector Using Machine Learning

## Introduction
Plagiarism detection is essential in educational and professional settings. This project leverages machine learning techniques to create a robust plagiarism detector that accurately identifies copied content.

## Dataset Collection
We gather a comprehensive dataset consisting of text documents containing original and plagiarized content, sourced from online platforms like Kaggle or manually created.

## Data Preprocessing
- **Tokenization**: Splitting text into words.
- **Lowercasing**: Converting text to lowercase.
- **Removing Punctuation**: Eliminating punctuation marks.
- **Stopwords Removal**: Removing common words that don't add meaning.

## Machine Learning Model
We utilize the Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer to transform text data into numerical features, training a simple logistic regression model.

## Web Application
A Flask web application provides a user interface for inputting two text documents and receiving a plagiarism score.
