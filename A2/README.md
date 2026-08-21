# Experiment 2 – Email Spam/Ham Classification

## Objective
To build and evaluate spam/ham email classifiers using Naïve Bayes and KNN algorithms, including hyperparameter tuning, cross-validation, performance evaluation, and time-complexity analysis.

## Dataset
Spambase Dataset.

The dataset contains email-related features used to classify emails as:
- 0 – Ham
- 1 – Spam

## Algorithms Implemented
- Gaussian Naïve Bayes
- Multinomial Naïve Bayes
- Bernoulli Naïve Bayes
- K-Nearest Neighbors (KNN)

## Implementation
The experiment includes:

1. Data loading and preprocessing
2. Handling missing values
3. Feature normalization
4. Exploratory Data Analysis (EDA)
5. Train-test splitting
6. Naïve Bayes classification
7. KNN classification for different values of k
8. GridSearchCV for KNN hyperparameter tuning
9. RandomizedSearchCV for KNN hyperparameter tuning
10. KDTree and BallTree comparison
11. 5-Fold Cross Validation
12. Training and prediction time comparison
13. Theoretical time-complexity analysis

## Performance Metrics
The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Visualizations
The experiment includes:

- Class distribution
- Correlation heatmap
- Feature histograms
- Boxplots
- Confusion matrices
- ROC curves
- Precision-Recall curves
- Accuracy vs k
- Cross-validation accuracy
- Training time comparison
- Prediction time comparison
- Classifier comparison
- GridSearchCV heatmap
- RandomizedSearchCV score distribution

## Requirements
Install the required Python packages using:

```bash
pip install -r requirements.txt