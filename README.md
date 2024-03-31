# Fake Reddit Prediction Competition 🎯
## Participant Information
- **Username:** yaraelzahy
- **Displayed Name:** Yara Elzahy

## Overview
Repository for Fake Reddit Prediction Competition. Explored various techniques and models for classifying Reddit posts as fake news or not. Used TF-IDF and Count Vectorizers with Logistic Regression, XGBoost, and Gradient Boosting models.

- **Character n-gram vs. Word n-gram:** Differences and OOV issues.
- **Stop Word Removal vs. Stemming:** Language dependency.
- **Tokenization Techniques:** Language dependency and importance.
- **Count Vectorizer vs. TF-IDF Vectorizer:** Differences and n-gram feasibility.

## Problem Formulation
- **Problem:** Determine fake news in Reddit posts.
- **Input:** Text features with varied word forms.
- **Output:** Binary classification of fake news.
- **Challenges:** Handling multiple word forms and outlier values.

## Experimental Protocol
- Cleaned and preprocessed text data.
- Used TF-IDF and Count Vectorizers for numeric conversion.
- Employed Logistic Regression, XGBoost, and Gradient Boosting.
- Hyperparameter tuning via GridSearchCV and RandomizedSearchCV.
- Evaluation using kaggle scores and cross-validation.

## Results
- **Best Model:** Logistic Regression with TF-IDF Vectorizer.
- **Highest Score:** Kaggle score of 0.85803.
- **Consistency:** Logistic Regression outperformed across trials.

## Conclusion
- Logistic Regression with TF-IDF Vectorizer was consistently effective.
- Hyperparameter tuning crucially impacted model performance.
- Repository provides insights into text preprocessing and model selection.

