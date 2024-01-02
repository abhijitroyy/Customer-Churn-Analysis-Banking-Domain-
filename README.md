# RBC Customer Churn Analysis [Banking Domain]

Royal Bank of Canada is facing a drastic increase in the rate of customer churning. RBC must identify the root causes of the increased churn rate and proactively address these issues. Customer retention is often more cost-effective than acquiring new customers, making it a critical aspect of a successful business strategy. 

In this project, I have considered a dataset from RBC which contains the following data which helped me identify the root causes of the increased churn rate. 

Aim of the Project:

The Customer Churn analysis project aims to comprehensively understand, assess and draw meaningful insights from the growing population of customers leaving the bank. This analysis involves a multidimensional exploration of various aspects related to credit score, geography, age, tenure, salary, etc. 

## Data Dictionary 

CreditScore — This can affect customer churn since a customer with a higher credit score is less likely to leave the bank.
Geography — A customer’s location can affect their decision to leave the bank. 
Gender — It’s interesting to explore whether gender plays a role in a customer leaving the bank.
Age — This is certainly relevant since older customers are less likely to leave their bank than younger ones.
Tenure — Refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
Balance — Also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
NumOfProducts — Refers to the number of products that a customer has purchased through the bank. 
Estimated Salary — As with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
Bank DOJ — Date when the Customer associated/joined with the bank.

HasCrCard — Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
1 represents credit card holder
0 represents non-credit card holder

IsActiveMember — Active customers are less likely to leave the bank.
1 represents Active Member
0 represents Inactive Member

Exited—whether or not the customer left the bank.
0 represents Retain 
1 represents Exit

## Analysis Queries 

1. What is the total number of customers?
2. How many of the customers are active customers? 
3. How many inactive customers? 
4. How many customers have a credit card?
5. How many customers do not have a credit card?
6. What is the total number of exit customers?
7. How many customers are retained?
8. In a clustered column chart, show the total customers by year and active category. 
9. In a line chart, show the difference between exit customers and the previous month's exit customers, monthly.
10. In a pie chart, show the difference between exit customers by gender category. 
11. In a stacked bar chart, show the total number of exit customers by credit type. 
12. Present a table showing the churn % for every year and month starting from 2016 January to 2019 December. 

## Calculations using DAX: 

CALCULATE, SUM, COUNT, AVERAGE, DIVIDE, SWITCH, CALENDER, FIRSTDATE, LASTDATE, YEAR, MONTH, PREVIOUSMONTH

##  Outcomes: 



