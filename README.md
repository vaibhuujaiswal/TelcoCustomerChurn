# TelcoCustomerChurn

This is taken from the kaggle competition : https://www.kaggle.com/datasets/blastchar/telco-customer-churn

I have preprocessed the data and answered the questions : 

Perform Exploratory Data Analysis:
The first step is to perform exploratory data analysis on the dataset. 
1. Give basic data overview, all stats, data distribution, label distribution and other
metrics. (Done in EDA File)
2. What are the most popular products by ranking ? (Done in EDA Question 2 to 6)
3. Are there any products/plans that are often purchased together ? If so, then what
are the chances of those products being purchased together and separately ?
4. Can you cluster customers, based on their purchasing preferences ? Could you list
the outliers in this cluster if any ?
5. Is there any clear correlation between certain customer types and the types of plan
they prefer to purchase ? If so, list those correlations.
6. Can you use any dimensionality reduction technique to reduce features ? Also could
you visualize the entire data as cluster points in a 2 dimensional graph.

Build a Model to predict churn of a customer:
We trained the model on the training set. Once the model is trained we
evaluate it on a held-out test set using metrics such as, Accuracy, AUROC and F1 score.
Also show the confusion matrix. 
1. Built machine/deep learning model like Naive Bayes (Multinomial and Gaussian), SVM, Logistic Regression (Best Performance)  to predict whether a customer will churn or
not.

2. built a simple recommender system based on apriori customer features to suggest which plan or plan type will best suit a customer from the test set, given if
they were to be a new customer with no prior purchases or history of transaction. - use this to write a readme for github repository containing the solution
