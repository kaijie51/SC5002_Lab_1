# SC5002 Lab 1 Assignment

This repo contains my Colab notebook for Part 2 of the SC5002 Lab 1 Assignment.

The notebook uses the California Housing dataset to predict the median house value of different areas in California based on features such as median income, house age, number of rooms, population and location. Linear Regression and Ridge Regression (alpha = 0.1, 10 and 1000) are compared using 5-fold cross-validation.

## Results

| Model | Mean R² Score |
|---|---|
| Linear Regression | 0.6457 |
| Ridge (alpha = 0.1) | 0.6457 |
| Ridge (alpha = 10) | 0.6443 |
| Ridge (alpha = 1000) | 0.3574 |

Ridge with a very high alpha (1000) performed worse as the model underfits.
