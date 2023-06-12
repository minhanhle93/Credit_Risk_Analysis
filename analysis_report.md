# Credit Risk Analysis

## Overview

The purpose of this analysis was to build machine learning models to predict the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. The challenge of this analysis was dealing with the imbalanced nature of the data, where healthy loans significantly outnumber risky loans.

The data provided contained financial information related to loans, and the goal was to predict whether a loan is classified as high-risk or healthy. The variables used for prediction were not explicitly mentioned in the prompt, but it can be assumed that they include various financial and borrower-related features.

The stages of the machine learning process involved data preprocessing, model training, and evaluation. The imbalanced nature of the dataset required specific techniques to handle class imbalance, such as resampling methods.

## Results

Machine Learning Model 1:

- Accuracy: 95%
- Precision: 85% for high-risk loans and 100% for healthy loans
- Recall: 91% for high-risk loans and 99% for healthy loans

Machine Learning Model 2:

- Accuracy: 99%
- Precision: 84% for high-risk loans and 100% for healthy loans
- Recall: 99% for both high-risk loans and healthy loans

## Summary

Both Machine Learning Model 1 and Model 2 achieved high accuracy scores, with Model 2 performing slightly better with an accuracy of 99%. In terms of precision, Model 1 had a precision of 85% for high-risk loans and 100% for healthy loans, while Model 2 had a precision of 84% for high-risk loans and 100% for healthy loans.

For recall, both models achieved a high recall of 99% for both high-risk loans and healthy loans. This means that both models were effective at correctly identifying the majority of high-risk loans and healthy loans.

Based on these results, it seems that Model 2 performed slightly better in terms of accuracy and precision for high-risk loans. However, both models achieved high performance in terms of recall. 