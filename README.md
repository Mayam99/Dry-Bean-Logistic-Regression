# Dry-Bean-Logistic-Regression

Introduction

In this notebook, we will be working on the Dry Bean Dataset from Kaggle, which involves the classification of different types of dry beans. The dataset contains various physical properties of the beans, and our goal is to build a model that can accurately classify the type of bean based on these properties.

Dataset Overview

The Dry Bean Dataset consists of 13,611 instances and 17 features, including:

Area

Perimeter

Major Axis Length

Minor Axis Length

Aspect Ratio

Eccentricity

Convex Area

Equivalent Diameter

Extent

Solidity

Roundness

Compactness

Shape Factor 1

Shape Factor 2

Shape Factor 3

Shape Factor 4

Class (the type of bean, which is the target variable)

The dataset contains the following bean types:

Seker

Barbunya

Bombay

Cali

Dermason

Horoz

Sira

Objective

Our primary objective is to develop a logistic regression model to classify the type of bean based on its physical properties. Logistic regression is a popular and straightforward method for classification problems, particularly when the target variable is categorical.

Steps Involved

1) Data Exploration and Preprocessing: We'll start by loading the dataset, exploring its structure, and performing necessary preprocessing steps such as handling missing values, normalizing features, and encoding categorical variables.

2) Model Building: Next, we'll build a logistic regression model using the preprocessed data.

3) Model Evaluation: We'll evaluate the performance of our model using appropriate metrics such as accuracy, precision, recall, and the F1 score.

4) Model Optimization: Finally, we'll explore ways to optimize our model, potentially using techniques like hyperparameter tuning and cross-validation.

By the end of this notebook, we aim to have a robust logistic regression model capable of accurately classifying the different types of dry beans in the dataset.
