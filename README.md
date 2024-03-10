# Amazon Sentiment Analysis

This project focuses on performing sentiment analysis on Amazon product reviews using machine learning techniques. The goal is to classify reviews into positive and negative sentiments based on their content.

## Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Prediction](#prediction)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Amazon Sentiment Analysis is a natural language processing project that aims to analyze customer reviews on Amazon products. By categorizing reviews into positive and negative sentiments, the project helps businesses understand customer feedback and improve their products and services.

## Data Preprocessing

Before training the machine learning models, the Amazon product review data undergoes several preprocessing steps, including:

- Converting text to lowercase
- Removing punctuation and special characters
- Removing numerical values
- Removing stopwords
- Lemmatization to convert words to their base form

## Model Training

Two machine learning models are trained on the preprocessed data:

1. Logistic Regression
2. Random Forest Classifier

These models are trained using TF-IDF vectorization of the text data.

## Evaluation

The performance of the trained models is evaluated using cross-validation and classification metrics such as accuracy, precision, recall, and F1-score.

## Prediction

The trained models can be used to predict the sentiment of new Amazon product reviews. Users can input a review text, and the models will classify it as either positive or negative.

## Usage

To use the Amazon Sentiment Analysis project:

1. Install the necessary dependencies (pandas, matplotlib, nltk, scikit-learn, wordcloud).
2. Download the Amazon product review dataset.
3. Run the provided Python scripts to preprocess the data, train the models, and make predictions.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).
