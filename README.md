# Practical Application III: Comparing Classifiers

## Overview

In this practical application, the goal is to compare the performance of various classifiers, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines, using a dataset related to marketing bank products over the telephone.

## Getting Started

The dataset comes from the UCI Machine Learning repository and contains data from a Portuguese banking institution, detailing the results of multiple marketing campaigns. More information on the data and features can be found in the accompanying article.

## Problem Statements

### Problem 1: Understanding the Data

To gain a better understanding of the data, examine the information provided in the UCI repository and the Materials and Methods section of the accompanying paper. The dataset includes 17 marketing campaigns conducted between May 2008 and November 2010, with a total of 79,354 contacts.

### Problem 2: Reading the Data

Use pandas to read the dataset `bank-additional-full.csv` and assign it to a meaningful variable name.

### Problem 3: Understanding the Features

Analyze the data description to identify any missing values or features that need to be coerced to a different data type. The dataset includes various attributes related to bank clients, their last contact, and other social and economic context attributes.

### Problem 4: Understanding the Task

State the business objective clearly. The dataset shows that marketing campaigns were generally ineffective in securing customer subscriptions to the long-term deposit product. The goal is to build a predictive model to enhance campaign efficiency by identifying factors that could potentially increase the success rate.

### Problem 5: Engineering Features

Prepare the features and target column for modeling with appropriate encoding and transformations. Use the ColumnTransformer to apply specific transforms to numerical and categorical columns, and LabelEncoder to encode the target column.

### Problem 6: Train/Test Split

Split the data into training and testing sets using sklearn's train_test_split.

### Problem 7: A Baseline Model

Establish a baseline performance using a simple classification model that predicts the majority class.

### Problem 8: A Simple Model

Build a basic model using Logistic Regression.

### Problem 9: Score the Model

Evaluate the accuracy of the Logistic Regression model.

### Problem 10: Model Comparisons

Compare the performance of the Logistic Regression model to KNN, Decision Tree, and SVM models. Capture training time and accuracy for each model.

### Problem 11: Improving the Model

Explore feature engineering, hyperparameter tuning, and grid search to improve the models. Present the findings in a DataFrame.

## Files

- `prompt_III.html`: The main HTML file containing the Jupyter notebook's content, including scripts for widget rendering and styles for proper display.

## Requirements

To view and interact with the notebook, ensure you have the following:
- A modern web browser (Chrome, Firefox, Safari, Edge).
- Internet access to load external scripts and styles.

## Viewing the Notebook

Open the `prompt_III.html` file in your web browser. The notebook contains interactive widgets that require JavaScript to be enabled.


## Contact

For any questions or issues, please contact the project maintainers.
