# Applied Machine Learning in Python

This repository contains the topics that were taught in the coursera course [Applied Machine Learning in Python](https://www.coursera.org/learn/python-machine-learning), it contains the assignments as well. These topics and assignments are gathered into different directories, according to weekly aims. The datasets used in the course are located in the Datasets directory of every week. Then each weekly aim is:

## First Week: Fundamentals of Machine Learning - Introduction to Scikit-Learn
This module introduces basic machine learning concepts, tasks, and workflow using an example classification problem based on the K-nearest neighbors method, and implemented using the scikit-learn library. So in the [first Assignment](https://github.com/jpradas1/Applied_Machine-Learning_Python/blob/master/Week_1/Assignment_1.ipynb), in order to implement the K-nearest neighbors model in a real problem, the dataset of breast cancer is trained and tested, where the scores measured, for predicting whether or not the diagnosis is malignant, are shown by the following figure

<img src="./.assets/assignment1.png" width="500">

## Second Week: Supervised Machine Learning
This module delves into a wider variety of supervised learning methods for both classification and regression, learning about the connection between model complexity and generalization performance, the importance of proper feature scaling, and how to control model complexity by applying techniques like regularization to avoid overfitting. In addition to k-nearest neighbors, this week covers linear regression (least-squares, ridge, lasso, and polynomial regression), logistic regression, support vector machines, the use of cross-validation for model evaluation, and decision trees. So for [the assignment](https://github.com/jpradas1/Applied_Machine-Learning_Python/blob/master/Week_2/Assignment_2.ipynb) of this week multiple machine learning model has been fitted, for instance, the following figures shows the classification made by a desicion tree for [UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom?ref=datanews.io), the second figure displays the performance of a Suported Vector Machine (SVC) over a range of one of its hyperparameter 'alpha', it helps to understand what is the optimal configuration for this model.

<img src="./.assets/assignment2_1.png" width="500">
<img src="./.assets/assignment2_2.png" width="500">

## Third Week: Evaluation
This module covers evaluation and model selection methods that it can be used to help understand and optimize the performance of your machine learning models. It is in [this module](https://github.com/jpradas1/Applied_Machine-Learning_Python/blob/master/Week_3/Assignment_3.ipynb) where concepts as **Confusion Matrix**, **Accurracy**, **Recall**, **AUC** and so forth, get importance.

<img src="./.assets/assignment3.png" width="500">

## Fourth Week: Unsupervised and Supervised Machine Learning
This module covers more advanced supervised learning methods that include ensembles of trees (random forests, gradient boosted trees), and neural networks (with an optional summary on deep learning). It learns about the critical problem of data leakage in machine learning and how to detect and avoid it. This [fnal assignment has a special goal, because it seek to predict how interesting or "engaging" it is for viewers distinct educational videos
