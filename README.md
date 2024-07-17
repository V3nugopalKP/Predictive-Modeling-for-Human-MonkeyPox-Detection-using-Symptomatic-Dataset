# Predictive-Modeling-for-Human-MonkeyPox-Detection

## Project Overview

This project focuses on the analysis and comparison of 10 machine learning models developed to predict human monkeypox based on clinical symptoms. The analysis was presented at ICCSMLAI 2024 on 27th February 2024.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Models Evaluated](#models-evaluated)
4. [Evaluation Metrics](#evaluation-metrics)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [Acknowledgements](#acknowledgements)

## Introduction

Monkeypox is a viral zoonosis with symptoms similar to those seen in the past in smallpox patients. The goal of this project is to predict the presence of monkeypox in patients based on their symptoms using various machine learning models. Accurate prediction can help in timely intervention and treatment.

## Dataset

The dataset used in this analysis includes clinical symptoms reported by patients suspected of having monkeypox. It consists of the following features:
- Fever
- Rash
- Lymphadenopathy
- Headache
- Muscle pain
- Fatigue
- Back pain
- Other relevant symptoms

## Models Evaluated

The following machine learning models were evaluated:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Naive Bayes
7. Gradient Boosting
8. XGBoost
9. AdaBoost
10. Neural Network

## Evaluation Metrics

The models were evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Results

| Model                 | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression   | 0.70     | 0.72      | 0.86   | 0.79     | 0.63    |
| Decision Tree         | 0.70     | 0.73      | 0.78   | 0.84     | 0.63    |
| Random Forest         | 0.69     | 0.72      | 0.86   | 0.78     | 0.62    |
| SVM                   | 0.65     | 0.65      | 1.00   | 0.79     | 0.50    |
| KNN                   | 0.71     | 0.72      | 0.91   | 0.80     | 0.62    |
| Naive Bayes           | 0.69     | 0.74      | 0.80   | 0.77     | 0.64    |
| Gradient Boosting     | 0.70     | 0.72      | 0.88   | 0.79     | 0.62    |
| XGBoost               | 0.71     | 0.71      | 0.92   | 0.80     | 0.62    |
| AdaBoost              | 0.70     | 0.72      | 0.87   | 0.79     | 0.63    |
| Neural Network        | 0.70     | 0.72      | 0.89   | 0.79     | x.xx    |

## Conclusion

Based on the evaluation metrics, the Decision Tree performed the best in predicting monkeypox based on symptoms. Future work will involve refining these models and incorporating more features to improve prediction accuracy.

## Acknowledgements

We would like to thank our team members and ICCSMLAI 2024 for the opportunity to present our work.
