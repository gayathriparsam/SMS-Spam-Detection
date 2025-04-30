# SMS-Spam-Detection
"Machine learning project to classify SMS messages as spam or legitimate using Naive Bayes, Logistic Regression, and SVM, with techniques like TF-IDF vectorization and SMOTE for class balancing."


# Spam SMS Classification

## Overview
This project builds a machine learning-based classifier to detect spam SMS messages. It uses algorithms such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) on a balanced dataset.

## Features
- Preprocessing of SMS text (cleaning, tokenization, lemmatization).
- Feature extraction using TF-IDF vectorization.
- Class imbalance handled with SMOTE.
- Model evaluation using precision, recall, F1-score, and confusion matrices.

## Results
| Model                  | Accuracy | Precision (Spam) | Recall (Spam) | F1-Score (Spam) |
|------------------------|----------|------------------|---------------|-----------------|
|   Naive Bayes          | 97%      | 83%              | 94%           | 88%             |
|   Logistic Regression  | 98%      | 92%              | 91%           | 91%             |
|   SVM                  | 98%      | 92%              | 92%           | 92%             |

