# Credit_Risk_Analysis

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, we evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results:

### Naive Random Oversampling

Balanced accuracy score: 65.12%
Precision score: 99%
Recall score: 56%

![Naive_Random_Oversampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/Naive_Random_Oversampling.png)

### SMOTE Oversampling

Balanced accuracy score: 65.49%
Precision score: 99%
Recall score: 69%

![SMOTE_Oversampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/SMOTE_Oversampling.png)

### Undersampling

Balanced accuracy score: 54.42%
Precision score: 99%
Recall score: 40%

![Undersampling.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/Undersampling.png)

### Combination (Over and Under) Sampling

Balanced accuracy score: 64.8%
Precision score: 99%
Recall score: 57%

![Combination.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/Combination.png)

### Balanced Random Forest Classifier

Balanced accuracy score: 
Precision score: 
Recall score: 

![Balanced_Random_Forest_Classifier.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/Balanced_Random_Forest_Classifier.png)

### Easy Ensemble AdaBoost Classifier

Balanced accuracy score: 
Precision score: 
Recall score: 

![Easy_Ensemble_AdaBoost_Classifier.png](https://github.com/alexhuynh0530/Credit_Risk_Analysis/tree/main/Screenshots/Easy_Ensemble_AdaBoost_Classifier.png)

## Summary: 

