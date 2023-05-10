# Fraud_transaction_detection
Its a project on a big dataset to detect whether a transaction is fraud or not.ALso it is a heavily imbalanced dataset.

Dataset link : https://drive.google.com/uc?export=download&confirm=6gh6&id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV

This case requires trainees to develop a model for predicting fraudulent transactions for a
financial company and use insights from the model to develop an actionable plan. Data for the
case is available in CSV format having 6362620 rows and 10 columns.

1. Importing required libraries
2. Cleaning dataset

Cleaning missing value,duplicate,null values and data types
3.Exploratory data analysis
Target variable analysis
![target](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/bdc5cc02-4c16-41be-bbed-bedde654e3e1)


Univariate analysis
![cat univariate](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/637bfc2e-c399-491e-9d65-74c2ce0207b0)

![num](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/882fcd0f-7245-4f00-b3eb-144cda9ba1a9)

Bivariate analysis

![cat vs target](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/8f20f5a2-2ddd-4b22-a0af-3f7996091475)

Correlation of data
![corre](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/411a2c02-944c-44fa-a1d9-7d0d3722a85d)

Outlier detection
Boxplot
![boxplot](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/721b43e0-c6c4-4df3-812d-c65b34a2a99d)
IQR
![iqr](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/6613e161-84d4-412e-9e16-e0c1fc983a01)

4.Encoding data
![encode](https://github.com/Thiruvenkatam007/Fraud_transaction_detection/assets/113424127/1953aa22-9252-4002-834b-d25905923bb9)

5.Train test split
6.Scaling data
7.Models
Logistic regression,random forest,xg-boost

8.Final model
XG-Boost

AUROC Plot
roc

Feature importance
feat_importance ance

Conclusion
XG_boost outperformed all the other models with the highest AUROC score of 0.9241
This implies that XG-boost is suitable to predict whether the client will subcribe to the insurance or not.
