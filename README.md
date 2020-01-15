# Reddit Comments Classification

## Abstract
The task at hand for this project was to build a classifier for reddit comments from 20 subreddits, ie 20
classes. Different models were tested such as Logistic Regression, Multinomial Naive Bayes, and Support Vector Machines from
the sklearn library. The Bernouilli Naive Bayes Model was also implemented from scratch but did not offer the best accuracy.
Some findings were in the importance of task-specific text pre-processing combined with tfidf vectorization. The training data
for this project was composed of 70000 reddit comments with their respective id’s and corresponding subreddits. The test data,
with no corresponding subreddits, was made up of 30000 reddit comments.
This project was also part of a Kaggle Competition on which our team’s best accuracy came out to 58.55%. This was achieved
using a Multiple Layer Perceptron model with a single hidden layer.

## Kaggle Competition: 
https://www.kaggle.com/c/reddit-comment-classification-comp-551/
