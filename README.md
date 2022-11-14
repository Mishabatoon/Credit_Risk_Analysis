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
![Naive Random](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Naive%20Random%20Sampling.png)

### SMOTE Oversampling
![SMOTE_Oversampling](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/SMOTE%20Oversampling.png)

### Undersampling (ClusterCentroids)
![Undersampling](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Undersampling.png)

### Combination (Over and Under) Sampling - SMOTEENN
![Combination](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Combination.png)

### Balanced Random Forest Classifier
![brfc](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Balanced%20Random%20Forest%20Classifier.png)

### Easy Ensemble AdaBoost Classifier
![enter image description here](https://raw.githubusercontent.com/Mishabatoon/Credit_Risk_Analysis/main/Screenshots/Easy%20Ensemble.png)



## Summary
4. Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
