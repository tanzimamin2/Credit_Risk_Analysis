# Credit_Risk_Analysis

## Overview of Project
### Purpose
The purpose of this analysis is to assess credit risk with machine learning models. The dataset used is unbalanced as there are far more good loans than risky loans. We will be using the credit card credit dataset from LendingClub, a peer-to-peer lending services company.


## Results
Lets take a closer look at the analysis and our findings:-

### Data Preprocessing

**1) What variable(s) are considered the target(s) for your model?**
* **_Target Variable_**:- ```IS_SUCCESSFUL```

**2) What variable(s) are considered to be the features for your model?**
* The model's _**features**_ are the variables that allow a prediction or independent variables, defined by:
  * ```APPLICATION_TYPE```, ```AFFILIATION```, ```CLASSIFICATION```, ```USE_CASE```, ```ORGANIZATION```, ```STATUS```, ```INCOME_AMT```, ```SPECIAL_CONSIDERATIONS```and ```ASK_AMT```

**3) What variable(s) are neither targets nor features, and should be removed from the input data?**
* These variables should be _**removed**_:-
  * ```EIN```
  * ```NAME```

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
   
