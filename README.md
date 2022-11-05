# (Prosper Loan Data Analysis)
## by (Chimaobi Uwakwe)


## Dataset

> This data set is the Prosper Loan Data which contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The Prosper data had a lot of redundant columns and only the features relevant for this analysis were selected narrowing it down to 17. 
The Data contained missing data which were dropped. There were also deplicates identified for which the additional entry were dropped. Finally, The Loan Origination date and closing date format were changed to datetime format. The Dataset can be found [here] ( https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.) and the data dictionary is [here] (https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)



## Summary of Findings


> In the exploration i found tha most loans were booked under the 36 months term. The analysis from the available data also revealed that 2013 had a high number of loan requests. I also found out that most loans were availed to customers who reported employed and fulltime as their employment status. I also observed that loan amounts between 4,000 and 5,000 and a second band between 8,000 and 16,000 were the most popular leading with the most significant nmber of count

## Key Insights for Presentation


> I started the analysis by asking which term for the loans is most preferred with a clear leader of the 36 months loan. I also checked for the influence of stated monthly income on Loan original amount which revealed a decent correlation of the pair.
The pair of Borrower APR and Loan original amount also revealed that loan amounts below 15,000 generated better yield for the lender. This position is also supported by the pair of Estimated Return and Loan Original Amount.
Also, Loan amounts of 15,000 and below for a 60 months term had higher borrower APR when compared to 
