# Experiment 4 - Binary Classification using Linear and Kernel-Based Models

## Objective

To classify emails as spam or ham using Logistic Regression and Support Vector Machine (SVM) classifiers and to analyze the effect of hyperparameter tuning on classification performance.

## Dataset

The experiment uses the Spambase dataset.

The dataset contains numerical features extracted from email content and a binary target indicating whether an email is spam or ham.

Dataset:
https://www.kaggle.com/datasets/somesh24/spambase

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Experiment Steps

1. Load the Spambase dataset.
2. Handle missing values.
3. Perform Exploratory Data Analysis (EDA).
4. Standardize the features.
5. Split the dataset into training and testing sets.
6. Train a baseline Logistic Regression model.
7. Tune Logistic Regression hyperparameters using Grid Search.
8. Train SVM using different kernels.
9. Tune SVM hyperparameters using Grid Search.
10. Evaluate the models using standard classification metrics.
11. Perform 5-Fold Cross-Validation.
12. Compare the performance of Logistic Regression and SVM.

## Models Used

### Logistic Regression

Logistic Regression is used as a linear binary classification model.

The following hyperparameters are tuned:

- Penalty: L1, L2
- C: 0.01, 0.1, 1, 10, 100
- Solver: liblinear, saga

### Support Vector Machine

SVM is evaluated using the following kernels:

- Linear
- Polynomial
- RBF
- Sigmoid

The following hyperparameters are tuned:

- C: 0.1, 1, 10, 100
- Gamma: scale, auto
- Degree: 2, 3, 4 for Polynomial kernel

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Training Time

Additional visualizations include:

- Class distribution
- Correlation heatmap
- Confusion matrices
- ROC curves
- 5-Fold Cross-Validation performance

## Hyperparameter Tuning

Grid Search with 5-Fold Cross-Validation is used to find the best hyperparameters for Logistic Regression and SVM.

The best estimator obtained from Grid Search is used for the final evaluation.

## Results

The notebook displays:

- Logistic Regression performance
- SVM kernel-wise performance
- Best hyperparameters
- Best cross-validation accuracy
- 5-Fold Cross-Validation results
- Confusion matrices
- ROC curves
- Comparative analysis of the models

## Files

```text
.
├── README.md
├── requirements.txt
├── spambase.csv
├── Experiment_4.ipynb
└── figures/