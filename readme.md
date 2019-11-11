# Prosper Loan Data Exploration
## by Eduardo Burgoa


## Dataset

This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

- More than 30% of closed loans are not completely collected and are considered Chargedoff or Defaulted.
- The most common categories are Debt Consolidation, Not available, Other, Business, Home improvement and Personal Loan.
- More than 50% of loans have amounts lower than $5,000.
- Althoug there is a high percentage of incomes not displayed, most of the borrowers seem to have medium and high incomes. 
- More than 90% of the incomes are verified.
- Defaulted and Chargedoff loans have a lower median ratings than completed loans. Therefore there seems to be a direct relation between ratings and the probaibility of completing the payment of a loan.
- There is a strong relation between borrower interest rate and loan status.
- `ProsperRating` is a better predictor of completation than `GreditGrade`.
- There is a strong correlation between `ProsperRating`and `BorrowerRate`.
- `GreenLoans` and `Household Expenses` have the worst completation on `Other` employment `Retired` and `Self-Employment`. 
- `Full-time` employees are the best completing loans except for `Household Expenses` which is only 47%.
- Completation of `Vacation` loans is high except for `Other` which is only 50% and `Not employed` which is 0%.
- Completation of `Motorcycle` is very high except for `Self-employed` which is only 25%. 
- Completation of `Wedding Loans` is moderately high except for `Other` employment status which is only 25%. 


## Key Insights for Presentation

- How many loans are not completely returned?
- Which factors are related to the rate to pay for a loan?
- What factors of the borrower are related to completation of loans?