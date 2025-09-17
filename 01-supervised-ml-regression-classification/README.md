# Project Jupiter — Goal Prediction (Chelsea × Liverpool) with Linear Regression

Inspired by Andrew Ng’s course example (house size vs. price), this notebook applies a **univariate linear regression model** to explore whether there is any relationship between the **match date** (variable \(x\)) and the **total number of goals** scored (variable \(y\)) in Chelsea vs. Liverpool games.

The purpose is not to perfectly predict future scores but to use football data as a **didactic playground** to understand key concepts: **hypothesis function, cost function, parameter fitting, and performance evaluation**.

## Notebook outline
1. Data preparation and cleaning.
2. Visualization of match date vs. goals.
3. Training a univariate linear regression model.
4. Model evaluation (MSE, \(R^2\)) and residual analysis.
5. Predicting the number of goals in the next match.

## Next steps
- `02_two_features_linear_regression.ipynb` → add a second predictor (e.g., home vs. away).
- `03_gradient_descent.ipynb` → implement gradient descent from scratch and visualize convergence.
- `04_model_validation.ipynb` → temporal validation and baseline comparisons.  