# Lending Club Case Study

> This is a Lending club case study in which we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
> When a person applies for a loan, there are two types of decisions that could be taken by the company:
> Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
> Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
> Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
> Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
> The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- EDA involves understanding the data and importance of the variables
- Enriching the existing dataset by deriving new columns
- Cleaning empty or duplicate data points
- Removing attributes that does not contribute to the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- As more borrowers defaulted on loans with terms of 60 months when the loan amount is higher, lending company should reduce such high amount loans having 60 months tenure.
- Lending company should thoroughly investigate loan applications for F, G and E grade loans as they are more prone to loan default. Also they should rethink on the Loans amounts for these grades.
- Loan applications from borrowers staying on Rent or Mortgage should be well examined before approving high loan amounts.
- For the borrowers residing in CA, NY, and FY a little more scrutiny is required. In addition to that if we compare the total number of loans issued in FL and NY, FL has more defaulters than NY which adds FL to the scrutiny list.
- Loans borrowed with the purpose of debt consolidation by small businesses resulted in more defaults. The company should reduce issuing loans to small businesses.
- Higer the DTI ratio, more is the default rate for credit card and deb consolidation loans. Lending company should reduce the credit and deb consolidation loans for the people with high DTI ratio

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Correlation Map and Understanding Entire dataset as well as subset of Loan Default
- Univariate Analysis
- Bivariate Analysis

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@nikitapatil1122] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># LendingClubCaseStudy
