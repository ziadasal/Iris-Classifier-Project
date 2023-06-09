# IRIS Flower Classification

![IRIS Flower](https://miro.medium.com/max/875/1*7bnLKsChXq94QjtAiRn40w.png)

## About

This repository contains the Iris Plants Database, which is a well-known dataset in the pattern recognition literature. The dataset consists of measurements of various attributes of Iris plants, with the goal of classifying them into three different species: Iris Setosa, Iris Versicolour, and Iris Virginica.

The dataset was created by R.A. Fisher and donated by Michael Marshall in July 1988.

## Past Usage

The Iris Plants Database has been widely used in various publications related to pattern classification and machine learning. Some notable references include:

1. Fisher, R.A. "The use of multiple measurements in taxonomic problems" (1936)
2. Duda, R.O., & Hart, P.E. "Pattern Classification and Scene Analysis" (1973)
3. Dasarathy, B.V. "Nosing Around the Neighborhood: A New System Structure and Classification Rule for Recognition in Partially Exposed Environments" (1980)
4. Gates, G.W. "The Reduced Nearest Neighbor Rule" (1972)
5. Cheeseman et al. "AUTOCLASS II conceptual clustering system" (1988 MLC Proceedings)

These publications have demonstrated the effectiveness of various classification algorithms on this dataset, achieving low misclassification rates.

## Dataset Information

The Iris Plants Database consists of 150 instances, with 50 instances for each of the three classes. The dataset contains the following attributes:

1. Sepal length (in cm)
2. Sepal width (in cm)
3. Petal length (in cm)
4. Petal width (in cm)

The predicted attribute is the class of the Iris plant, which can be one of the following:

- Iris Setosa
- Iris Versicolour
- Iris Virginica

The dataset is relatively simple, but it presents challenges as two of the classes are not linearly separable from each other. There are no missing attribute values in the dataset.

## Summary Statistics

Here are some summary statistics for the dataset:

| Attribute     | Min  | Max  | Mean | SD   | Class Correlation |
|---------------|------|------|------|------|-------------------|
| Sepal length  | 4.3  | 7.9  | 5.84 | 0.83 | 0.7826            |
| Sepal width   | 2.0  | 4.4  | 3.05 | 0.43 | -0.4194           |
| Petal length  | 1.0  | 6.9  | 3.76 | 1.76 | 0.9490 (high!)    |
| Petal width   | 0.1  | 2.5  | 1.20 | 0.76 | 0.9565 (high!)    |

## Classification Models

In this repository, we have implemented five different classification models to classify the Iris flowers. The models used are:

1. Logistic Regression
2. K-Nearest Neighbors
3. Support Vector Machine
4. Decision Tree
5. Random Forest

We compare the accuracy of each model to determine their performance on the Iris dataset.

## Conclusion

Since the Iris dataset is small, all the models achieve high accuracy in classification. Therefore, any of these models can be used for prediction purposes.
