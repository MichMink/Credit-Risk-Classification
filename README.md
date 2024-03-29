# Credit-Risk-Classification

## Overview of the Analysis

In this analysis, the goal was to develop a machine learning model to predict high-risk loans. The dataset consisted of financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict whether a loan would be high risk based on these variables.

Key steps in the machine learning process included data preprocessing, model selection, fitting/training, and evaluation. This output is based on a Logistic Regression Model.

Logistic Regression was chosen for this analysis due to its simplicity, interpretability, and effectiveness in binary classification tasks, such as predicting high-risk loans. It provides a probabilistic interpretation of the relationship between the independent variables and the likelihood of a loan being high risk. Additionally, logistic regression works well with linearly separable data and is robust to noise, making it suitable for financial datasets with potentially complex relationships between variables.

## Results

* **Regression Line Model:**
    * Regression Line Output:
        ```
                  precision    recall  f1-score   support

               0       1.00      0.99      1.00     18765
               1       0.85      0.91      0.88       619

        accuracy                           0.99     19384
       macro avg       0.92      0.95      0.94     19384
    weighted avg       0.99      0.99      0.99     19384
        ```

## Summary

Based on the results, it's evident that the Logistic Regression model achieved high accuracy, precision, and recall scores. With an accuracy of 99%, precision of 85%, and recall of 91%, the model shows strong performance in predicting high-risk loans based on the provided features.

- **Precision**: Precision measures the accuracy of the model in correctly identifying high-risk loans among all the loans predicted to be high risk. In the context of credit risk analysis, precision indicates the proportion of loans correctly identified as high risk out of all the loans predicted as high risk by the model.
- **Recall**: Recall measures the ability of the model to capture all actual high-risk loans among all the loans that are actually high risk. In credit risk analysis, recall indicates the proportion of actual high-risk loans correctly identified by the model out of all the loans that are truly high risk.
- **F1-score**: F1-score is the mean of precision and recall, providing a single metric that balances both precision and recall. It is particularly useful in credit risk analysis as it considers both the proportion of correctly identified high-risk loans and the proportion of actual high-risk loans captured by the model, providing a balanced assessment of the model's performance in predicting high-risk loans.




