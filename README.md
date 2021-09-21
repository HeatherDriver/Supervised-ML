# Supervised-ML

This folder contains my submission for the Udacity Intro to Machine Learning with PyTorch's Project, which was using supervised ML for Finding Donors for CharityML.

In this project, I looked at several supervised algorithms to model individuals' income using data collected from the 1994 U.S. Census. I then chose the best algorithm and looked at how to optimise this algorithm to best model the data. While I evaluated 5 models (only 3 are shown as required), the best algorithm for the task was Gradient Boosting, which performed better than AdaBoost and substantially better than Naive Bayes and Logistic Regression. I also looked at SVM but the training time was prohibitively long, for lower accuracy and precision. 

The goal was to construct a model that accurately predicts whether an individual makes more than $50,000 - the final model was able to do this with 87% accuracy and 75% precision (F-score with beta at 0.5).
