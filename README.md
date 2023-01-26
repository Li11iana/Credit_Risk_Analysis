# Credit_Risk_Analysis
Loan risk prediction analysis using imbalanced-learn and scikit-learn

## Overview of the project:
Credit risk is defined as the possibility of loss when a borrower is unable to repay a loan or meet other financial obligations that interrupt the cash flow. Beyond not receiving the owed principal and interest, the lender might also have to inccur in additional costs due collections. For that reason, banks and investers evaluate carefully each loan request to try an estimate the credit risk before agreeging to any contractual obligations with the debtor. 

Since fortunately most of the loans are paid, the data available for Credit Risk is "inherently unbalance", thus requiring various training and evaluation methods to be tested for this machine learning classification project. Fot that, imbalanced-learn and scikit-learn libraries will be used to build and evaluate models using resampling.

### Objective
* Evaluate and recommend the best model for credit risk classification analysis using Supervised Machine Learning


## Results:
The credit card dataset from LendingClub was first cleaned and the training and target variables prepared. As shown below, the studied data has unbalanced classes:
![Unbalanced_data](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/unbalanced%20data.png)

The dataset was then  evaluated using the following machine learning algorithms:

### Resampling Models
1. Naive Random Oversample
The first model tested was Naive Random Oversampling. After training and fitting the model the following parameters were obtained

![Naive Random Oversampling](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png)

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

![Naive Random Oversampling Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling%20Classification%20Report.png)

2. SMOTE Oversample

![SMOTE Oversampling](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png)

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

![SMOTE Oversampling Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling%20Classification%20Report.png)

3. ClusterCentroids Undersample

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

### Combination Model
4. SMOTEEN Over and Under Sample

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

### Ensemble Classifiers
5. Balanced Random Forest Classifier


* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

6. Easy Ensemble Classifier


* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

## Summary:
The credit card dataset from LendingClub was first cleaned and the training and target variables prepared. The dataset was then  evaluated using three machine learning models using the following algorithms:
1. Oversample:

2. Undersample:

3. Combination: 

4. Ensemble Classifiers: Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier


## Recommendation
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
