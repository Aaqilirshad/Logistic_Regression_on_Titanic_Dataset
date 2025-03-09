# Logistic Regression on Titanic Dataset

**Author:** Aaqil Irshad

## Project Overview

This project involves analyzing the Titanic dataset from Kaggle to predict survival. A Logistic Regression model is implemented for classification of survival status (survived or deceased).

## Dataset

The Titanic dataset is sourced from Kaggle and is a semi-cleaned version.

## Key Steps

1. **Exploratory Data Analysis (EDA):**
    - Data visualization using Seaborn.
    - Identification and handling of missing data.
    
2. **Data Cleaning:**
    - Imputation of missing values (especially for the `Age` column).
    - Dropping irrelevant columns (`Cabin` due to excessive missing values).

3. **Feature Engineering:**
    - Conversion of categorical variables into dummy/indicator variables (e.g., `Sex`, `Embarked`, `Pclass`).

4. **Model Building:**
    - Splitting the data into training and testing sets.
    - Training a Logistic Regression model.
    - Evaluation of the model using classification metrics.

5. **Prediction on Unlabeled Data:**
    - Loading and cleaning the test dataset.
    - Predicting survival status using the trained Logistic Regression model.

## Dependencies

- Pandas
- NumPy
- Seaborn
- Scikit-learn

## Results

The model's performance is evaluated using precision, recall, and f1-score metrics. The confusion matrix helps in understanding the true positive, true negative, false positive, and false negative rates.

## Conclusion

This project demonstrates the process of building and evaluating a Logistic Regression model for predicting survival on the Titanic dataset. It includes steps from data cleaning and feature engineering to model building and evaluation.
