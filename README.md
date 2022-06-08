# Credit Risk Analysis

## Overview
In the case of credit risk identification analysis, credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. To employ different techniques to train and evaluate models with unbalanced classes, both imbalanced-learn and scikit-learn libraries are used to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then,a combinatorial approach is used for over- and undersampling using the SMOTEENN algorithm. Further, another two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are also used to compare the prediction on credit risk. Finally, we evaluate the performance of these models and make recommendation on whether those models should be used to predict credit risk.


## Results
 This project consists of six model analysis.

 - Use Resampling Models to Predict Credit Risk
    
### Naive Random Oversampling
![nro_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/nro_1.png)

![nro_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/nro_2.png)

### SMOTE Oversampling
![smote_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/smote_1.png)

![smote_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/smote_2.png)

### Undersampling
![under_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/under_1.png)

![under_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/under_2.png)

 - Use the SMOTEENN Algorithm to Predict Credit Risk
### Combination (Over and Under) Sampling
![smoteenn_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/smoteenn_1.png)

![smoteenn_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/smoteenn_2.png)


 - Use Ensemble Classifiers to Predict Credit Risk
### Balanced Random Forest Classifier
![brfc_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/brfc_1.png)

![brfc_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/brfc_2.png)

### Easy Ensemble AdaBoost Classifier
![eec_1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/eec_1.png)

![eec_2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/eec_2.png)


- Accuracy Score
![score1](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/score1.png)

![score2](https://github.com/hankai26/Credit_Risk_Analysis/blob/main/Module-17-Challenge/image/score2.png)


## Summary
The analysis results indicate that the precision for all six models are low, as well as the f1 score. That means those models have problems in predicting high-risk cases. None of the six models would be recommended in this case.