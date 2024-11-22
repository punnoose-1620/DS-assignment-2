# Data Science Assignment 2: Classification and Regression

This repository contains files and workflows for Assignment 2 of the Data Science course, where classification and regression techniques are explored using two datasets: `adult.csv` and `housing.csv`. The results are validated using a 10-fold cross-validation approach.
## Contents

  Classification on adult.csv:
      Tried 3 classification models (Decision Tree, KNN, Random Forest)
      Evaluated accuracy, precision, recall, and F1-score using 10-fold cross-validation.
  Regression on housing.csv:
      Applied 3 regression models (Simple Regression Tree, Gradient Boosted Trees, Random Forest Regressor).
      Compared R², Mean Squared Error (MSE), and Mean Absolute Error (MAE).

## Objective

  Classification Task: Predict whether an individual earns over $50K based on demographic attributes.
  Regression Task: Predict housing prices using features like lot area, neighborhood, and house quality.

## How to Run

  Load the KNIME workflows included in this repository.
  For classification:
      Load `adult.csv` and preprocess data.
      Run the classification models and compare results using cross-validation.
  For regression:
      Load `housing.csv` and preprocess data.
      Train regression models and evaluate results.

## Results

  Included evaluation metrics for all models, comparison tables, and visualizations for both classification and regression tasks.

## Dependencies

  KNIME Analytics Platform for running workflows.
  The following datasets:
      `adult.csv`
      `housing.csv`

Future Enhancements

  Experiment with hyperparameter tuning for improved accuracy.
  Explore additional models and techniques, such as neural networks or ensemble methods.
