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



### Compiling, Training, and Evaluating the Model


**1) How many neurons, layers, and activation functions did you select for your neural network model, and why?**
* For the first attempt, two layers were used (_First layer-_ 80 Neurons, Second layer- 30 Neurons. 

  For the code to be more accurate, three layers were added and the neuron count increased.
  
  Even after adding more layers the accuracy did not increase (the accuracy stayed around 72%)
  
* For the third attempt, third layer was removed and the neuron count was increased (_First layer-_ 200 Neurons, _Second layer-_ 80 Neuron).

**2) Were you able to achieve the target model performance?**
* No

**3) What steps did you take to try and increase model performance?**
* New layers were added but did not help
* Neuron count was increased. Helped a bit, still was not able increse the accuracy over 75%

## Summary

In 

## Links
  * Visit this [link](https://github.com/tanzimamin2/Neural_Network_Charity_Analysis) for the excel dataset and other resources.
   
