# randomforest-titanic-predictions

## Overview

This R script is part of STAT 2450 Assignment 7, focusing on the implementation and evaluation of random forest models on the Titanic dataset. The analysis includes data preparation, model fitting, evaluation, and statistical inferences.

## Getting Started

### Prerequisites

Ensure that you have the required library installed:

```R
install.packages("randomForest")
library(randomForest)
```

### Data

The dataset used in this assignment contains records of passengers on the Titanic. Two CSV files (`titanictrain.csv` and `titanictest.csv`) are loaded and combined into a dataframe named 'mytitanic'.

## Sections

### 1. Question 1: Creating Folds

Set the random seed, permute rows, and create an array 'myfolds' representing folds for cross-validation.

### 2. Question 2: Creating Training and Testing Sets

Use 'myfolds' to create arrays 'textIndexes', 'mytest', and 'mytrain'.

### 3. Question 3: Fitting a Random Forest Model

Set the random seed and use the 'randomForest' library to fit a random forest model to 'mytrain'. Print the fitted model as 'myclassifier'.

### 4. Question 4: Evaluating Random Forest Model

Print 'myclassifier', plot out-of-bag errors, analyze the OOB error rates, and overlay a red line on the plot.

### 5. Question 5: Predictions and Confusion Matrix

Use 'predict' function to calculate predictions on 'mytest'. Print a confusion table and compute misclassification error and prediction accuracy.

### 6. Question 6: Importance of Predictors

Print and plot the importance of predictors.

### 7. Question 7: Tabulating Predictors

Tabulate survival chances based on 'Title', 'Title' against 'Sex', check independence, and tabulate 'Sex' against 'Survived'.

### 8. Question 8: Completing a Function

Complete the 'dotitan' function for classification accuracy with random splits.

### 9. Question 9: Running 'dotitan'

Run 'dotitan' with specified parameters, compute mean accuracy, and plot a histogram.

### 10. Question 10: Evaluating Random Forest Stability

Prepare a test-train split, run 50 replicates, save testing accuracies, and plot a histogram.

## Authors

- Tasneem Hoque

## Acknowledgments

- This script is part of a statistical analysis assignment for STAT 2450.
