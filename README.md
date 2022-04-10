# Credit_Risk_Analysis

## Overview of the analysis:
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company to predict credit risk. Evaluate the performance of different machine  learning models & recommend  whether they should be used to predict the credit risk.

## Results:

### Naive Random Oversampling:

* The balanced accuracy scores
    ![image](./IMAGES/ros_accuracy.PNG)
* The confusion matrix
    ![image](./IMAGES/ros_confusionMatrix.PNG)
* Classification report
    ![image](./IMAGES/ros_classificationreport.PNG)

### SMOTE Oversampling:

* The balanced accuracy scores :
    ![image](./IMAGES/smote_accuracy.PNG)

* The confusion matrix
    ![image](./IMAGES/smote_confusionmatrix.PNG)

* Classification report
    ![image](./IMAGES/smote_classificationreport.PNG)



### ClusterCentroids:

* The balanced accuracy scores
    ![image](./IMAGES/cc_accuracy.PNG)
* The confusion matrix
    ![image](./IMAGES/cc_confusionMatrix.PNG)

* Classification report
    ![image](./IMAGES/cc_classificationreport.PNG)
### SMOTEENN:

* The balanced accuracy scores
    ![image](./IMAGES/smoteenn_accuracy.PNG)
* The confusion matrix
    ![image](./IMAGES/smoteenn_confusionMatrix.PNG)
* Classification report
    ![image](./IMAGES/smote_classificationreport.PNG)

### RandomForestClassifier:

* The balanced accuracy scores
    ![image](./IMAGES/rf_accuracy.PNG)
* The confusion matrix
    ![image](./IMAGES/RF_confusionMatrix.PNG)
* Classification report
    ![image](./IMAGES/RF_classification_report.PNG)

### EasyEnsembleClassifier:

* The balanced accuracy scores
    ![image](./IMAGES/eec_accuracy.PNG)
* The confusion matrix
    ![image](./IMAGES/eec_confusion_matrix.PNG)
* Classification report
    ![image](./IMAGES/eec_classification_report.PNG)

## Summary

![image](./IMAGES/summary.PNG)

Of the six machine learning models tested, I would recoomend the Easy ensemble as it had 93% accuracy and 94%% recall/sensitivity. The others I will reject as they had 50 to 66% accuracy and recall between 40 to 70%.
