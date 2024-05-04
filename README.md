# Lending Club Case Study

**Lending Club is US based peer-to-peer consumer finance company founded in 2007.

Lending Club specialises in lending various types of loans to urban customers.

LendingClub matches borrowers with investors willing to fund their loans.**

> When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

## Dataset

![Loan Dataset](Loan_image.png)

[Loan Zip file](dataset/loan.zip)

[Loan CSV file](dataset/loan.csv)

[Data dictionary for the fields used](dataset/Data_Dictionary.csv)

## Table of Contents

- [Problem Statement](#problem-statement)
- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

## Problem Statement

### Business Understanding

When a person applies for a loan, there are two types of decisions that could be taken by the company:

**Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

**Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 

In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## General Information

- Steps for EDA :
<ol>
    <li>Data Understanding</li>
    <li>Data Cleaning</li>
    <li>Univariate Analysis</li>
    <li>Bivariate Analysis</li>
    <li>Multivariate Analysis</li>
    <li>Conclusion</li>
</ol>
- Data Set : Loan Lending Club loans

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusion: 


## Continuous Variable:

- Loans exceeding $15,000 exhibit a higher likelihood of borrower default.
- Funding amounts surpassing $15,000 correlate with elevated default rates.
- Investments exceeding $15,000 demonstrate a higher tendency for default.

## Interest Rate Influence:

- A notable increase in default rates accompanies rising interest rates.

## Income and Debt-to-Income Ratio (DTI):

- Elevated annual incomes correspond to reduced default rates.
- Conversely, increasing DTI correlates with heightened default rates.

## Influence of Academic Achievement and Income:

- Higher incomes coupled with favorable academic performance typically result in fewer defaults.

## Creditworthiness Assessment:

- Grades and subgrades predominantly reflect the creditworthiness of borrowers.

## Categorical Variable:

- Loan terms of 60 months exhibit a higher default propensity compared to 36-month terms.
- Default rates escalate as the grade (A, B, C, D, E, F, G) decreases.
- Similarly, default rates rise with decreasing subgrade (A1, A2, B1, B2, etc.).

## Verification and Borrower Type:

- Verified borrowers tend to display a higher percentage of defaulted loans.
- Small business borrowers are associated with a heightened default risk.

## Geographical Influence:

- The percentage of defaulted loans is notably higher in states like NE and relatively elevated in NV and SD.



## Technologies Used

- matplotlib - 3.7.1
- Python 3.10.11
- seaborn - 0.12.2
- pandas - 2.0.2
- numpy - 1.24.3

## Acknowledgements

- This project was group case study for an online advance course.
- https://www.kaggle.com/
- https://learn.upgrad.com/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/
- https://www.geeksforgeeks.org/

## Contact

Created by [@aravindvcyber] feel free to contact me!
