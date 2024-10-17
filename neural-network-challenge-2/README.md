# Employee Attrition and Department Prediction Model

This project implements a multi-output neural network model to predict employee attrition and department based on various features of employee data.

## Project Overview

The model uses TensorFlow and Keras to build a neural network that simultaneously predicts:
1. Whether an employee is likely to leave the company (attrition)
2. The department an employee belongs to

The model is trained on a dataset containing various employee attributes such as age, distance from home, education level, job satisfaction, and more.

## Installation

To run this project, you need to have Python installed along with the following libraries:

``bash
pip install pandas numpy tensorflow scikit-learn
``


## Usage

The main code is contained in the `attrition.ipynb` Jupyter notebook. To use the model:

1. Load the dataset (not provided in this repository)
2. Run the cells in the notebook sequentially
3. The model will be trained and evaluated, providing accuracy and loss metrics for both attrition and department predictions

## Model Architecture

The model uses a multi-output neural network with:
- An input layer
- Multiple dense layers
- Two separate output layers:
  - A sigmoid activation layer for attrition prediction (binary classification)
  - A softmax activation layer for department prediction (multi-class classification)

## Results

The model achieves the following performance (note: these values may vary with different runs):

- Department Accuracy: ~60-65%
- Attrition Accuracy: ~83-85%

## Future Improvements

Potential ways to improve the model include:
- Hyperparameter tuning (learning rate, batch size, number of epochs)
- Experimenting with more advanced architectures
- Implementing regularization techniques like dropout
- Collecting more data or performing data augmentation


