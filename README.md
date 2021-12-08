# Lending Club Case Study
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default 
cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company:

   1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:

       I. **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate).</br>
       II. **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.</br>
       III. **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
- The percentage of charged off loans increase with increase in loan amount range. Even though, most of the loans are below 20000 amount. The higher loans, carry significant risk of default
- Charged off rate is higher for the long term loans. It is risky to give higher loan amount with longer payment terms.
- Small business has more loan defaults than the renewable energy and education loans.
-  As per the analysis, it is evident that the loan default increases when the interest rate is high.
-  The charged off rate is high when the annual income is low.



## Technologies Used
- Python 3 and following python based libraries used numpy, pandas and matplotlib and seaborn

## Acknowledgements
- This [forum](https://stackoverflow.com/) helped a lot to draw different plots based on the requirement.


## Contact
Created by [@baskiaiml] and [@libvenus]- feel free to contact us!
