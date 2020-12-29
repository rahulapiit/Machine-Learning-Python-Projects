
# Telecom Churn 
![enter image description here](https://github.com/rahulapiit/Machine-Learning-Python-Projects/blob/main/Telecom%20Churn/customerchurn.jpg?raw=true)

In this project, analysis of customer-level data of a leading telecom firm has been performed to build a predictive model to identify customers at high risk of churn and identify the main indicators of churn.

Dimensionality reduction technique such as PCA has been performed with various classification based models such as Logistic Regression, Random Forest and SVM. 

Since the rate of churn is typically low (about 5-10%, this is called class-imbalance) - Kfold techniques have been used to handle class imbalance.

Hyperparameter Tuning have been performed using Random Forest, XGBOOST and SVM to increase the recall thus trying to reduce churn of the high-value customers, which will help to reduce significant revenue leakage.

The dataset contains customer-level information for a span of four consecutive months - June, July, August and September. The months are encoded as 6, 7, 8 and 9, respectively.

The  **business objective** is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. To do this task well, understanding the typical customer behaviour was done during churn.

To checkout my notebook, please click [here](https://github.com/rahulapiit/Machine-Learning-Python-Projects/blob/main/Telecom%20Churn/Telecom_Churn.ipynb)
