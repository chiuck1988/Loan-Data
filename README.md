# Loan-Data
This project involves analyzing data from LendingClub.com, a platform that links borrowers seeking funds with investors. The goal is to develop a predictive model determining whether a borrower is probable to repay their loan. The dataset columns correspond to the following aspects:

- credit_policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- purpose: The purpose of the loan
- int_rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
- installment: The monthly installments owed by the borrower if the loan is funded.
- log_annual_inc: The annual income of the borrower.
- dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income * 100).
- fico: The FICO credit score of the borrower.
- days_with_cr_line: The date the borrower has had a credit line. (represented as a numerical format. For instance, January 1, 1900, is denoted by the number 1, January 2, 1900, is represented as 2, and so forth).
- revol_bal: The borrower's revolving balance (amount unpaid at the end of the billing cycle).
- revol_util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available, a rate of 67.4% would be stored as 0.674)).
- inq_last_6mths: The borrower's number of inquiries by creditors in the last 6 months.
- delinq_2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
- pub_rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
- not_fully_paid: information indicating whether the loan will be repaid or not (1: fully repaid; 0: not fully repaid)
