# Student Mental Health Prediction

## Overview
This project applies machine learning classification techniques to predict depression and other mental health issues among students based on survey data. It includes data preprocessing, visualization, and model evaluation to identify key factors influencing mental health.

## Project Description
This study analyzes student mental health data to understand the impact of academic and personal factors on conditions such as depression, anxiety, and panic attacks. Various machine learning models are used to classify responses and predict mental health outcomes.

## Dataset
The dataset consists of student survey responses covering:
- Gender
- Age
- Course and year of study
- CGPA
- Marital status
- Self-reported mental health conditions (depression, anxiety, panic attacks)
- Treatment-seeking behavior

## Data Preprocessing
Key preprocessing steps include:
- Handling missing values
- Encoding categorical variables
- Normalizing numerical features
- Splitting data into training and testing sets

Additionally, data mining techniques such as correlation analysis and feature selection are applied to identify the most influential factors affecting mental health outcomes. Clustering methods are explored to detect patterns within different student groups.

## Modeling
The following classifiers are evaluated:
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Gaussian Naive Bayes

Performance is measured using accuracy, precision, recall, and F1-score.

## Results
Results are visualized through:
- Mental health condition distributions
- Key feature impact analysis
- Confusion matrices for model evaluation

The models achieved the following performance:
- **SVC**: Accuracy of 85%, with strong precision and recall scores.
- **Decision Tree**: Accuracy of 78%, providing interpretability but lower generalization.
- **Gaussian Naive Bayes**: Accuracy of 74%, performing well on specific categories but with lower overall predictive power.

The results indicate that SVC is the most effective classifier for this dataset, while Decision Tree and Naive Bayes offer additional interpretability. Future work may focus on improving feature engineering, exploring ensemble models, and incorporating deep learning techniques for enhanced predictions.

