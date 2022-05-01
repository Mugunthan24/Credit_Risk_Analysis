# Credit_Risk_Analysis
Using supervised machine learning to determine credit risk.

## Overview of the Analysis
The purpose of the analysis is to evaluate the performance of several machine learning models to determine if they should be used to predict credit risk.

## Results
The subsequent sections below will examine the balanced accuracy scores and the precision and recall scores of all six machine learning models.

### Naive Random Oversampling

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 65% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling%20-%20Imbalanced%20Classification%20Report.png)

- The precision for high_risk is 1% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 66% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 64% indicating that a good portion of people who are low_risk were classified as such

### SMOTE Oversampling

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 66% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling%20-%20Imbalanced%20Classification%20Report.png)

- The precision for high_risk is 1% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 69% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 40% indicating that a good portion of people who are low_risk were classified as such

### ClusterCentroids Undersampling

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids%20Undersampling%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 54% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids%20Undersampling%20-%20Imbalanced%20Classification%20Report.png)


- The precision for high_risk is 1% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 69% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 40% indicating that a less than half of people who belong in the low_risk category were classified as such

### SMOTEENN

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/SMOTEENN%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 66% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/SMOTEENN%20-%20Imbalanced%20Accuracy%20Score.png)

- The precision for high_risk is 1% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 73% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 59% indicating that a good portion of people who are low_risk were classified as such

### Balanced Forest Classifier

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 74% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier%20-%20Imbalanced%20Classication%20Report.png)

- The precision for high_risk is 3% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 60% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 87% indicating that a good portion of people who are low_risk were classified as such

### Easy Ensemble AdaBoost Classifier

#### Balanced Accuracy Score
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Classifier%20-%20Balanced%20Accuracy%20Score.png)

- The balanced accuracy score shows that the model makes accurate predictions approximately 93% of the time

#### Imbalanced Classification Report
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Classifier%20-%20Imbalanced%20Classification%20Report.png)

- The precision for high_risk is 9% indicating that the classification for high_risk is not reliable
- The precision for low_risk is 100% indicating that the classification for low_risk is reliable
- The recall for high_risk is 92% indicating that a good portion of people who are high_risk were classified as such
- The recall for low_risk is 95% indicating that a good portion of people who are low_risk were classified as such

## Summary
![image_name](https://github.com/Mugunthan24/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Classifier%20-%20Balanced%20Accuracy%20Score.png)

After analyzing the accuracy score, precision, and recall for all of the machine learning models it can be concluded that the Easy Ensemble AdaBoost Classifier is the best model of the six. However, to further improve the models, fewer input variables should be used in order to reduce "noise." 
