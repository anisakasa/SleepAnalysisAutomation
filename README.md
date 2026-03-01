# SleepDisordersPredictions
Exploratory and predictive analysis of lifestyle factors influencing sleep health outcomes


#Project Overview

This project uses a Logistic Regression model to predict whether a person has a sleep disorder based on health and lifestyle data.
The goal is to analyse patterns in sleep-related factors and build a classification model to assist in early detection.

#Problem Statement 

Sleep disorders are increasingly common due to lifestyle, stress, and health-related factors. Early identification can help improve overall health and quality of life.The goal of this project is to build a machine learning model that predicts whether an individual has a sleep disorder (1) or does not have a sleep disorder (0) based on health and lifestyle features such as sleep duration, physical activity level, stress level, BMI, and heart rate.

#Why Logistic Regression?

Logistic Regression was chosen because this is a binary classification problem (predicting either presence or absence of a sleep disorder).

Logistic Regression is:
- Simple and interpretable
- Effective for small to medium-sized datasets
- Useful for understanding how each feature impacts the probability of a condition

Additionally, the model provides coefficients that help interpret which factors increase or decrease the likelihood of a sleep disorder.

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Machine Learning Approach
- Data cleaning and preprocessing
- Feature selection
- Train-test split
- Logistic Regression model
- Model evaluation using:
  - Accuracy score
  - Confusion matrix
  - Classification report

Results
The model achieved an accuracy of 94.67% on the test dataset.
Feature importance analysis showed that certain lifestyle and health factors significantly influence sleep disorder prediction.

