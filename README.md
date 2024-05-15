# Human Activity Recognition (HAR) Prediction Models

## Introduction
This project focuses on building and evaluating machine learning models for Human Activity Recognition (HAR) using a dataset of sensor readings from wearable devices. The goal is to classify different human activities based on the sensor data.

## Summary
The primary steps involved in this project include:

- **Data Loading and Preprocessing**
  - Loading the HAR dataset and preprocessing the data.
- **Feature Extraction**
  - Extracting relevant features from the sensor data for model training.
- **Model Training**
  - Training various machine learning models, including:
    - Decision Tree
    - Random Forest
    - Gradient Boosting
    - Support Vector Machine (SVM)
    - k-Nearest Neighbors (k-NN)
- **Model Evaluation**
  - Evaluating the performance of the trained models using metrics such as accuracy, precision, recall, and F1-score.
- **Model Selection**
  - Selecting the best-performing model based on the evaluation metrics.

## Evaluation Metrics
The evaluation of the HAR models is based on the following metrics:

- **Accuracy**: The proportion of correctly classified instances among the total instances.
- **Precision**: The proportion of true positive instances among the instances classified as positive.
- **Recall**: The proportion of true positive instances among the total actual positive instances.
- **F1-score**: The harmonic mean of precision and recall, providing a balance between the two.

## Results
The results of the model training and evaluation are summarized as follows:

- **Decision Tree**: 
  - Accuracy: 0.85
  - Precision: 0.84
  - Recall: 0.85
  - F1-score: 0.84
- **Random Forest**: 
  - Accuracy: 0.89
  - Precision: 0.88
  - Recall: 0.89
  - F1-score: 0.88
- **Gradient Boosting**: 
  - Accuracy: 0.88
  - Precision: 0.87
  - Recall: 0.88
  - F1-score: 0.87
- **Support Vector Machine (SVM)**: 
  - Accuracy: 0.86
  - Precision: 0.85
  - Recall: 0.86
  - F1-score: 0.85
- **k-Nearest Neighbors (k-NN)**: 
  - Accuracy: 0.84
  - Precision: 0.83
  - Recall: 0.84
  - F1-score: 0.83

Based on the evaluation metrics, the Random Forest model achieved the highest accuracy and F1-score, making it the best-performing model for this HAR dataset.

## Dependencies
To run this project, you need the following dependencies:

