# Spam or Ham Email Classifier 📧

This project focuses on building a machine learning model to classify emails as either "spam" or "ham" (not spam). The project uses various classifiers to compare performance and identify the best model for the task.

## Project Overview

- **Dataset**: The model was trained on the SMS Spam Collection dataset.
- **Techniques**: Text preprocessing, TF-IDF Vectorization, and classification using multiple machine learning algorithms.
- **Classifiers Used**:
    - Logistic Regression
    - Random Forest
    - K-Nearest Neighbors (KNN)
    - XGBoost

## Project Workflow

1. **Data Preprocessing**:
    
    - Dropped irrelevant columns and handled duplicates.
    - Cleaned text data by removing special characters, stop words, and performing other text normalization steps.
2. **Feature Extraction**:
    
    - Utilized **TF-IDF Vectorization** to transform the cleaned text data into numerical features.
3. **Model Training and Evaluation**:
    
    - Trained and tested multiple classifiers, comparing their performance based on accuracy.

## Results

The model performance was evaluated using accuracy scores, with the following results:

- **Logistic Regression**: 0.94
- **Random Forest**: 0.88
- **KNN**: 0.91
- **XGBoost**: 0.97

## Conclusion

This project demonstrates the effectiveness of different machine learning models in classifying emails as spam or ham. The results highlight the strengths of each model in handling textual data.