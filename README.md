# Credit Risk Analysis

# Overview
In the case of credit risk identification analysis, credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. To employ different techniques to train and evaluate models with unbalanced classes, both imbalanced-learn and scikit-learn libraries are used to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then,a combinatorial approach is used for over- and undersampling using the SMOTEENN algorithm. Further, another two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are also used to compare the prediction on credit risk. Finally, we evaluate the performance of these models and make recommendation on whether those models should be used to predict credit risk.


# Results
 This project consists of three technical analysis.
 
 
 Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

# Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)


![complete_vine](https://github.com/hankai26/Amazon_Vine_Analysis/blob/main/images/complete_vine.png)
![complete_nonVine](https://github.com/hankai26/Amazon_Vine_Analysis/blob/main/images/complete_nonVine.png)



