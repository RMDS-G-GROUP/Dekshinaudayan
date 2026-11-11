# H1N1 Vaccination Prediction – Dataset B

## Project Overview

This project was completed as part of the MSc Data Science Research Methods in Data Science Hackathon. The aim is to predict H1N1 vaccination uptake using demographic, health-related and behavioural survey data.

The project involves exploratory data analysis, data preprocessing, feature engineering, machine learning model comparison, hyperparameter tuning, ensemble learning and evaluation of vaccination decisions based on estimated financial costs.

## Dataset

The dataset contains survey information related to H1N1 vaccination.

- Training dataset: 4,756 records
- Testing dataset: 4,749 records

## Methodology

The project follows these steps:

1. Exploratory Data Analysis (EDA)
2. Handling missing values and preprocessing
3. Feature engineering
4. Training and evaluating machine learning models
5. Cross-validation and hyperparameter tuning
6. Ensemble learning
7. Model explainability using SHAP and feature importance
8. Expected cost comparison
9. Generating predictions for the test dataset

## Machine Learning Models

Five main models were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Extra Trees Classifier
5. Histogram Gradient Boosting Classifier

Additional experiments included a tuned Random Forest and a Soft Voting Ensemble.

## Model Performance

The following results were obtained from the notebook's validation-based comparison.

| Model | ROC-AUC | Log Loss | Expected Cost |
|---|---:|---:|---:|
| Random Forest | 0.7987 | 0.5287 | $178,550 |
| Extra Trees | 0.8011 | 0.5277 | $181,025 |
| Logistic Regression | 0.8166 | 0.5061 | $187,500 |
| Histogram Gradient Boosting | 0.8028 | 0.5278 | $189,250 |
| Decision Tree | 0.7903 | 0.6404 | $193,100 |

Random Forest
