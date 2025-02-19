# Mobile Price Classification Model

This repository contains a Mobile Price Classification Model aimed at predicting the price range of mobile phones based on their technical specifications, using Logistic Regression, kNN, and, Randomforest model. The goal is to classify mobile phones into one of four price ranges using machine learning techniques.

## Dataset
The dataset used for this project comes from [Kaggle's Mobile Price Classification Dataset](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification/data). Each mobile phone in the dataset is labeled with one of four price ranges (0 to 3), with 0 being the cheapest and 3 being the most expensive.

## Usage
To run the notebook locally, ensure you have the following dependencies installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Evaluation
The model is evaluated using accuracy score.

## Feature Selection
Feature Selection is based on lasso regression and is proven authenticity after building ramdom forest model using feature importance feature of ramdom forest.
![picture](/lasso-feature-selection.png)
![picture](/feature-importance-forest.png)

