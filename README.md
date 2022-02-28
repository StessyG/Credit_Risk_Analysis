# Credit_Risk_Analysis
# Overview of the analysis:

The purpose of this analysis is to use supervised machine learning algorithms to predict credit card risk. The company believes that machine learning will provide a quicker and more reliable loan experience. Several techniques(imbalanced-learn, scikit-learn, RandomOverSampler, SMOTE algorithms, ClusterCentroids algorithm, SMOTEENN algorithm, BalancedRandomForestClassifier, and EasyEnsembleClassifier) were used in this analysis to train and evaluate models with unbalanced classes.

# Results:
The results for the six machine learning models including their respective balanced accuracy score, precision, and recall scores are as shown below: 

1. Naive Random Oversampling

Balanced accuracy score: 0.640324421824783
Precision: low for high-risk(0.01) and high for low-risk(1.00)
Recall: 0.66 for high-risk and 0.62 for low-risk

2. SMOTE Oversampling

Balanced accuracy score: 0.6514992150524688
Precision: low for high-risk(0.01) and high for low-risk(1.00)
Recall: 0.61 for high-risk and 0.69 for low-risk

3. Cluster Centroids Algorithm

Balanced accuracy score: 0.5447046721744204
Precision: low for high-risk(0.01) and high for low-risk(1.00)
Recall: 0.69 for high-risk and 0.40 for low-risk

4. SMOTEENN Algorithm

Balanced accuracy score: 0.6550612907408608
Precision: low for high-risk(0.01) and high for low-risk(1.00)
Recall: 0.75 for high-risk and 0.56 for low-risk

5. Balanced Random Forest Classifier

Balanced accuracy score: 0.7885466545953005
Precision: low for high-risk(0.03) and high for low-risk(1.00)
Recall: 0.70 for high-risk and 0.87 for low-risk

6. Easy Ensemble AdaBoost Classifier

Balanced accuracy score: 0.9316600714093861
Precision: 0.09 for high-risk and 1.00 low-risk
Recall: 0.94 for high-risk and 0.92 for low-risk

# Summary: 

Based on the performance of all six models, the Easy Ensemble AdaBoost Classifier model is the best model to chosse in this scenario. While the other models' balanced accuracy score is below 0.80, the Easy Ensemble AdaBoost Classifier model has a score of 0.93. All the models have a similar precision ranging from 0.01 to 0.09 for high-risk and 1.00 for low-risk. The Easy Ensemble AdaBoost Classifier model is also the best model to choose for its highest recall high-risk/low-risk of 0.94/0.92.