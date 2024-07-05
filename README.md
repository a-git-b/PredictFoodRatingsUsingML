# Predict Food Ratings Using ML

## Overview
This project involves predicting food ratings on a scale of 1-5 based on a given dataset that includes recipe names, user reviews, and additional information about the recipes. The primary goal is to develop a model that accurately predicts these ratings using machine learning techniques.

## Dataset
The dataset contains
- Recipe Names
- User Reviews
- User Reputation
- Various other attributes
  
## Problem Statement
Given the dataset, the task is to predict the food ratings on a scale from 1 to 5. This is approached as a classification problem.

## Steps implemented
1. Data Preprocessing
   - Handled missing values
   - Conducted EDA to understand the distribution and relationships within the data.
2. Text Preprocessing
   - Transformed user reviews into numeric data using TfidfVectorizer to handle text data effectively.
3. Data Scaling
   - Scaled the numerical features to ensure that the models perform optimally.
4. Model Selection and Hyperparameter Tuning
   - Applied various classification models like Logistic Regression, RandomForestClassifier, SGDClassifier, XGBoostClassifier.
   - Performed hyperparameter tuning to improve their performance.
5. Evaluation
   - Evaluated the model based on accuracy score.

## Results
   XGBClassifier was the best performing model with highest accuracy. 
     
