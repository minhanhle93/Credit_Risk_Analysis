# Creditworthiness Prediction Analysis

This repository contains the code and analysis for predicting the creditworthiness of borrowers using machine learning models. The analysis utilizes a dataset of historical lending activity obtained from a peer-to-peer lending services company. The primary challenge addressed in this analysis is the inherent class imbalance in the dataset, where healthy loans significantly outnumber risky loans.

## Overview

The goal of this analysis is to develop accurate machine learning models that can classify loans as either high-risk or healthy based on the provided financial information. The dataset consists of various features related to loans and borrowers, which are used as inputs for the prediction models. The analysis involves several stages, including data preprocessing, model training, and evaluation.

## Machine Learning Models

Two machine learning models, referred to as Model 1 and Model 2, are developed and evaluated in this analysis using Logistic Regression with the original data and resampled data.

## Summary

Both Model 1 and Model 2 exhibited strong performance in predicting loan creditworthiness. Model 2 achieved higher accuracy and precision scores for high-risk loans compared to Model 1. However, both models demonstrated excellent recall scores, correctly identifying the majority of high-risk and healthy loans.

## Technologies Used

- numpy
- pandas
- sklearn
- pathlib
- imblearn