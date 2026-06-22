# Airline Passenger Satisfaction Prediction

## Project Overview

This project focuses on predicting airline passenger satisfaction using supervised machine learning techniques. By analyzing passenger demographics, travel details, service ratings, and flight-related factors, the model classifies passengers as Satisfied or Dissatisfied, helping airlines identify areas for service improvement.

## Objectives

- Predict passenger satisfaction levels using historical airline data.
- Identify key factors influencing customer satisfaction.
- Compare multiple machine learning algorithms and select the most effective model.
- Support data-driven decision-making for improving airline services.

## Dataset

- **Source:** Kaggle 
- **Name:** Airline Passenger Satisfaction Dataset
- **Records:** 25,977
- **Features:** 23
- **Target Variable:** Passenger Satisfaction (Satisfied / Dissatisfied)
- Includes passenger demographics, travel information, service ratings, and delay-related features.

## Data Preprocessing

The following preprocessing techniques were applied: 

- Label Encoding and One-Hot Encoding
- Outlier Removal using IQR
- Feature Engineering - Total Delay , Average Service Rating , Significant Delay Flag
- Feature Selection using Correlation Analysis and SelectKBest
- Dimensionality Reduction using PCA
- Feature Scaling using StandardScaler
- Class Imbalance Handling using SMOTE Oversampling

## Machine Learning Models

The following classification models were trained and evaluated:

- Random Forest
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)


## Best Performing Model

#### Random Forest Classifier

Performance:

- **Accuracy:** 94.36%
- **F1-Score:** 93.71%

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Outcome

Successfully developed a machine learning classification pipeline capable of predicting airline passenger satisfaction with over 94% accuracy, providing valuable insights into customer experience and service quality improvement opportunities.
