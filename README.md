# Prosper Data Analytics
## by Satyam Chauhan


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The idea to analyze various features and generate informative visuals. It would be interesting to see how certain feature influence borrowers APR or what's the most popular purpose for loan etc. 

## Summary of Findings

> Univariate Analysis:

    1. Visualization 1:
        a. Sorted the loan status based on value_counts
    2. Visualization 2:
        a. I wanted to use fico score credit rating so I mapped the fico score category to the credit score in the data set
        b. There was a band of scores provided in the dataset so I took the average of them and then started mapping
    3. Visualization 3:
        c. Borrower rate has bimodal distribution 
    4. Visualization 4:
        a. I created categories by breaking down the LoanOriginalAMount into bins and edges
    5. Visualization 5:
        a. Performed sorting of the loan term so that it is sorted in descending order

> Bivariate Analysis:

    1. Visualization 1:
        a. home ownership lowers credit risk since it can be used a collateral as can be seen by the interest rates offered to home owners
    2. Visualization 2:
        a. Good ratings get better interest APR but Very Poor rating seems to have a good borrower APR which needs further investigation
    3. Visualization 3:
        a. This plot gives us the glimpse of Default/Completion of loans based on credit ratings
    4. Visualization 4:
        a. The distribution of borrower apr for different credit rating scores where most of them are skewed
    5. Visualization 5:
        a. The Income bands with very high and no income (students) receive favorable interest rates
    6. Visualziation 6:
        a. This insight shows the interest rate changes over the years. This interest rate was low before the 2008 financial crash and we can see that increasing trend in the ionterest rate
    7. Visualization 7:
        a. Debt consolidation is the top loan type followed business and home improvement
    8. Visualization 8:
        a. Prosper's top customers are computer proggrammers, Analyst, and Admin Assistant
        
> Multivariate Analysis: 

    1. Visualization 1:
        a. loans with on time payment lower than 10 could default whereas higher on time payment have lower interest rate except few exceptiosn which needs further investigation
    2. Visualization 2:
        a. It shows that the loans that defaulted had higher interest rate for than the ones that were successfully paid off maybe some factors led to the increase in interest rate which in turn caused the default
    3. Visualziation 3:
        a. The borrower's interest and lenders yeild increases with deteriorating rating since it increases the investor's risk
    4. Visualization 4:
        a. Loan amount requested by the applicants is dependent on their income range
        
## Key Insights for Presentation

Explorative analysis gave out bunch of key insights. I would like like to use visualizations that show top loan type, top professions (this could be used by prosper for targeted loan offering or for selling that information to businesses for targeted ad) Thereafter I would like to visualize borrower apr vs income band to see how the interest rates vary based on income band 

Finally, I would conclude with two multivariate plots

1st visualization will show the relationship between lender's yeild, borrower's rate and prosper rating and the 2nd visualization will show the loan amount requeted by various income bands and how it fares againts interest rates 
