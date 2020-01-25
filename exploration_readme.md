# Prosper Loan Listing Data Exploration Summary
## by Roy Amante A. Salvador


## Dataset

The data consists of 113,387 Prosper Loan Listings with [81 variables](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)  such as amount of loan, interest rate, status of loan, borrower information among many more. As such, we narrowed our investigation with the following variables.

* Loan Listing Information
    * Interest Rate, Loan Amount, Loan Term, Loan Status, Risk Rating, Category, Period of Origination
    
* Borrower Information
    * Income Range, Credit Score, Group Membership
    
* Funding Information
    * Number of Investors, Speed of Funding

The dataset can be downloaded [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1578484330585000). 


## Summary of Findings

We first checked and  found out the distribution of each of our features of interest. We will only include information regarding distribution of Interest Rate. During bivariate and multivariate, we were able find relationship of Interest rate with all of the feature variables mentioned previously except for Speed of Funding. Similarly, Loan amount and NUmber of Investors are seen also to be correlated with most variables but we will no longer include them to manage load of information. 

Most of the plots used in exploration are simple enough to interpret so we will just polish them for presentation. A couple of categorical fields, Loan Listing Category and Income Range have a lot of possible values so we will change them from box plots to point plots to make them visually cleaner.




## Key Insights for Presentation

We stick with our plan of focusing our presentation with Prosper Loan Interest Rate. We need to answer the following questions

* What are the Loan interest rates at Prosper?
* Which factors can be used to predict interest rate? 
* Why are we investigating?
