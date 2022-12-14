# Credit_Risk_Analysis

## Purpose

The goal of this project is to use machine learning in roder to assess the credit card risk and resolve the inherent unbalanced classification problem as good loans outnumber risk loans.
Therefore, it's important to train and evaluate different models with unbalanced classes and choose best performing ones.

## Tools and Software 
- Anaconda, Jupyter Notebooks, Numpy, Pandas, scipy, Scikit-learn, etc. as well as Git Bash to commit changes into GitHub Repository.


# Results
Jill's goal is to analyze different machine learning algorithms and models in order to assess the credit risk unbalanced classification and therefore, best select the high performing model or combination of models.<br>
- Here are an overall matrix that contains balanced accuracy scores, precision, recall scores, and F1 scores of all six machine learning models. <br>

| Models                           | Accuracy Score    | Precision |Recall(Sensitivity) | F1 Score   | Best Performance                                      |
|:---------------------------------|:------------------|:----------|:-------------------|:-----------|:------------------------------------------------------|
|Oversampling:                     |                   |           |                    |            |                                                       | 
|Naïve random oversampling         |0.6573009382322703 |0.99       |0.60                |0.75        |                                                       |
|SMOTE                             |0.6622479600626106 |0.99       |0.69                |0.81        |SMOTE performs better.                                 |
|                                  |                   |           |                    |            |                                                       |
|Undersampling:                    |                   |           |                    |            |                                                       |
|Cluster Centroids                 |0.5447339051023905 |0.99       |0.40                |0.56        |                                                       |
|                                  |                   |           |                    |            |                                                       |
|Combined:                         |                   |           |                    |            |                                                       |
|SMOTEENN                          |0.639224858524206  |0.99       |0.58                |0.73        |                                                       |    
|                                  |                   |           |                    |            |                                                       |
|Ensemble:                         |                   |           |                    |            |                                                       |
|Balanced Random Forest Classifier |0.7885466545953005 |0.99       |0.87                |0.93        |                                                       |
|Easy Ensemble Classifier          |0.9316600714093861 |0.99       |0.94                |0.91        |Easy Ensemble Classifier performs better than the rest.|


## Code Snippets 

- Feature and Target Creation<br>
![Feature and Target Creation](/Resources/credit_risk_feature_target_creation.png)<br>

- Training and Test Split Dataset<br>
![Training and Test Split Dataset](/Resources/credit_risk_split_train_test_sets.png)<br>

- Naive Oversampling<br>
![Naive Oversampling](/Resources/credit_risk_random_oversampling_logisticRegression.png)<br>

- SMOTE Oversampling<br>
![SMOTE Oversampling](/Resources/credit_risk_smote_oversampling.png)<br>

- Imbalance Classification Report<br>
![Imbalance Classification Report](/Resources/credit_risk_imbalance_classification_report.png)<br>

- Balanced Random forest Classifier<br>
![Balanced Random forest Classifier](/Resources/credit_risk_ensemble_random_forest_classifier.png)<br>

- Confusion Matrix and Accuracy Score<br>
![Confusion Matrix and Accuracy Score](/Resources/credit_risk_ensemble_random_forest_classifier.png)<br>

- Combination (Over and Under) Sampling<br>
![Combination (Over and Under) Sampling](/Resources/credit_risk_combination_sampling.png)<br>

- Easy Ensemble AdaBoost Classifier<br>
![Easy Ensemble AdaBoost Classifier](/Resources/credit_risk_easy_ensemble_adaboost_classifier.png)<br>


# Summary
The analysis done by Jill and her colleague for LendingClub find that there is unbalanced classification between the good loans and risky loads. 
While the good loans easily outnumber the risky loans you will need to train and evaluate different models to solve this kind of unbalanced classes.
Jill and her team deploy different modeling techniques including oversampling using RandomOverSample and SMOTE algorithms, undersampling using the ClusterCentroids algorithm as well as combined method of (over and under) sampling using teh SMOTEENN algorithm. Then two machine learning models BalancedRandomForestClassifier and EasyEnsembleClassifier are compared in order to reduce bias and predict credit risk. Finally, different models are evaluated and the best performing model is selected.


## Links to images

Feature and Target Creation: [credit_risk_feature_target_creation.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_combination_sampling.png?raw=true)<br>

Training and Test Split Dataset: [credit_risk_split_train_test_sets.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_split_train_test_sets.png?raw=true)<br>

Naive Oversampling: [credit_risk_random_oversampling_logisticRegression.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_random_oversampling_logisticRegression.png?raw=true)<br>

SMOTE Oversampling: [credit_risk_smote_oversampling.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_smote_oversampling.png?raw=true)<br>

Imbalance Classification Report: [credit_risk_imbalance_classification_report.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_imbalance_classification_report.png?raw=true)<br>

Balanced Random forest Classifier: [credit_risk_ensemble_random_forest_classifier.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_ensemble_random_forest_classifier.png?raw=true)<br>

Confusion Matrix and Accuracy Score: [credit_risk_ensemble_random_forest_classifier.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_ensemble_random_forest_classifier.png?raw=true)<br>

Combination (Over and Under) Sampling: [credit_risk_combination_sampling.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_combination_sampling.png?raw=true)<br>

Easy Ensemble AdaBoost Classifier: [credit_risk_easy_ensemble_adaboost_classifier.png](https://github.com/bariir/Credit_Risk_Analysis/blob/main/Resources/credit_risk_easy_ensemble_adaboost_classifier.png?raw=true)<br>

