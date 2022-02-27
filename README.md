# Credit_Risk_Analysis

## Overview of Project

This project was meant to analyze the results of a school district's standardized testing in order to find trends related to school size, type, and funding. This was done in order to provide the information necessary to make better decisions in the upcoming funding cycle. Unfortunately due to a case of academic dishonesty in one of the scools 9th graders' another analysis had to be performed excluding said school in order to have an accurate count of results with that school's 9th graders removed.

## Results 

### Balanced Accuracy Scores
Naive Random Oversampling Accuracy Score: 0.65 |  SMOTE Oversampling Accuracy Score: 0.64 | Undersampling Accuracy score: 0.52
:-------------------------:|:-------------------------:|:--------------------:
<img width="669" alt="NaiveRandomOversampling_acc_score" src="https://user-images.githubusercontent.com/89175578/155903914-6a340e07-6364-493d-a803-e5745c72c7c2.png">| <img width="667" alt="SMOTEOversampling_acc_score" src="https://user-images.githubusercontent.com/89175578/155903928-115a12fe-11fe-4d33-9e88-1943b4ebf74f.png">| <img width="665" alt="Undersampling_acc_score" src="https://user-images.githubusercontent.com/89175578/155903940-31275afb-5209-470d-b35a-5d4e2a711cf3.png">
Combination (Over and Under) Sampling Accuracy Score: 0.63 | Balanced Random Forest Classifier Accuracy Score: 0.79 | Easy Ensemble AdaBoost Classifier Accuracy Score: 0.93
<img width="668" alt="CombinationSampling_acc_score" src="https://user-images.githubusercontent.com/89175578/155903869-ddbabf72-ea99-4840-851f-45c75a0a6fd3.png">| <img width="672" alt="BalanceRandomForestClassifier_acc_score" src="https://user-images.githubusercontent.com/89175578/155903855-dd1dc5c0-8049-4ed6-8050-67b1ee166483.png"> | <img width="662" alt="EasyEnsembleAdaBoostClassifier_acc_score" src="https://user-images.githubusercontent.com/89175578/155903887-4405c232-216c-4ed3-8f77-1ec969356ff2.png">

### Precision and Recall Scores 
Naive Random Oversampling Precision and Recall Scores        |  SMOTE Oversampling Precision and Recall Scores Scores | Undersampling Precision and Recall Scores scores
:-------------------------:|:-------------------------:|:--------------------:
<img width="666" alt="NaiveOversampling_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155903985-c1ecc80a-5de5-4de0-9f09-2d16ed479f73.png">| <img width="663" alt="SMOTEOversampling_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155903993-ff60fd0e-8a6a-424d-b108-04f6a89170d4.png">|<img width="666" alt="Undersampling_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155904001-861c2fc0-fb76-4804-829b-4b49470b768b.png">
|- High Precision Score: 0.01 </br> - Low Precision Score: 1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.63 </br> - Low Recall Score: 0.67 </br> - Avg. Recall Score: 0.67 |- High Precision Score: 0.01 </br> - Low Precision Score: 1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.62 </br> - Low Recall Score: 0.66 </br> - Avg. Recall Score: 0.66 |- High Precision Score: 0.01 </br> - Low Precision Score: 1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.57 </br> - Low Recall Score: 0.46 </br> - Avg. Recall Score: 0.46|

Combination (Over and Under) Sampling Precision and Recall Scores Scores | Balanced Random Forest Classifier Precision and Recall Scores Score | Easy Ensemble AdaBoost Classifier Precision and Recall Scores Score
:-------------------------:|:-------------------------:|:--------------------:
<img width="660" alt="CombinationSampling_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155904011-f3d0a807-f488-46b1-885e-7d681034b184.png">|<img width="663" alt="BalancedRandomForestClassifier_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155904028-1b01927f-3e33-471c-99b0-43befe5d49f1.png">|<img width="665" alt="EasyEnsembleAdaBoostClassifier_precision_recall_scores" src="https://user-images.githubusercontent.com/89175578/155904034-19610053-1ece-49e9-aff6-367ff933bc66.png">
|- High Precision Score: 0.01 </br> - Low Precision Score: 1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.68 </br> - Low Recall Score: 0.58 </br> - Avg. Recall Score: 0.58 |- High Precision Score: 0.04 </br> - Low Precision Score:  1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.67 </br> - Low Recall Score: 0.91 </br> - Avg. Recall Score: 0.91 |- High Precision Score: 0.07 </br> - Low Precision Score: 1.00 </br> - Avg. Precision Score: 0.99 </br> - High Recall Score: 0.91 </br> - Low Recall Score: 0.94 </br> - Avg. Recall Score: 0.94 |


## Summary of Re-analysis.

- summarize results of machine learning model
- recommendation on the model to use
    - justification 

