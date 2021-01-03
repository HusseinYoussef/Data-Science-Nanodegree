# Prosper Loan Data Exploration
## by Hussein Youssef


## Dataset

> * This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> * I focused only on a subset of the features including Term, LoanStatus, BorrowerAPR, ProsperRating, Occupation, ListingCategory, EmploymentStatus, StatedMonthlyIncome, LoanOriginalAmount.
> * Removed rows with NA borrower's APR.
> * For MonthlyIncome, I removed some of the outliers to reduce them.

## Summary of Findings

> * Debt Consildation (1), Home Improvement (2) and Business (3) are the most popular listings. The dataset also contains lots of 'Not available (0)' and 'Other (7)' listings.
> * Most of the Loans have 'Current' status.
> * MonthlyIncome distribution is a right-skewed distribution with mean near 5000.
> * A, B, C and D are the most popular ratings. 
> * Most borrowers are employed and full-time. In addition to that, there is a small portion of the borrowers who are retired or unemployed.
> * The length of most of the loans are 36 months.
> * APR is more close to a unimodal distribution with mean around 0.2.
> * Borrowers with really high APR have risk signals, such as very low loan amount, lower income, NAN or Not employed EmploymentStatus, NAN Occupation, low ProsperRating or low ProsperScore.
> * There exists a negative relationship between borrower's APR and LoanAmount. The more the loan amount is, the lower APR is.
> * There is a weak negative relation between monthly income and the APR.
> * There is a positive relation between loanAmount and Income.
> * Rating has negative relation with APR, the more the rating is, the less APR is.
> * Large loan amounts tend to have longer terms and better ratings.
> * Large loan amounts are mostly created by Employed borrowers.
> * More monthly incomes have higher ratings.
> * HR ratings have only 36-months terms.
> * 36-months ratings is the most popular/standard terms apparently.
> * Most of the 60-months terms tend to have C and B ratings.
> * The Negative relation between the APR and loanAmount turns to be slightly positive in high ratings!
> * There is negative relation between APR and rating across all terms.
> * There is positive relation between LoanAmount and rating for 36-months and 60-months terms but there is no change in 12-months term.
> * For monthly income vs rating, the behaviour across all terms is quite similar with weak positive relation.

## Key Insights for Presentation

> In the presentation, I focused on some of the features that affect borrower's APR directly and how they affect it, for example, I showed the relation between Borrower's APR and LoanAmount, relation between Borrower's APR and Ratings, the behaviour between Borrower's APR and LoanAmount across Ratings and lastly the behaviour between Borrower's APR and Ratings across Terms.