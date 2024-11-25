# Supervised Learning Project

This was a fun project which was centered on supervised learning. The objective was to help a bank predict which customers would leave soon by creating a predictive model.

## Data Description

__Features__

RowNumber — data string index
CustomerId — unique customer identifier
Surname — surname
CreditScore — credit score
Geography — country of residence
Gender — gender
Age — age
Tenure — period of maturation for a customer’s fixed deposit (years)
Balance — account balance
NumOfProducts — number of banking products used by the customer
HasCrCard — customer has a credit card
IsActiveMember — customer’s activeness
EstimatedSalary — estimated salary

__Target__
Exited — сustomer has left

## The Process

This project would feature data with an imbalance of classes. After determining that our data was imbalanced, we would scale our data so that we would be able to more optimally train our model. We trained logistic regression, decision tree, and random forest models. The random forest model was tuned to find the optimal parameters. It passed verification on our final test set with F1 score as our metric, and further validated with a plot of its ROC curve.
