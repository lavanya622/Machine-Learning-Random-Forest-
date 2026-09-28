# Random Forest

## Overview

This project demonstrates the practical implementation of **Random Forest** for Machine Learning.

The project focuses on customer churn prediction and covers data preprocessing, imbalanced data handling, model evaluation, cross-validation, and hyperparameter tuning.

## Dataset

The dataset contains **2,000 records and 15 columns**.

The dataset includes customer-related information such as:

* Customer age
* Annual income
* Tenure
* Monthly bill
* Support calls
* Complaints
* Data usage
* Late payments
* Satisfaction score
* Discount percentage
* Contract type
* Internet service
* Payment method
* Region

### Target Variable

**Churn**

* `0` — No Churn
* `1` — Churn

## Workflow

The project follows a complete Machine Learning workflow:

**Data Collection → Data Preprocessing → Missing Value Handling → Categorical Data Processing → Train-Test Split → Imbalanced Data Handling → Random Forest → Prediction → Model Evaluation → Cross-Validation → Hyperparameter Tuning**

## Imbalanced Data Handling

The dataset was analyzed for class imbalance and appropriate resampling was performed on the training data.

This step was included to improve the representation of minority-class samples during model training while keeping the test data unchanged for evaluation.

## Random Forest

Random Forest is an ensemble learning algorithm that combines multiple Decision Trees to produce a final prediction.

It was used in this project for **customer churn classification**.

## Model Evaluation

The Random Forest model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

These metrics were used to understand the classification performance of the model.

## Cross-Validation

**5-Fold Stratified Cross-Validation** was performed to evaluate the consistency of the model across multiple data splits.

The mean cross-validation accuracy was calculated from the five folds.

## Hyperparameter Tuning

**GridSearchCV** was used to identify suitable Random Forest hyperparameters.

The tuning process considered parameters such as:

* Number of trees (`n_estimators`)
* Maximum tree depth (`max_depth`)
* Minimum samples required for splitting (`min_samples_split`)
* Minimum samples required in a leaf (`min_samples_leaf`)
* Bootstrap sampling (`bootstrap`)

This helped explore different model configurations and identify the best parameter combination based on cross-validation.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

## Key Learning

Through this project, I gained practical experience in:

* Random Forest Classification
* Ensemble Learning
* Data Preprocessing
* Imbalanced Data Handling
* Classification Model Evaluation
* Confusion Matrix Analysis
* Stratified Cross-Validation
* Hyperparameter Tuning
* GridSearchCV

## Conclusion

This project provided practical experience in building a **Random Forest classification model** for customer churn prediction.

It also strengthened my understanding of **imbalanced data handling, model evaluation, cross-validation, and hyperparameter tuning**.

---



⭐ Part of my **Machine Learning Practical Series**
