# Logistic Regression

## Introduction

Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Unlike linear regression which outputs continuous number values, logistic regression transforms its output using the logistic sigmoid function to return a probability value which can then be mapped to two or more discrete classes.

## Logistic Sigmoid Function

The logistic sigmoid function is defined as:

$$\sigma(t) = \frac{1}{1+e^{-t}}$$

where $t$ is the input to the function. It maps the input t to a value between 0 and 1. It is also called a squashing function as it squashes the input t to a value between 0 and 1.

## Project Overview

In this project, I will implement logistic regression from scratch and apply it to two different datasets. Before starting on the programming exercise, I will first import the libraries I will need for this project.

## Import Libraries

The following libraries will be used throughout this project:

- numpy: the fundamental package for scientific computing with Python.
- pandas: the library for data structures and data analysis tools.
- matplotlib.pyplot: the library for plotting the graphs.
- scipy.optimize: the library for various optimization algorithms.

## Visualizing the Data

Before starting to implement any learning algorithm, it is always good to visualize the data if possible. The code will load the data and display it on a 2-dimensional plot by calling the function plotData. The two axes are the two exam scores, and the positive and negative examples are shown with different markers.

## Implementation

### Sigmoid Function

Before I start with the actual cost function, I will first implement the sigmoid function. The sigmoid function is defined as:

$$\sigma(t) = \frac{1}{1+e^{-t}}$$

The code will implement this function in sigmoid.m so it can be called by the rest of the program. When I am finished, I will test a few values by calling sigmoid(x) in a new cell. For large positive values of x, the sigmoid should be close to 1, while for large negative values, the sigmoid should be close to 0. Evaluating sigmoid(0) should give me exactly 0.5. My code should also work with vectors and matrices. For a matrix, my function should perform the sigmoid function on every element.

## How to run the project

The project is implemented using Jupyter Notebook. To run the notebook, please use the following command:

```bash
jupyter notebook
```

and then open the notebook in the browser.

## Reference

- [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
- [Logistic Regression](https://www.coursera.org/learn/machine-learning/home/week/3)

## Contact me

If you have any questions or suggestions about this project, please feel free to contact me:

- [LinkedIn](https://www.linkedin.com/in/felix-kiprotich-a2ba1a1a4/)
- [Email](mailto:penscolashackletonfelix@gmail.com)