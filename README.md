# Iris Dataset Analysis

This repository contains Python code for a supervised machine learning model that learns from the measurements of irises with known species and predicts the species for new irises.

## Overview

The Iris dataset is a well-known dataset in the field of machine learning and pattern recognition. It consists of 150 samples of iris flowers from three different species: Setosa, Versicolor, and Virginica. For each sample, four features are measured: sepal length, sepal width, petal length, and petal width. The goal of this analysis is to build a machine learning model that can predict the species of an iris flower based on its measurements.

## Code Description

The code in this repository performs the following tasks:

1. Loads the Iris dataset using scikit-learn's `load_iris` function and explores its structure.

2. Splits the dataset into training and testing sets using the `train_test_split` function.

3. Creates a scatter matrix of the dataset to visualize the relationships between features.

4. Builds a k-nearest neighbors (KNN) classifier using scikit-learn's `KNeighborsClassifier` and fits it to the training data.

5. Makes predictions on new data points using the trained KNN classifier.

6. Evaluates the performance of the model on the test set, computing the accuracy score.

# References

Müller, A.C., & Guido, S. "Introduction to Machine Learning with Python" (Book Reference)

## Usage

To run the code, make sure you have Python and the required libraries installed. You can install the necessary libraries using pip:

```bash
pip install scikit-learn numpy pandas matplotlib







