# Lloyds Banking Group Data Challenge

Lloyds Banking Group is launching a new loans product. Prior to the launch they would like you to use historical customer data to:
* Task 1 – Data Strategy : Understand and summarise the different behaviours or attributes between customers who paid back their loan and customers who did not
* Task 2 – Data Science: To use the historical data to design a process which predicts the likelihood of a new customer not paying back their loan


* Number of records: 18,324


| Field Number | Field Name             | Data Type          |  | Description (optional)                                                                                                                                          |
| ------------ | ---------------------- | ------------------ |  | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              |                        |                    |  |                                                                                                                                                                 |  |
| 1            | id                     | Unique Identifer   |  | A unique ID for the loan listing.                                                                                                                               |  |
| 2            | addr_state             | Categoric Variable |  | The US state provided by the borrower in the loan application (address)                                                                                         |  |
| 3            | annual_inc             | Numeric Variable   |  | The annual income provided by the borrower during registration.                                                                                                 |  |
| 4            | emp_length             | Categoric Variable |  | Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years. Data captured as categorical. |
| 5            | emp_title              | Categoric Variable |  | The job title supplied by the Borrower when applying for the loan.                                                                                              |  |
| 6            | home_ownership         | Categoric Variable |  | The home ownership status provided by the borrower during registration. Our values are: RENT, OWN, MORTGAGE, OTHER                                              |  |
| 7            | installment            | Numeric Variable   |  | The monthly payment owed by the borrower if the loan originates.                                                                                                |  |
| 8            | loan_amnt              | Numeric Variable   |  | The listed amount of the loan applied for by the borrower.                                                                                                      |  |
| 9            | purpose                | Categoric Variable |  | A category provided by the borrower for the loan request.                                                                                                       |  |
| 10           | term                   | Categoric Variable |  | The number of payments on the loan. Values are in months and can be either 36 or 60.                                                                            |  |
| 11           | int_rate               | Numeric Variable   |  | Interest Rate on the loan                                                                                                                                       |  |
| 12           | avg_cur_bal            | Numeric Variable   |  | Average current balance of all current credit lending products / accounts                                                                                       |  |
| 13           | inq_last_12m           | Numeric Variable   |  | Number of credit inquiries (searches) in past 12 months                                                                                                         |  |
| 14           | max_bal_bc             | Numeric Variable   |  | Maximum current balance owed on all revolving accounts (a revolving account is a credit card or overdraft where the balance can fluctuate month on month)       |  |
| 15           | mo_sin_old_il_acct     | Numeric Variable   |  | Months since oldest bank installment account opened                                                                                                             |  |
| 16           | mo_sin_old_rev_tl_op   | Numeric Variable   |  | Months since oldest revolving account opened                                                                                                                    |  |
| 17           | mo_sin_rcnt_rev_tl_op  | Numeric Variable   |  | Months since most recent revolving account opened                                                                                                               |  |
| 18           | mo_sin_rcnt_tl         | Numeric Variable   |  | Months since most recent account opened                                                                                                                         |  |
| 19           | mort_acc               | Numeric Variable   |  | Number of mortgage accounts.                                                                                                                                    |  |
| 20           | mths_since_last_delinq | Numeric Variable   |  | The number of months since the borrower's last delinquency (missed payment).                                                                                    |  |
| 21           | num_bc_tl              | Numeric Variable   |  | Number of bankcard accounts                                                                                                                                     |  |
| 22           | num_il_tl              | Numeric Variable   |  | Number of installment accounts                                                                                                                                  |  |
| 23           | num_op_rev_tl          | Numeric Variable   |  | Number of open revolving accounts                                                                                                                               |  |
| 24           | num_tl_90g_dpd_24m     | Numeric Variable   |  | Number of accounts 90 or more days past due in last 24 months                                                                                                   |  |
| 25           | num_tl_op_past_12m     | Numeric Variable   |  | Number of accounts 90 or more days past due in last 24 months                                                                                                   |  |
| 26           | open_acc               | Numeric Variable   |  | The number of open credit lines in the borrower's credit file.                                                                                                  |  |
| 27           | percent_bc_gt_75       | Numeric Variable   |  | Percentage of all bankcard accounts > 75% of limit.                                                                                                             |  |
| 28           | pub_rec_bankruptcies   | Numeric Variable   |  | Number of public record bankruptcies                                                                                                                            |  |
| 29           | total_acc              | Numeric Variable   |  | The total number of credit lines currently in the borrower's credit file                                                                                        |  |
| 30           | total_bal_ex_mort      | Numeric Variable   |  | Total credit balance excluding mortgage                                                                                                                         |  |
| 31           | loan_status            | Categoric Variable |  | Current Status of Loan where customers have fully paid back their loan OR did not pay back their loan, in which case they are flagged as Charged-off            |  |
|              |                        |                    |  |                                                                                                                                                                 |  |
