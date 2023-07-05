---
layout: post
title:  "Logistic Regression Explained"
date:   2023-06-29 23:34:56 +0530
categories: Algorithms
---
Logistic regression is a classification algorithm. The idea of logistic regression is to find the relationship between features and the probability of a particular outcome.  

*It predicts a binary outcome based on a set of independent variables. A binary outcome is one where there are only two possible scenarios. Independent variables are those variables or factors which may influence the outcome.*

> TL;DR - This algorithm can be used to classify data into two categories or scenarios. Like Predicting whether a student passes or fails, whether a person survives an accident or not. The output can either be yes or no (2 outputs).

## What are independent variables?

The independent variables fall into any of the following categories:

* **Continous**
In technical terms, continuous data is categorized as either **interval data** where the intervals between each value are equally split, or **ratio data**, where the intervals are equally split and there is a true or meaningful “zero”.

> For example, the temperature in degrees Celsius would be classified as interval data; the difference between 10 and 11 degrees C is equal to the difference between 30 and 31 degrees C, but there is no true zero—a temperature of zero degrees does not mean there is “no temperature”.

* **Discrete, Ordinal**
The data that can be placed into some kind of order on a scale.
>For example, if you are asked to state how happy you are on a scale of 1-5, the points on the scale represent ordinal data. A score of 1 indicates a lower degree of happiness than a score of 5, but there is no way of determining the numerical value between each of the points on the scale. Ordinal data is the kind of data you might get from a customer satisfaction survey.

* **Discrete, Nominal**
The data which fits into named groups which do not represent any kind of order or scale.
> For example, eye colour may fit into the categories “black”, “brown”, or “green”, but there is no hierarchy to these categories.

## References

* https://www.youtube.com/watch?v=yIYKR4sgzI8
* https://careerfoundry.com/en/blog/data-analytics/what-is-logistic-regression/

For more mathematical aspects:

 * https://www.analyticsvidhya.com/blog/2021/08/conceptual-understanding-of-logistic-regression-for-data-science-beginners/
* https://medium.com/data-science-group-iitr/logistic-regression-simplified-9b4efe801389
* https://towardsdatascience.com/logistic-regression-explained-9ee73cede081