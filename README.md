# Credit Risk Analysis

## Overview of the Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. It is important for creditors to evaluate and verify borrowers' credit scores and background in order to assess the credit risk.
Here are the methods used to analyze, evaluate and predict the credit risk:

- Use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling.
- Oversample the data using the `RandomOverSampler` and `SMOTE` algorithms
- Undersample the data using the `ClusterCentroids` algorithm
- Use a combinatorial approach of over- and undersampling using the `SMOTEENN` algorithm
- Compare two new machine learning models that reduce bias, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier`, to predict credit risk
    
## Results  

### Naive Random Oversampling
- Balanced Accuracy Score is 0.6314677834584286
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 57% are high risk applicants and 69% are low risk applicants
![Naive Random](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Naive%20Random%20Sampling.png)


### SMOTE Oversampling
- Balanced Accuracy Score is 0.6268316069795457
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 61% are high risk applicants and 64% are low risk applicants
![SMOTE_Oversampling](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/SMOTE%20Oversampling.png)


### Undersampling (ClusterCentroids)
- Balanced Accuracy Score is 0.6268316069795457
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 61% are high risk applicants and 45% are low risk applicants
![Undersampling](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Undersampling.png)

### Combination (Over and Under) Sampling - SMOTEENN
- Balanced Accuracy Score is 0.5292442720105072
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 70% are high risk applicants and 58% are low risk applicants
![Combination](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Combination.png)

### Balanced Random Forest Classifier
- Balanced Accuracy Score is 0.7877672625306695
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 67% are high risk applicants and 91% are low risk applicants
![brfc](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Balanced%20Random%20Forest%20Classifier.png)

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score is 0.925427358175101
- The precision is low for high risk loan/credit applicants and is high for low risk loan/credit applicants
- Recall: 91% are high risk applicants and 94% are low risk applicants
![enter image description here](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Easy%20Ensemble.png)



## Summary
Out of the six machine learning models that were ran, Easy Ensemble AdaBoost Classifier has the highest Balanced Accuracy Score which is 93%. Although, all models have the same precision, the Easy Ensemble AdaBoost Classifier is the best fit model to analyze and predict the credit risk.
