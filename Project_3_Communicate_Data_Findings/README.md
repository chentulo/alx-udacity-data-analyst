# Prosper Loan Data Exploration
## by Wellington Chentulo


## Dataset

The dataset used in this exploration consists of loan information from Prosper, containing 113,937 loan observations.
The dataset contains 81 observations, some of which are the amount of the loan, term of the loan, borrower's interest rate
on the loan, and the number of investors in a particular loan. 
The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature information available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

In this exploration, I observed that there was a perfect positive relationship between the borrower's interest rate and 
the lender's yield on the loan. However, the borrower's interest rate and the Prosper score showed a negative relationship.
This was expected since a higher Prosper score indicates a low credit risk borrower and lower risk would attract a lower interest rate.

Outside the main variable of interest, I observed that the lender yield and the Prosper score showed a negative relationship, which was a similar relationship to that between the borrower interest rate and the Prosper score. The number of investors showed a small positive correlation with both the loan amount and the Prosper score. My other observation was that there is a small negative correlation between the lender's yield and the loan amount.

## Key Insights for Presentation

For the presentation, I focus on just the interaction between the borrower rate and lender yield and Prosper score. 
I start by introducing the borrower rate variable, followed by the pattern in the borrower rate distribution, 
lender yield and Prosper score distribution. Then I conclude with a summary of my findings and what the limitations were in this project.

I will use a scatterplot, boxplots and the correlation heatmap to convey the interactions between these variables.