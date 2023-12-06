# Evaluation-of-credit-worthiness-by-Credit-scoring-and-segmentation
## Introduction

Credit scoring is a statistical method that is used to predict the probability that a loan applicant, existing borrower, or counterparty will default or become delinquent. The project involves calculating the credit scores and segmenting customers based on their credit scores.

# Description
The following parameters are considered for evaluation
"Age", "Gender", "Marital Status", "Education Level", "Employment Status", "Credit Utilization Ratio"
"Payment History", "Number of Credit Accounts", "Loan Amount", "Interest Rate", "Loan Term", "Type of Loan"

# Calculating Score
To calculate credit scores FICO method is used and then the Kmean clustering algorithm is used to segment customers based on their scores.

# FICO Method
A FICO score is a credit score created by the Fair Isaac Corporation (FICO).
FICO scores take into account data in five areas to determine a borrower's creditworthiness: 
Payment history (35%)
The current level of indebtedness(30%)
Types of credit used (10%) 
Length of credit history (15%)
New credit accounts (10%) 

In this project, we have considered
Payment History (35%)
Credit Utilization Ratio (30%)
Number of Credit Accounts (15%)
Education Level (10%)
Employment Status (10%)

# FICO Range
Scores range from 300 to 850, with scores in the 670 to 739 range considered to be “good” credit scores.


