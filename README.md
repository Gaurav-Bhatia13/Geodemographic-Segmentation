# Geodemographic-Segmentation
Classification model built on Churn Modelling data set that contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer left the bank (closed his account) or he continues to be a customer.
The dataset used for the project is taken from kaggle webiste.
https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling
The Dataset contains independent features including - Customer Id, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, Number Of Products, Has Credit Card, IsActiveMember, EstimatedSalary, Exited.
The dependent feature is Exited.
The classification model predicts the outcome wether the customer will stay or exit the bank based on these input features.
Model also estimates probability score of customer to stay connected with the bank, such that bank can use its own threshold to classify its critical customers.
The usecase of the model is to provide more focus on such customers that are at high risk of exiting the bank.
I have used Artificial Neural Netwroks for the project and achieved an accuracy score of 85.05%.
