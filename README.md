Credit Risk Prediction for Loan Approval - German Credit Data
=============================================================

## Analysis on German Credit Data using Python

In this Project, I have used German Credit Data to predict the credit risk for a customer using his socio-economic profile and demographics. Once the credit risk of the customer is known, his chances of getting a loan application approved can be determined. 

The dataset used is from UCI, Machine Learning Repository -[Statlog German Credit Data](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data) "German Credit Data")


When bank receives a loan application, it has to run a credit risk determination to determine if the applicant can repay the loan within committed time. In this study I am planning to use logistic binary regression to categorize the applicant into two different credit risks,

* If the applicant has a **good credit risk** (creditability = 1), then he is likely to repay his loan. The applicant has higher probability of loan application approval.

* If the applicant has a **low Credit Risk** (creditability =0), then he is not likely to repay his loan. So, the applicant has lower chances of getting his loan application approval.

In predictive analytics, the model is trained using classification algorithm using Binary logistic regression and it is then used to predict the credit risks for other customers. 

It is clear, the prediction has higher risk for the bank when the applicant falls in low credit risk category. The bank should ensure that the person is capable of paying back the borrowed amount.

So, this model can be used to by bank or approving authority to evaluate the risks associated with lending the money to a loan applicant. The project aims at minimizing the risk and maximize the profit of the bank. Both the factors are good from bank's perspective, the bank needs a decision rule regarding who to give approval or decline the approval. This model is efficiently help them to determine a right decision for loan approval.
