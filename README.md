# Churn Prediction Project
This project aims to predict customer churn using machine learning. Customer churn is the loss of customers over time, 
and it is a major challenge for businesses of all sizes. By predicting churn, businesses can identify and target customers 
who are at risk of leaving, and implement strategies to retain them.

# Data Preparation
The first step in any machine learning project is to prepare the data. In this project, the data was prepared as follows:
- Label Encoding: A label encoder was used to transform the categorical columns into numerical values. This is necessary because machine learning models can only process numerical data.
- Outlier Removal: Outliers and white noise were removed from the data using the interquartile range (IQR) method. Outliers can skew the results of machine learning models, so it is important to remove them before training a model.
- Oversampling: The data was oversampled to address the class imbalance problem. Class imbalance is a situation where there are significantly more data points in one class than in another class. In this project, there were more churned customers than non-churned customers. To address this, the minority class (non-churned customers) was oversampled using the SMOTE algorithm.

# Model Training and Evaluation
Once the data was prepared, a variety of machine learning models were trained and evaluated. The following models were evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting Machine
- XGBoost

The XGBoost model achieved the best performance, with an AUC score of 0.82. AUC is a measure of the performance of a binary classifier, and it ranges from 0 to 1.
A score of 0.5 indicates that the model is performing no better than random guessing, while a score of 1 indicates that the model is performing perfectly.

# Conclusion
This project has demonstrated that machine learning can be used to effectively predict customer churn. 
The XGBoost model achieved an AUC score of 0.82, which indicates that it can be used to reliably identify customers who are at risk of churning.

# Description
In today's competitive business landscape, customer retention is more important than ever. 
By accurately predicting which customers are at risk of churning, businesses can take proactive steps to retain them. 
This project has developed a machine learning model that can predict customer churn with an accuracy of 82%. 
This model can be used by businesses to identify and target customers who are at risk of leaving, and implement strategies to keep them coming back.
