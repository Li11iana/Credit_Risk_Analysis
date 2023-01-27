# Credit_Risk_Analysis
Loan risk prediction analysis using imbalanced-learn and scikit-learn

## Overview of the project:
Credit risk is defined as the possibility of loss when a borrower is unable to repay a loan or meet other financial obligations that interrupt the cash flow. Beyond not receiving the owed principal and interest, the lender might also have to inccur in additional costs due collections. For that reason, banks and investers evaluate carefully each loan request to try an estimate the credit risk before agreeging to any contractual obligations with the debtor. 

Since fortunately most of the loans are paid, the data available for Credit Risk is "inherently unbalance", thus requiring various training and evaluation methods to be tested for this machine learning classification project. Fot that, imbalanced-learn and scikit-learn libraries will be used to build and evaluate models using resampling.

### Objective
* Evaluate and recommend the best model for credit risk classification analysis using Supervised Machine Learning


## Results and Summary:

The credit card dataset from LendingClub was first cleaned and the training and target variables prepared. As shown below, the studied data has unbalanced classes:
![Unbalanced_data](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/unbalanced%20data.png)

The dataset was then  evaluated using the following machine learning algorithms:

### Resampling Models
#### Naive Random Oversample
This first model tested was Naive Random Oversampling. After training and fitting the model the following parameters were obtained:

![Naive Random Oversampling](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png)

* Accuracy = 0.66
* True Positive (TP) = 73
* True Negative (TN) = 10,264
* False Positive (FP) = 6,840
* False Negative (FN) = 28

A classification report of the Naive Random Oversampling model shows how it performed.

![Naive Random Oversampling Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling%20Classification%20Report.png)

Classification report: 
* __Precision__ = The model presents 0.01 precision when classifiyng high risk credit and contrastly 1.00 precision for low risk credit.
* __Recall__ = The ratio of true classifications to the sum all events classified is relatively similar for high and low risk with 0.72 for the first one (sensitivity) and 0.60 for the latter (specificity).
* __F1 Score__ = The wieghted harmonic mean of precision and recall shows further contrast between the models ability to classify correctly with just 0.02 for the high risk and 0.72 for low risk credit.
* __Support__ = The number of actual occurrences of the class high risk is 101 events while there were 17104 low rish credit cases in the testing sample.

2. SMOTE Oversample

![SMOTE Oversampling.png](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling.png)

* Accuracy = 0.658
* True Positive (TP) = 63
* True Negative (TN) = 11,844
* False Positive (FP) = 5,260
* False Negative (FN) = 38

A classification report of the SMOTE Oversampling model shows how it performed.

![SMOTE Oversampling Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling%20Classification%20Report.png)

Classification report: 
* __Precision__ = The model presents 0.01 precision when classifiyng high risk credit and contrastly 1.00 precision for low risk credit.
* __Recall__ = The ratio of true classifications to the sum all events classified is relatively similar for high and low risk with 0.62 for the first one (sensitivity) and 0.69 for the latter (specificity).
* __F1 Score__ = The wieghted harmonic mean of precision and recall shows further contrast between the models ability to classify correctly with just 0.02 for the high risk and 0.82 for low risk credit.
* __Support__ = The number of actual occurrences of the class high risk is 101 events while there were 17104 low rish credit cases in the testing sample.

3. ClusterCentroids Undersample

![ClusterCentroids Undersampling.png](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/ClusterCentroids%20Undersampling.png)

* Accuracy = 0.545
* True Positive (TP) = 70
* True Negative (TN) = 6,780
* False Positive (FP) = 10,324
* False Negative (FN) = 31

A classification report of the Naive Random Oversampling model shows how it performed.

![ClusterCentroids Undersampling Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/ClusterCentroids%20Undersampling%20Report.png)

Classification report: 
* __Precision__ = The model presents 0.01 precision when classifiyng high risk credit and contrastly 1.00 precision for low risk credit.
* __Recall__ = The ratio of true classifications to the sum all events classified is relatively similar for high and low risk with 0.69 for the first one (sensitivity) and 0.40 for the latter (specificity).
* __F1 Score__ = The wieghted harmonic mean of precision and recall shows further contrast between the models ability to classify correctly with just 0.01 for the high risk and bearly 0.57 for low risk credit.
* __Support__ = The number of actual occurrences of the class high risk is 101 events while there were 17104 low rish credit cases in the testing sample.

### Combination Model
4. SMOTEEN Over and Under Sample

![MOTEENN Sampling](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/SMOTEENN%20Sampling.png)

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

![SMOTEENN Sampling Classification Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/SMOTEENN%20Sampling%20Classification%20Report.png)

### Ensemble Classifiers
5. Balanced Random Forest Classifier

![Balance Random Forest](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Balance%20Random%20Forest.png)

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

![Balance Random Forest Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Balance%20Random%20Forest%20Report.png)

6. Easy Ensemble Classifier
![Easy Ensemble Classifier](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20Classifier.png)

* Accuracy = 
* True Positive (TP) = 
* True Negative (TN) =
* False Positive (FP) =
* False Negative (FN) = 

![Easy Ensemble Classifier Report](https://github.com/Li11iana/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20Classifier%20Report.png)



## Recommendation
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
