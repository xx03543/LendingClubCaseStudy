# Project Name
Identify patterns which indicate if a person is likely to default, while taking loans 
Identify risky loan applicants using EDA, and such loans can be reduced thereby cutting down 
the amount of credit loss. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Background: The aim is to identify patterns which indicate if a person is likely to default, 
  which may be used for taking actions such as denying the loan, reducing the amount of loan, 
  lending (to risky applicants) at a higher interest rate, etc. 

Inclusions
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

Data Set and Exclusions
We are using a loan data from 2007 to 2011 - 4 years data where we only consider the loan approved cases.
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Conclusions
Most of loan applicants are either rented or mortgaged.
Maximum of loan application are for credit card payment and debt consolidation.
Home improvement and major purchases are other popular reasons of loan application.
Most applicants are from California state and then New York and Texas.
Majority of loan applicants are vastly experienced professional, i.e. more than 10 years.
Most people have multiple credit lines linked with them.


## Technologies Used
- library - Numpy
- library - Pandas
- library - Seaborn
- library - matplotlib

## Acknowledgements
https://core.ac.uk/download/pdf/234629128.pdf

