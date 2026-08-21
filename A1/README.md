# Machine Learning Algorithms Laboratory – Experiment 1

## Experiment 1: Working with Python Packages

### Objective

To explore Python libraries used in Machine Learning and understand the complete ML workflow including EDA, preprocessing, feature selection, model training, and performance evaluation.

## Libraries Used

- NumPy
- Pandas
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn

## Datasets Used

1. Iris Dataset
2. Loan Amount Prediction
3. Predicting Diabetes
4. Classification of Email Spam
5. Handwritten Character Recognition / MNIST

## ML Tasks

| Dataset | ML Task | Feature Selection | Suitable Algorithm |
|---|---|---|---|
| Iris Dataset | Supervised Classification | ANOVA (SelectKBest) | KNN |
| Loan Amount Prediction | Supervised Regression | F-Regression (SelectKBest) | Linear Regression |
| Predicting Diabetes | Supervised Classification | ANOVA (SelectKBest) | Logistic Regression |
| Email Spam Classification | Supervised Classification | Chi-Square (SelectKBest) | Multinomial Naive Bayes |
| Handwritten Character Recognition / MNIST | Supervised Classification | ANOVA (SelectKBest) | SVM |

## ML Workflow

The experiment follows these steps:

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Handle missing values
4. Remove irrelevant features
5. Encode categorical variables
6. Perform feature selection
7. Split the data into training and testing sets
8. Normalize or scale the features
9. Train the machine learning model
10. Make predictions
11. Evaluate model performance
12. Visualize the results

## Performance Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Regression

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Structure

```text
ML-Experiment-1/
│
├── README.md
├── requirements.txt
├── ML_Experiment_1.ipynb
│
└── figures/
    ├── iris/
    ├── loan/
    ├── diabetes/
    ├── email_spam/
    └── mnist/