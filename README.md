# Credit_Risk_Analysis

## Overview of Project
### Purpose
The purpose of this analysis is to assess credit risk with machine learning models. The dataset used is unbalanced as there are far more good loans than risky loans. We will be using the credit card credit dataset from LendingClub, a peer-to-peer lending services company.


## Results
Lets take a closer look at the analysis and our findings:-

**1) Oversampling: Naive Random Oversampling**
* **_Accuracy Score_**: 66%
* **_Precision_**
  * _**High Risk**_: 0.01
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.72
  * _**Low Risk:**_ 0.60 


**2) Oversampling: SMOTE Oversampling**
* **_Accuracy Score_**: 66%
* **_Precision_**
  * _**High Risk**_: 0.01
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.61
  * _**Low Risk:**_ 0.70


**3) Undersampling: Cluster Centroids**
* **_Accuracy Score_**: 66%
* **_Precision_**
  * _**High Risk**_: 0.01
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.69
  * _**Low Risk:**_ 0.40


**4) Combination of Over and Under Sampling**
* **_Accuracy Score_**: 54%
* **_Precision_**
  * _**High Risk**_: 0.01
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.78
  * _**Low Risk:**_ 0.57


**5) Balanced Random Forest Classifier**
* **_Accuracy Score_**: 79%
* **_Precision_**
  * _**High Risk**_: 0.03
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.70
  * _**Low Risk:**_ 0.87


**6) Easy Ensemble AdaBoost Classifier**
* **_Accuracy Score_**: 93%
* **_Precision_**
  * _**High Risk**_: 0.09
  * _**Low Risk:**_ 1.00
* **_Recall_**
  * _**High Risk**_: 0.92
  * _**Low Risk:**_ 0.94


## Summary
The Easy Ensemble AdaBoost Classifier algorithm has the highest accuracy score of 93%. The precision values in general across all the algorithm are low and the recall values are high, as such these algorithms including the Easy Ensemble AdaBoost Classifier algorithm are not good enough to assess if a credit is high risk. This indicates that there is a lot of false positives and my recommendation would be to not use this models to predict credit risk.


## Links
  * Visit this [link](https://github.com/tanzimamin2/Credit_Risk_Analysis) for the excel dataset and other resources.
   
