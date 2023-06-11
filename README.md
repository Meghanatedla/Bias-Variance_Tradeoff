 ---
# Bias<sup>2</sup> - Variance Tradeoff

## _Calculating Bias and Variance_
---
The goal was to analyze the risk factor of employees in a multinational corporation who were laid off or retained. Two datasets were provided: a `training set` and a `test set`. The training set was randomly divided into 20 equal parts, and a linear classifier was trained on each of these subsets. The bias and variance of each model were then calculated using the test set. This process was repeated for different class functions, ranging from linear to polynomials of degree 15.

## _Calculating Irreducible Error_
---
The irreducible error represents the inherent noise or randomness in the data that cannot be reduced by any model. By subtracting the bias squared and variance from the mean squared error (MSE), the value of the irreducible error for the models trained was obtained.

## _Plotting Bias<sup>2</sup> − Variance Graph_
---
A graph depicting the Bias^2 − Variance tradeoff was plotted based on the values obtained. The graph helped visualize the relationship between bias<sup>2</sup>, variance, and model complexity. By analyzing the graph, insights were gained into the tradeoff between bias and variance, as well as the behavior of the model.

## Folder Structure and Files
---
Inside the src folder, you will find the following files:

* `code.ipynb`: This Jupyter Notebook contains the source code used in the model. It includes the implementation of tasks such as re-sampling the data, training linear classifiers, calculating bias and variance, calculating irreducible error, and plotting the Bias<sup>2</sup> − Variance graph.

* `train_dataset.pickle`: This file contains the train dataset used to train the models.

* `test_dataset.pickle`: This file contains the test dataset used to evaluate the trained models.
