# SC5002 Lab Assignment

This repository contains my Colab notebook for Part 2 of the SC5002 lab assignment. The notebook uses the California Housing dataset to compare Linear Regression and Ridge Regression (alpha = 0.1, 10 and 1000) using 5-fold cross-validation.

## Results

| Model | Mean R² Score |
|---|---|
| Linear Regression | 0.6457 |
| Ridge (alpha = 0.1) | 0.6457 |
| Ridge (alpha = 10) | 0.6443 |
| Ridge (alpha = 1000) | 0.3574 |

Ridge with a very high alpha (1000) performed much worse as the model underfits. Part 1 and the AI prompt logs are in my report.
