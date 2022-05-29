# Credit_Risk_Analysis

## Overview
The goal of this project is to use the dataset from LendingClub, a peer-to-peer lending services company to create models that will predict whether a loan is high-risk or low-risk. As the majority of loans are low risk or good loans the dataset will be unbalanced with high risk loans being in the minority. 

We will use several machine learning models to balance the data and then evaluate the performance of the models based on a the accuracy score and classification report. 

## Results

* Random Oversampling: 

The Random Oversampling model produced an accuracy score of 68%. The model produced an overall precision score of 99% and a recall of 61% for high risk loans and a recall of 68% for low risk loans.
![ROS Output](https://user-images.githubusercontent.com/96552268/170891053-b070dc05-dc63-4704-9d3f-b805b5c69d41.png)

* SMOTE:


The SMOTE model produced an accuracy score of 63%. The model produced an overall precision score of 99% and a recall of 64% for high risk loans and a recall of 63% for low risk loans.

![SMOTE Output](https://user-images.githubusercontent.com/96552268/170891292-a5d2d3ec-6f51-4042-bd21-f34f87a40e65.png)


* Cluster Centroid Undersampling:


The Cluster Centroid Undersampling model produced an accuracy score of 45%. The model produced an overall precision score of 99% and a recall of 61% for high risk loans and a recall of 45% for low risk loans.


![ClusterCentroid Output](https://user-images.githubusercontent.com/96552268/170891305-7408a54f-bc61-4b54-a5e1-bfc9e6b95f46.png)

* SMOTTEEN
The SMOTTEEN model produced an accuracy score of 45%. The model produced an overall precision score of 99% and a recall of 61% for high risk loans and a recall of 45% for low risk loans.
![SMOTEENN Output](https://user-images.githubusercontent.com/96552268/170891309-2954a7eb-8d24-4088-ba3a-7be50013ef40.png)


* Balanced Random Forest Classifier:


The Balanced Random Forest Classifier model produced an accuracy score of 78%. The model produced an overall precision score of 99% and a recall of 67% for high risk loans and a recall of 91% for low risk loans.

![RandomForest Output](https://user-images.githubusercontent.com/96552268/170891319-180de0a7-6d0c-431a-b4dc-910f51eafb1a.png)


* Easy Ensemble Classifier:

The Easy Ensemble Classifier model produced an accuracy score of 92%. The model produced an overall precision score of 99% and a recall of 91% for high risk loans and a recall of 94% for low risk loans.

![EasyEnsamble Output](https://user-images.githubusercontent.com/96552268/170891328-58b07e2e-9ee5-45f6-aaf9-8f383c7cacf2.png)


## Summary

* Summary
* Recommendation
