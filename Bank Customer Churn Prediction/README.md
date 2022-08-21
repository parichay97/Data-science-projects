# Bank Customer Churn Prediction
Churn is defined in business terms as ‘when a client cancels a subscription to a service they have been using.’ A common example is people cancelling Spotify/Netflix subscriptions. So, Churn Prediction is essentially predicting which clients are most likely to cancel a subscription i.e ‘leave a company’ based on their usage of the service.

From a company point of view, it is necessary to gain this information because acquiring new customers involves lot of effor and costlier than retaining old ones. Hence, the insights gained from Churn Prediction helps them to focus more on the customers that are at a high risk of leaving.

Many factors influence the reasons for a customer to Churn. It may be the fact that there’s a new competitor in the market offering better prices or maybe the service they are getting has not been up to the mark, so on and so forth.

Hence, there is no correct answer as to why exactly the customer churned because there are many influencing factors.

## Data Description
Dataset consists of 10000 rows and 13 columns. Below is the detail about columns:

1. RowNumber
2. CustomerId - ID of the customer
3. Surname - Surname of the customer
4. CreditScore - Credit Score of customer
5. Geography - Customers location
6. Gender - Gender of customer
7. Age - Age of Customer 
8. Balance - Bank balance of Customer
9. NumOfProducts -  Number of Products customer has with bank
10. HasCrCard - Whether customer has credit card or not
11. IsActiveMember -  Whether customer is active or not
12. EstimatedSalary - Customer Salary
13. Exited - Whether customer stayed or left the bank

## Problem Statement 
To build a classifier which can determine whether customer will leave in the next 6 months or not?

Source of the data: https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling
