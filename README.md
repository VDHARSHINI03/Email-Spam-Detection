# Email-Spam-Detection
# Spam Classifier

This project aims to classify text messages as either spam or ham (non-spam) using machine learning techniques.

## Dataset

The dataset used in this project is a collection of text messages labeled as spam or ham. The dataset contains the following columns:

- `Category`: Label indicating whether the message is spam or ham.
- `Message`: Text content of the message.

## Preprocessing

The text data is preprocessed using the following steps:
- Conversion to lowercase
- Tokenization
- Removal of stopwords and punctuation
- Stemming of words

## Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is used to convert the text data into numerical features.

## Classification Models

The following classification models are used to classify messages:
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)
- Random Forest

## Evaluation

The performance of each classifier is evaluated using accuracy and precision scores.

## Usage

1. Clone the repository:

