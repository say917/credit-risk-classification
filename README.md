# credit-risk-classification

# Overview
The overall purpose of this analysis is to use a supervised machine learning model to analyze healthy loans and high risk loans in the given dataset called "lending_data.csv". This dataset is comprised of Loan Size, Interest Rate, Borrower Income, Number of Accounts, Derogatory Mark and Total Debt. Using this information we will construct a logistic Regression model to predict Precision, Recall and f1 Score.
Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)

# Results

        precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

- Accuracy is 99% of the classified instances
- Precision Healthy Loan is 100% which indicates how many of the predicted positive instances are actually positive.
- Precision Risk Loan is 85% which indicates how many of the predicted positive instances are actually positive.
- Recall Healthy Loan is 99% which indicates how many of the actual positive instances were correctly identified by the model.
- Recall Risk Loan is 91% which indicates how many of the actual positive instances were correctly identified by the model.

# Summary

**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels? Do you recommend the model for use by the company.

**Answer:** The logical regression model's predications are fairly accurate for healthy loans(0). Our model shows a precision rate of 100% with 99% recall. High risk loans(1) have a precision rate of 85% with 91% recall. This could be subjected to a small population size as indicated by the support. Healthy loans have a bigger feature size therefore, it better represents the large dataset. I recommend using this model as the indicators are favorable.
