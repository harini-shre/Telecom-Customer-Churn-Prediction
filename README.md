# Telecom Customer Churn Prediction

### What is Churn?

Churn denotes that an existing customer is terminating his/her services with the organization and moving out.

### Why is Churn Important?
The objective of a business is to
* bring new customers
* retain existing customers

If the existing customer leaves the organization, then it is a loss to the company and also creates a bad reputation for the company. To avoid this it is essential to retain the existing customers.

The Churn Prediction helps in Identifying/Predicting which all customers are about to terminate the company services. This will help the organization in communicating with customers who are about to churn and take necessary steps to retain them.

It also helps in identifying the areas of dissatisfaction of customers, and thus the organization can work on improving the areas which in turn help in better retainment of customers.

### Dataset

The dataset is a fictional dataset of customer churn from the telecom industry. The dataset is obtained from Kaggle, which stems from the IBM sample set collection: https://www.kaggle.com/blastchar/telco-customer-churn

### Objective
The objective is to build a model that predicts if a customer will churn or not using Python.

### Machine Learning Approaches Used
* Logistic Regression
* LinearSVC
* Kernal SVC
* KNN
* Random Forest
* Adaboost

### Model Evaluation Metric
The dataset is *imbalanced*, so accuracy is not a suitable metric in this case. Our main objective is to find all the customers who churn (ie) True Positive.

True Positive is more important. In this case, the False Negative ( Actually Churn but Predicted as Not Churn) is more costly(important) than False Positive. *So the metric chosen is **F2-Score**.*

### Output:
The **Logistic Regression** model is finalized as it has obtained the highest **F2-Score of 57.30%**.
This model has obtained an **accuracy of 80.64%**.