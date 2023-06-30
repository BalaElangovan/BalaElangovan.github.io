---
layout: post
title:  "Intro to Classification Algorithms"
date:   2023-06-29 23:34:56 +0530
categories: Algorithms
---
Classification is recognizing, understanding and grouping objects or data into preset categories. Classification is a type of **Supervised Learning** as machine learning programs learns from pre-categorized datasets and use various algorithms to classify unknown datasets into categories.
Classification algorithms take a pre-categorized dataset as training datasets and train the model to categorize the likelihood of subsequent data into their respective categories.

> Tl; DR - Classification is a form of "Pattern recognition", with classification algorithms applied to training datasets to find the same pattern in future sets of data.

## Types Of Classification Tasks in Machine Learning

1. **Binary Classification**

As the name suggests, Binary classification is a simple type of classification. The goal is to classify the input data into two mutually exclusive categories. The training datasets will be labelled in such a format.

> Examples - 0 and 1; true or false; positive and negative.

2. **Multi-Class Classification**

The multi-class classification has at least two mutually exclusive class labels and the goal is to predict which class a given input belongs to. Most of the binary classification algorithms can be used for this classification.

> Example - Classifying vegetables like carrots, potatoes and tomatoes.


3. **Multi-Label Classification**

In multi-label classification, there is no mutual exclusion as the datasets can have more than one label for the input example. We can use binary classification or multi-class classification algorithms to perform multi-label classification. However, multi-label classification has specialized algorithms like **Multi-label Decision Trees, Multi-label Gradient Boosting, Multi-label Random Forest** etc.

> Example - Categorising our shopping into categories. The different categories are Shopping, Groceries, Transport, Eating out, Subscriptions, Rent etc.

4. **Imbalanced Classification**

As the name suggests, the data is unevenly distributed in each class, meaning one class will have more data than others in the training datasets. In this situation, We can't use conventional predictive models like decision trees, or logistic regression as they might be biased towards the class with a high number of observations.

the most commonly used approaches are Sampling techniques and Cost-sensitive techniques. These techniques aim to balance the distributions.

> Example - Consider the training data with 80% carrots, 15% potatoes and 5% tomatoes. The conventional models might be biased towards carrots.

## Some Popular Classification Algorithms in Machine Learning (Explained in brief in another blog)

1. Logistic Regression

2. Naive Bayes Classification

3. K-Nearest Neighbours

4. Decision Tree

5. Support Vector Machines

## Refernces

* https://towardsdatascience.com/top-machine-learning-algorithms-for-classification-2197870ff501
* https://monkeylearn.com/blog/classification-algorithms/
* https://builtin.com/data-science/supervised-machine-learning-classification
