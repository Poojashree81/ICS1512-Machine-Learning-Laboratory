# Regression Analysis using Linear and Regularized Models

## Objective

To implement and compare Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net Regression for predicting a continuous target variable.

## Dataset

The experiment uses a real-world loan application dataset. The target variable is the **loan amount sanctioned**.

## Models Implemented

* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net Regression

## Preprocessing

The following preprocessing steps are performed:

* Handling missing values
* Encoding categorical variables using One-Hot Encoding
* Standardizing numerical features
* Splitting the dataset into training and testing sets

## Hyperparameter Tuning

Grid Search with 5-fold cross-validation is used for regularized regression models.

### Ridge

* Alpha: `0.01, 0.1, 1, 10, 100`

### Lasso

* Alpha: `0.001, 0.01, 0.1, 1, 10`

### Elastic Net

* Alpha: `0.01, 0.1, 1, 10`
* L1 Ratio: `0.2, 0.5, 0.8`

## Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Training Time

## Visualizations

The experiment includes:

* Target variable distribution
* Feature vs. target scatter plots
* Predicted vs. actual values
* Residual plot
* Training error vs. validation error
* Coefficient comparison

## Analysis

The experiment analyzes:

* Overfitting and underfitting
* Effect of regularization
* Generalization performance
* Bias–variance trade-off
* Effect of Lasso feature sparsity

## Files

* `ML_Experiment_3.ipynb` – Jupyter Notebook containing the implementation
* `loan_data.csv` – Dataset
* `figures/` – Generated plots in EPS format
* `requirements.txt` – Required Python libraries

## Conclusion

The performance of Linear Regression and regularized regression models is compared to understand how regularization affects model complexity, prediction accuracy, and generalization.
