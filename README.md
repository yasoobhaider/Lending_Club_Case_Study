**Lending Club Case Study**
> This project is to analyze the factors responsible for financial risk in approving or denying a loan.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Following business problem we are trying to address here-
  
 ** Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:
      Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not       
               labelled as 'defaulted'.
  **Charged-off:** Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

  The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of   
  default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- Data set utilized is the loan data from bank which consists of all the loans disbursed for a certain duration.

## Conclusions
- Interest rate is driving factor for loan repayment.
- Borrowers having grade E, F and G applied for large loan amount and as they paid for the same, so they can be considered as regular.
- Loans related to credit card repayment or debt consolidation has loans which are large in numbers and higher probability for repayments.



## Technologies Used
- Python - version 3.12.2
- Numpy Library - version 1.26.4
- Pandas library - version 2.2.2
- Seaborn Library - version 0.13.2
- Matplot Library - version 3.8.4

## Acknowledgements
Give credit here.
- This project was inspired by upgrad program for analytics

## Contact
Created by [@yasoobhaider] - feel free to contact me!

<!-- ## License -->
<!-- This project is open source and available. -->
