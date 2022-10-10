# Credit_Risk_Analysis


Purpose:

The goal of this project is to use machine learning in roder to assess the credit card risk and resolve the inherent unbalanced classification problem as good loans outnumber risk loans.
Therefore, it's important to train and evaluate different models with unbalanced classes and choose best performing ones.

## Tools and Software: 
- Anaconda, Jupyter Notebooks, Numpy, Pandas, scipy, Scikit-learn, etc. as well as Git Bash to commit changes into GitHub Repository.


# Results
Jill's goal is to analyze different machine learning algorithms and models in order to assess the credit risk unbalanced classification and therefore, best select the high performing model or combination of models.<br>
- Here are an overall matrix that contains balanced accuracy scores, precision, recall scores, and F1 scores of all six machine learning models. <br>


| Models                           | Accuracy Score    | Precision |Recall(Sensitivity) | F1 score | Best Performance        |
|:---------------------------------|:------------------|:----------|:-------------------|:---------|:------------------------|
|Oversampling:                     |                   |           |                    |          |                         | 
|Naïve random oversampling         |0.6573009382322703 |0.99       |0.60                |0.75      |                         |
|SMOTE                             |0.6622479600626106 |0.99       |0.69                |0.81      |SMOTE performs better.   |
|                                  |                   |           |                    |          |                         |
|Undersampling:                    |                   |           |                    |          |                         |
|Cluster Centroids                 |0.5447339051023905 |0.99       |0.40                |0.56      |                         |
|                                  |                   |           |                    |          |                         |
|Combined:                         |                   |           |                    |          |                         |
|SMOTEENN                          |0.639224858524206  |0.99       |0.58                |0.73      |                         |                
|                                  |                   |           |                    |          |                         |
|Ensemble:                         |                   |           |                    |          |                         |
|Balanced Random Forest Classifier |0.7885466545953005 |0.99       |0.87                |0.93      |                         |
|Easy Ensemble Classifier          |0.9316600714093861 |0.99       |0.94                |0.91      |Easy Ensemble Classifier  
performs better than the rest.|
