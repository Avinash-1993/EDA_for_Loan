# Exploratory Data Analysis on Loan dataset
EDA for Loan that unables to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.


## Table of Contents
* [General Info](#general-information)
* [Data Cleaning](#data-cleaning)
* [Graphs Used for Visualization](#graphs-used-visualization)
* [Summary](#summary)



## General Information
- To develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
- Consumer finance company specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- Dataset has 39717 rows and 111 columns.

## Data Cleaning
- Removing of irrelevant columns.
- Removing of columns which has more than 40% missing or NA values.
- Removing of columns which has unqiue value only 1.
- Creating of bins for defining the ranges for variuos important columns.


## Graph Used for Visualization
- For Continuous Variables, we use various statistical metrics visualization methods such as Boxplot,Histogram/Distribution Plot, Violin Plot.
- For Categorical Variables, countplot or Bar chart can be used as visualization.


## Summary
- Most of the loan amounts are distributed between 5000 to 15000 USD.
- Most of the loans interest rates are distributed between 8% to 15%.
- Most of the applicants earns between 35000 to 80000 USD annually.
- Approx. 52% of the applicants applied loan for paying their other loans(Debt Consolidation)
- Approx. 48% of applicants are living in rented home whereas 42% applicants were mortgaged their home.
- Loan applicants are increasing year on year, approx. 47% of loan applicants received loans in 2011.
- Approx. 70% of applicants applied loan for 36 months term period.
- Heatmap tell that how 'loan_amnt’, 'funded_amnt' & 'funded_amnt_inv' are closely interrelated. 



## Contact
Created by [@githubusername] - feel free to contact me!
