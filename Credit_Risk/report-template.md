# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis is to train a machine learning model to accurately predict healthy and high risk loans based on a number of factors including: interest rate, borrowers income and debt-to-income ratio. The dataset included 77536 rows of day with 7 columns.
As previously indicated, columns included: loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status.

The dataset was first split into independent variables "X" and dependent variable "y". Both sets of variables were then split into test and training data with 75% of the data being used to train the date while 25% was used to test the data. Logistic regression was the model chosen in this analsis

## Results
* Acccuracy score - 100% of the actual healthy loans were identified correctly while 95% of the actual high risk loans were identified correctly
* Precision - Based on the clasification report, we can tell that 100% of the predicted health loans were correct and 85% of the predicted high-risk loans were correct. This indicates that the precision of this model is quite high
* Recall -  Healthy loans has a recall score of 100% while high-risk loans had a recall score of 95%. This indicates that for healthy loans, the ratio of correctly predicted healthy loans to the total actual healthy loans was a 100%. This also means that the ratio of correctly predicted high risk loans to the total actual high risk loans was a 100%

## Summary
In summary, I would recommend this model in light of the hight accuracy, precision and recall values for both high risk and healthy loans. It important to note that the model performs better when attempting to predict healthy loans than high risk loans. Based on the classification table, we know that this model is only about 85% precise when predicting high risk loans. If the business values accurately predicting high risk loans over healthy loans, we would potentially need to explore other models.
