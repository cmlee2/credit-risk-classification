# credit-risk-classification
## Overview of the Analysis

The purpose of this analysis was to predict whether a loan would be labeled as a healthy loan or a high risk loan. For this challenge, I used a Logisitic Regression Model to predict healthy loan (0) and high-risk loan (1) labels. The data provided included various lending data, including: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. I separated the data in to labels and features and split the data into training and testing datasets. I then fit Logisitc Regression model compared the model's predictions to the test dataset's labels.

## Results

* Machine Learning Model 1:.
   - The balanced accuracy score had a score of .952 implying that the model performs vert well on imbalanced datasets.
   - The precision of predicting health loans was 1, implying there were no false positives. The precision of predicting high-risk loans was .85 implying there were some false positives included.
   - The recall score of predicting healthy loans was .99, implying there were very few false negatives. The recall score of predicting high-risk loans was .91, implying there were more false negatives compared to health loans.
   - The precision and recall of weighted average was .99 implying that the model is very accurate in predicting the healthy loan and high risk loan labels.

## Summary

This model has a very high precision and recall, making it recommended for usage to predict loan labels.
