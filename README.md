# Lending Club Case Study
>   We are working for a consumer finance company which specializes in lending various types of loans to urban customers.
  The company wants to understand the strong indicators driving  loan defaults. The company can utilize this knowledge for its portfolio and risk assessment. 



## Table of Contents
* [General Info](#general-information)
* [Steps performed](#steps-performed)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

- When a person applies for a loan, there are two types of decisions that could be taken by the company:  
- Loan accepted: If the company approves the loan, follwing are the scenarios:
	*  Fully paid: Applicant has fully paid the loan.
	* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed.
	* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.  </p>
	* Loan rejected:The company had rejected the loan because the candidate does not meet their requirements etc.

#### Dataset:
Dataset is a .csv file containing information about past loan applicants and whether they ‘defaulted’ or not.
The analysis will not consider consumer variables since they were not available at the time of loan application. 
Rejected loans will not be a part of analysis since there is no transactional history of those applicants with the company.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps performed
* Data understanding - Data types, meaning of variables and the business requirement
* Data cleaning- missing values treatment and data manipulations
* Data Analysis - univariate analysis, bi-variate analysis and derived metrics
* Reocmmendations - deriving the factors driving defaulters and explanation of the trends observed

## Conclusions
- We have selected 3 numerical and 2 categorical variables displaying a pattern among defaulters.
* Loan Amount
* Annual income
* DTI
* Home ownership
* Purpose
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- libraries used:
* NumPy
* matplotlib
* seaborn
- Data File Format: MS Excel file
- Software platform used for analysis: Google Cloud (Colab (Python) & Drive), MS Excel & CSV Files, MS PowerPoint, Adobe PDF 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Mohini Aggarwal and LokSundar Ganthi have worked on this project to derive the most important driving factors for loan default.
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@mohinia09] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
