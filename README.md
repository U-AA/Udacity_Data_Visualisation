# (Dataset Exploration: Prosper Loan Dataset)
## by (Utianle Helena Kolade)


## Dataset

The prosper loan dataset is a financial dataset containing 113,937 loans with 81 variables on each loan. The dataset variables include things related to the loan, borrowers, lenders and interest rates.
This dataset however was too large to make unique analysis, therefore, the variables that were not needed for the analysis were dropped.
This led to a final dataset of 24 columns and 113066 enteries.

## Summary of Findings

> The loan original amount plotted against the borrower APR and the borrower rate have similar plots. They bot have a negative regression, meaning that the higher the loan amount, the lower the rates and APR.

> it can be seen from the loan status vs term plot that majority of the people have opted for the 36 months term for their payments and those on the 36 months term have the higher counts in all payment statuses... even the defaulted.

> The prosper score of between 4.0 to 9.0 is where most people from both the currently paying off loan status and the completed loan status lie. This is a good indication that the prosper score does not neccessarily affect your ability to pay back your loan.

> The completed status has a higher number of people who do not own homes.

> The variables worked on for the analysis are rather more independent than dependent on each other.

> People not paying their loans on time or fully completing their loan payments have nothing to do with their occupation, employment status, income range, state, being a home owner, rates and APR or any of the other variables analised.

> The only variables that had positive correlations are BorrowerRate and BorrowerAPR, LoanOriginalAmount and MonthlyLoanPayment, and the credit score ranges. On the other hand, a few had average negative correlations such as ProsperScore against both BorrowerRate and BorrowerAPR, and also IncomeVerifiable against DebtToIncomeRatio, and a few others had weak negative correlations such as: the credit score ranges against the borrower rates and APR.


## Key Insights for Presentation

For the presentation, I focused mainly on the Income Range spread for the loan seekers, then showed the relationship between Borrower APR and Borrower rate with LoanAmount, then finally a correlation heat map of all the quantitative attributes.