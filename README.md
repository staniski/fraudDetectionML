# fraudDetectionML
This is a university final year prokect trying to identify fraudelent transactions using supervised and unsupervised machine learning.
That dataset is taken from https://www.kaggle.com/c/ieee-fraud-detection

#Supervised 
CatBoost, XGBoost, LightGBM
Bets score -> CatBoost with 97% roc curve score on test data using categorial features.
Best speed -> LightGBM.

#Unsupervised 
DBSCAN, KNearestNeighbour, PCA
All of the unsupervised methods returned lower than 50% althought DBSCAN showed potential when increasing eps and min_samples.
PCA and DBSCAN were used in conjunction with KNearestNeighbour.

#Optimization 
Bayesian optimization technique using Optuna library as it was a more efficient way of finding best parameters.


