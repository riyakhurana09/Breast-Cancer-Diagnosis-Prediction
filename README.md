# Breast-Cancer-Diagnosis-Prediction
Prediction of breast cancer diagnosis as benign or malign, based on real-valued features computed for each cell nucleus.

Dataset: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

This dataset has 569 observations with a class distribution of 357 benign (B) and 212 malignant (M) cases. There is a total of 32 attributes including ID, Diagnosis (target variable) and the mean, standard error, and largest mean of the ten real-valued features which were computed for each image, resulting in 30 features.

For this binary classification, I explored the model performance of Decision Tree, KNN, Logistic Regression and SVM model for different parameter values to predict the result of the diagnosis based on the above-mentioned features. I used Recall as my scoring metric as I want to reduce False Negatives for malignant class, hence, focus on accurately predicting all the people who have malignant cancer.

Best Performing Model: Logistic Regression (Recall – 0.929)

