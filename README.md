# Retention-Analysis-Case-Study
Retention Analysis performed in dataset aggregated by a Spanish Bank
A Spanish Bank has been collecting data on multiple facets of customer behavior. Currently
the data science team at the bank is trying to help in developing strategies to retain
customers.
A team of data warehousing experts have already collected data that the management
thinks could be helpful in doing the relevant analysis.
The dataset extracted has following variables:
Varaiables Description
gender Gender of Customer
age Age of Customer
gross_income Annual income
segment Segment as specified by the bank
num_credit_cards Number of credit cards issued (through cross sell)
tiprel_1mes Customer Inactivity Flag at the beginning of the period (A-Active, I-Inactive)
ind_actividad_client
e Customer Inactivity Flag at the end of the period (6 Months) (1-Active, 0-Inactive)
num_Products Total number of financial products that the customer has bought (through cross sell)
num_loans Total number loans disbursed to the customer (through cross sell)
duration Number of days since customer
This data has been extracted as a json file named ‘retention.json’. In order to study the
behaviour of customers who become inactive, the data from datawarehouse was pulled for
a duration of 6 months and within this duration it was observed which customers were
active or inactive in the beginning of the six month window and which customers are
active/inactive after the 6 month time window.
