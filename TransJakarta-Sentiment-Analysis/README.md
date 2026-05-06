# Sentiment Analysis of TransJakarta App Reviews

## Project Overview
This project analyzes user reviews from the TransJakarta mobile application on Google Play Store using Natural Language Processing (NLP) and machine learning techniques.

## Objective
The objective of this project is to classify user reviews into positive and negative sentiments and compare the performance of multiple machine learning models.

## Dataset
- Source: Google Play Store Reviews
- Total Reviews: 4,364 reviews
- Data collected using `google-play-scraper`

## Text Preprocessing
The preprocessing stage was conducted to clean and standardize the review text before feature extraction and machine learning modeling.

Preprocessing techniques include:
- Text cleaning
- Lowercasing
- Stopword removal
- Stemming
- Tokenization

## Feature Extraction
TF-IDF Vectorizer was used to transform text data into numerical vectors.

## Handling Imbalanced Data
SMOTE (Synthetic Minority Oversampling Technique) was applied to balance the dataset and improve classification performance.

## Machine Learning Models
- Support Vector Machine (SVM)
- CatBoost
- XGBoost

## Results
SVM achieved the best performance with:
- Accuracy: 94%
- Precision: 96%
- Recall: 95%
- F1-Score: 96%

## Key Insights
- SVM achieved the best overall classification performance.
- SMOTE improved minority class prediction.
- Most reviews show positive sentiment toward the TransJakarta application.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Sastrawi
- TF-IDF
- Google Colab
