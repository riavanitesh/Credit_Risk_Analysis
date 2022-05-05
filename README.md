# Credit_Risk_Analysis
Supervised Machine Learning and Credit Risk

## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

1. imbalanced-learn
2. scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model)


## Purpose:

1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Compare the advantages and disadvantages of each supervised learning algorithm.
6. Determine which supervised learning algorithm is best used for a given data set or scenario.
7. Use ensemble and resampling techniques to improve model performance.

## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/96365651/166853397-55d723dc-1a63-452f-9cd8-ec315997c084.png)

1. Balanced Accuracy: 0.6612700484668286
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .66/.67

## SMOTE Oversampling
![image](https://user-images.githubusercontent.com/96365651/166853432-e6aff8d8-6299-44cf-a780-1ef389e17410.png)

1. Balanced Accuracy: 0.6303296388959394
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .62/.64

### Undersampling

![image](https://user-images.githubusercontent.com/96365651/166853459-e389f262-70e4-4da3-beb6-ff801faf8ca6.png)

1. Balanced Accuracy: 0.6303296388959394
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .63/.40

### Combination Under-Over Sampling

![image](https://user-images.githubusercontent.com/96365651/166853479-53d4ae91-5f9f-4d9e-95dd-6b9e6929e665.png)

1. Balanced Accuracy: 0.5173713090878325
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/96365651/166853538-55c9369e-46ae-457c-90bc-ffd702565744.png)

1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/96365651/166853573-1d2d7f03-d349-4056-b521-d0ed5f20c3a1.png)

1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .91/.94

## Summary:

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.





