# Module 12 Report Template

## Overview of the Analysis

Creditworthiness Prediction Model Report

**Overview**

In this analysis, our primary objective was to construct a machine learning model aimed at forecasting the creditworthiness of borrowers for a peer-to-peer lending services company.

Within our dataset, a binary value system was employed, with 0 signifying healthy loans and 1 indicating loans at a high risk of default.

The initial dataset consisted of 77,536 entries distributed as follows:
- Healthy Loans: 75,036
- High-Risk Loans: 2,500

Various features within the dataset were explored, encompassing loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, and total debt.

We leveraged the Logistic Regression method to develop this predictive model, following these key steps:

1. Imported the original data CSV using Pandas.
2. Segregated labels (y) from features (x).
3. Split the data into training and testing sets via the train_test_split method.
4. Constructed the Logistic Regression model using the training data.
5. Made predictions on the test dataset and compared them with the y_test data.
6. Evaluated the model's performance.

**Results**

The machine learning model, constructed using Logistic Regression, yielded the following outcomes:

- Balanced Accuracy Score = 0.952
- Confusion Matrix:
    - True Negatives: 18,663
    - True Positives: 563
    - False Positives: 102
    - False Negatives: 56

**Negative Results:**
- Precision = 1.00
- Recall = 0.99

**Positive Results:**
- Precision = 0.85
- Recall = 0.91

**Summary**

In summary, this model demonstrates commendable predictive capabilities for both healthy and high-risk loans. Notably, it excels in predicting healthy loans, boasting a precision of 100% and a recall of 99%. While its performance is slightly less robust in predicting high-risk loans, with a precision of 85% and a recall of 91%, these results are still deemed acceptable.

The model achieves a balanced accuracy score of approximately 95%, affirming its effectiveness in predicting loan outcomes.
