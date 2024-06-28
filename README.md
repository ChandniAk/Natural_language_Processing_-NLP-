# Spam Detection with SpaCy and SVM Classifier
This project implements a spam detection system using the SpaCy library for natural language processing and a Support Vector Machine (SVM) classifier from scikit-learn for classification.

# Overview
Spam detection is a common use case in text classification where the goal is to classify messages as either "spam" or "not spam". In this project, we utilize SpaCy for text preprocessing and feature extraction, and we employ an SVM classifier to perform the classification.

# Requirements
Python 3.x
SpaCy
scikit-learn
Pandas 

# Installation
Clone the repository:
git clone https://github.com/yourusername/spam-detection.git
cd spam-detection
Install the required libraries:
pip install spacy scikit-learn pandas
Download the SpaCy language model:
python -m spacy download en_core_web_sm

# Implementation Details
### Data Preprocessing:
The raw text data is cleaned and preprocessed using SpaCy. This includes tokenization, lemmatization, and removal of stop words.
### Feature Extraction:
The cleaned text data is transformed into numerical features using techniques such as TF-IDF (Term Frequency-Inverse Document Frequency).
### Model Training:
An SVM classifier is trained using the extracted features. The sklearn.svm.SVC class is used for this purpose.
### Evaluation:
The trained model is evaluated on a test dataset to assess its performance in terms of accuracy and confusion matrix.


# Conclusion
This project demonstrates how to use SpaCy for text preprocessing and scikit-learn's SVM classifier for building an effective spam detection system. With this approach, you can expand the dataset and fine-tune the model to achieve even better performance.



