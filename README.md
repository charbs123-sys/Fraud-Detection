# Fraud-Detection

This project relates to the synthetic dataset found at https://www.kaggle.com/datasets/kartik2112/fraud-detection/data. Significant EDA is performed to determine how appropriate features are, any trends we observe in the data and what we expect the model to produce. A number of models including, but not limited to, XGBoost, Logistic regression SVM and a number of Neural Network architectures were considered.

Note the most significant challenge of this dataset was class imbalance which was resolve using undersampling techniques such as Random Under-Sampling, Oversampling techniques (SMOTE) along with Robust Scaler to ensure appropriate normalization of results.

Overall, I found that XGBoost performed best in terms of speed and had reasonable recall, the FeedForward Neural Network was slower however had the best recall when implementing SMOTE during cross validation so as to not artifically modify the validation set.
