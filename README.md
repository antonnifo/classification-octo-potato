## classification-octo-potato  
### Overview
Predicting a qualitative response for an observation can be referred to as classifying that observation, since it involves
assigning the observation to a category, or class.Just as in the regression setting, in the classification setting we have a
set of training observations *(x 1 , y 1 ), . . . , (x n , y n )* that we can use to build
a classifier. We want our classifier to perform well not only on the training
data, but also on test observations that were not used to train the classifier.Some examples of classification problems include: 
1. A person arrives at the emergency room with a set of symptoms
that could possibly be attributed to one of three medical conditions.
Which of the three conditions does the individual have?
1. An online banking service must be able to determine whether or not
a transaction being performed on the site is fraudulent, on the basis
of the user’s IP address, past transaction history, and so forth.
1. On the basis of DNA sequence data for a number of patients with
and without a given disease, a biologist would like to figure out which
DNA mutations are deleterious (disease-causing) and which are not.

### logistic regression projects 
**Titanic: Machine Learning from Disaster** is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so I am. This is a binary classification problem: based on information about Titanic passengers we predict whether they survived or not. General description and data are available on [Kaggle](https://www.kaggle.com/c/titanic). Titanic dataset provides interesting opportunities for feature engineering.  
[Nb viewer](https://nbviewer.jupyter.org/github/antonnifo/classification-octo-potato/blob/master/logistic%20regression/kernel-titanic.ipynb)  
### KNearest Neighbour  
classified data set from a company! They've hidden the feature column names but have given you the data and the target classes.
We'll try to use KNN to create a model that directly predicts a class for a new data point based off of the features.
[Nb viewer](https://nbviewer.jupyter.org/github/antonnifo/classification-octo-potato/blob/master/K-nearest%20neighbors/K%20Nearest%20Neighbors%20with%20Python.ipynb)
