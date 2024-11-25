# Machine Learning Project 1

This was the kickoff project to machine learning. The purpose of this project was to help a mobile carrier determine which of its newer plans it should suggest to legacy customers. 

## Data Description

Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 

сalls — number of calls,

minutes — total call duration in minutes,

messages — number of text messages,

mb_used — Internet traffic used in MB,

is_ultra — plan for the current month (Ultra - 1, Smart - 0)

## The Process 

We split our data into a 60/20/20 set for training, validation, and testing respectively. We looked at logistic regression, decision tree, and random forest models. Our random forest and decision tree models performed very similarly, but decision tree was the best choice in the end, scoring the highest accuracy. We also sanity checked our model by comparing it to a dummy model which simply guessed the most frequent value in our target. 

If you would like to see more about how I attained my results in this project, please open the attached Jupyter Notebook.
