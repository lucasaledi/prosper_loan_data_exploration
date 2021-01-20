# Prosper Loan Data Exploration
## by Lucas Aledi

# Dataset Overview
In this project, we have decided to analyse a dataset containing 113,937 loans with 81 variables on each loan, and
in-depth information such as loan amount, borrower's APR and interest-rate, as well as Prosper's rating, current loan
status, borrower income, and many others. After some wrangling, this has been reduced to +77500 loans with 26 variables on each loan. The main features include LoanOriginalAmount, LoanStatus, IncomeRange and BorrowerAPR.

The relevant dataset can be downloaded programmatically from [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)


# Summary of findings
After reviewing the information available in this analysis, one could come to the following conclusions:
    - Prosper has had an accelerating growth year-on-year (except for a slowdown in 2012). However, with the available data, we still don't know how well Prosper is doing in comparison to its competitors;
    - Not surprisingly, on average, the larger the loan amount, larger the monthly payment. Those, on their turn, tend to coalesce into 3 clearly distinct groups, driven by the loan term;
    - Lower income (below $50000 per year), when paired with higher levels of BorrowerAPR (above 0.25), seem to be related to higher levels of default. Given the insight above, it could be in the best interest of Prosper to develop a reliable model in predicting when this profile of customer would tend to default.

# Key Insights for Presentation
First, we are going to show that Prosper has had an accelerating growth year-on-year. For that, we used two bar plots showing the total number and amount of loans granted per year-month from July 2009 up to March 2014.
Secondly, to show the strong linear relationship between loan sizes, monthly payments and loan term, we used 2 scatter plots and 1 violin plot. On the scatter plot, we've decided to add a text box with the correlation coefficient. The violin plot is used to emphasize this relationship within the most common loan sizes.
Finally, to visualize the fact that small incomes, when combined with higher levels of BorrowerAPR, tend to lead to more defaults, we used 2 bar plots, 2 distplots and, finally, 2 scatter plots. Note that, in the last two plots, we try to visualize 4 different variables, being 2 of them numerical (LoanOriginalAmount and BorrowerAPR) and the other 2 categorical (LoanStatus and IncomeRange). That's why we've decided to split the visualization into 2 plots.


# Credits
github.com/lucasaledi

udacity.com
