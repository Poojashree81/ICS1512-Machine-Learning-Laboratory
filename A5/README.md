# Decision Tree and Random Forest: A Comparative Classification Study

## Objective

This experiment implements and compares Decision Tree and Random Forest classifiers using the Wisconsin Diagnostic Breast Cancer dataset.

The objectives are:

- Implement a Decision Tree classifier.
- Implement a Random Forest classifier.
- Study the effect of hyperparameters on model performance.
- Perform 5-Fold Cross-Validation for hyperparameter selection.
- Compare the performance of Decision Tree and Random Forest models.

## Dataset

The dataset used is the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.

Dataset files:

- `wdbc.data`
- `wdbc.names`

The dataset contains:

- 569 samples
- 30 numerical features
- 2 classes:
  - Malignant (M)
  - Benign (B)

The dataset is loaded from:

```text
/kaggle/input/datasets/poojashree81/breast-cancer-wisconsin/wdbc.data