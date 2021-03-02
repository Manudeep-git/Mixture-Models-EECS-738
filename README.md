# Mixture-Models-EECS-738

Probably Interesting Data

Goal: To develop a mixture model for modelling data from 2 different datasets without using any extensive python libraries such as scikit-learn

## Problem Statement

1. Set up a new git repository in your GitHub account
2. Pick two datasets from https://www.kaggle.com/uciml/datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to model distributions within the dataset
5. Build a heuristic and/or algorithm to model the data using mixture models of probability distributions programmatically
6. Document your process and results

## DataSets

1.Glass_Classification:

  * Prediction of the Glass types using the features
  * Principle component analysis of glass and feature importance
  
2.Adult_Census:
* The prediction task is to determine whether a person makes over $50K a year.

## Approach

## Dataset1

Gaussian Mixture models using was  attempted to be developed using simple probability and distance functions and then utilizing Expectation-Maximization concept. The number of initial clusters(2) were pre-assumed for this assignment. The algorithm initially assumes parameters of the model and then maximizes them by applying to a function. Afterwards, it uses the updated maximised parameters and continue the cycle untill convergence. This approach was applied one of the datasets 

## Dataset2

K-Means was used for the second dataset to see how it works internally. Main focus was on age vs capital gains. K-means in this approach demonstrates a clump of indivduals who reported exceptionally high capital gains. This group likely reached the maximum allowed by the census, which is how their cluster ended up being so close together. K-Means approach did well and clusters are seperated successfully.

## References
https://towardsdatascience.com/expectation-maximization-algorithm-explained-ffaf0655357e<br>
https://machinelearningmastery.com/expectation-maximization-em-algorithm/<br>
https://www.geeksforgeeks.org/ml-expectation-maximization-algorithm/