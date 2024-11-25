# Final Project

This project would be the final summation of all the projects I had taken in the TripleTen program. A telecom operator is looking to forecast churn of their clients. My task is to help them predict churn with machine learning. 

## Data Description

contract.csv — contract information

personal.csv — the client's personal data

internet.csv — information about Internet services

phone.csv — information about telephone services

In each file, the column customerID contains a unique code assigned to each client.

## The Process

I would use several libraries and utilize many lessons I had learned in this project. I used sklearn modules, pandas and numPy, matplotlib, and tools such as GridSearchCV for hyperparameter tuning. I utilized several skills in processing the data, such as merging data, filling in missing data based on distribution, creating visualizations, and engineering new features by extracting from datetime columns. One-hot encoding and scaling would be used to prepare the data for model training. Many models were tested including random forest, LightGBM, and KNN. Our tuned LightGBM model gave us the best results based on our grading metric of ROC-AUC score.

This project certainly had a ton of substance, and all of it can be looked at by opening the Jupyter Notebook attached.
