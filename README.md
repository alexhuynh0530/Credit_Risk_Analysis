# Credit_Risk_Analysis

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we create and evaluate the performance of 6 machine learning models and make a written recommendation on whether they should be used to predict credit risk.

## Results:

### Naive Random Oversampling

Balanced accuracy score: 65.12%

Precision scores
- High risk: 0.01
- Low risk: 1.00

Recall scores
- High risk: 0.74
- Low risk: 0.56

![Naive_Random_Oversampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/Naive_Random_Oversampling.png)

### SMOTE Oversampling

Balanced accuracy score: 65.49%

Precision scores
- High risk: 0.01
- Low risk: 1.00

Recall scores
- High risk: 0.62
- Low risk: 0.69

![SMOTE_Oversampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/SMOTE_Oversampling.png)

### Undersampling

Balanced accuracy score: 54.42%

Precision scores
- High risk: 0.01
- Low risk: 1.00

Recall scores 
- High risk: 0.69
- Low risk: 0.40

![Undersampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/Undersampling.png)

### Combination (Over and Under) Sampling

Balanced accuracy score: 64.8%

Precision scores
- High risk: 0.01
- Low risk: 1.00

Recall scores 
- High risk: 0.72
- Low risk: 0.57

![Combination.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/Combination.png)

### Balanced Random Forest Classifier

Balanced accuracy score: 78.85%

Precision scores
- High risk: 0.03
- Low risk: 1.00

Recall scores
- High risk: 0.70
- Low risk: 0.87

![Balanced_Random_Forest_Classifier.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/Balanced_Random_Forest_Classifier.png)

### Easy Ensemble AdaBoost Classifier

Balanced accuracy score: 93.17%

Precision scores
- High risk: 0.09
- Low risk: 1.00

Recall scores 
- High risk: 0.92
- Low risk: 0.94

![Easy_Ensemble_AdaBoost_Classifier.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/blob/main/Screenshots/Easy_Ensemble_AdaBoost_Classifier.png)

## Summary: 

When evaluating the models, we want to find the model with high recall in identifying high-risk credit applications. A low recall is indicative of a large number of false negatives, which we want to avoid.

The Easy Ensemble AdaBoost Classifier method produces the best model with a high accuracy of 93.17% as well as the highest recall score of 0.92.
