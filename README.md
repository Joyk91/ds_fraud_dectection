# Fraud Detection Model

## Exploratory Data Analysis and Model Fitting on Credit Scoring Data

### Question

Olivia, a manager at a local financial institution has contacted you. She is asking you for assistance in
assessing the credit worthiness of future potential customers. She has a data set of 793 past loan customer
cases, with 14 attributes for each case, including attributes such as financial standing, reason for the loan,
employment, demographic information, foreign national, years residence in the district and the
outcome/label variable Credit Standing - classifying each case as either a good loan or bad loan.
The manager has 10 new customers, which she would like to know if she should consider them good or bad
prospective loans.


#### Data Details
Most of the attributes are self-explanatory; the name of some of the attributes are somewhat cumbersome but this is what you have been given; here are the further details of some of them:
Checking Acct - What level of regular checking account does the customer have –No acct, 0balance, low (balance), high (balance)
Credit History – All paid – no credit taken or all credit paid back duly
Bank Paid – All credit at this bank paid back
Current – Existing loan/credit paid back duly till now
Critical – Risky account or other credits at other banks
Delay – Delay in paying back credit/loan in the past
Months Acct – The number of months the customer has an account with the bank.

Using R help Olivia to answer the following questions.

1. Exploratory Data Analysis (EDA): - Carry out some EDA on the data set; carry out at least one trivariate analysis; do you notice anything unusual or any patterns with the data set? Detail these and outline any actions you propose to take before you start model building in part b).
2. Explain how a ROC curve operates and when this is used as a performance metric.
3. Build a decision tree model and give your decision tree, detailing its parameters. Explain how you decided on/fined tuned these parameters. (Include an image of your tree as well as a text output description.). Use set.seed(abc) where abc are the last 3 digits of your student no. Use this set.seed for all other model building below.
4. Use the decision tree to apply a model to the scoring set. Choose 3 different potential loan clients and explain to Olivia in plain English how the decision tree works (15 marks) and how the accuracy/probabilities of these being a good/bad loan was calculated by the decision tree (5 marks).
5. Now try and improve your model using 2 other approaches, e.g. ensemble technique, boosting or a different model. Comment on your results and analyse why your model is giving better/worse results. 20 marks
6. Although the dataset is balanced fairly well here between good and bad loans Olivia tells you now that this is often not the case. Also the cost of misclassification is in the ratio of 1:5 between falsely classifying actual bad as good and falsely classifying actual good as bad. Redo your best model and comment how your answer changes.
7. Olivia’s company uses a process that is a mixture of a grading system and human input to grade each past loan as good or bad. Olivia is suspicious that during a particular time that this process performed very poorly and produced inaccurate results. Using R or Excel can you find a series of consecutive or nearly consecutive ID numbers of circa 10 or more, i.e. where these gradings show a suspiciously incorrect pattern. Detail how you go about your investigation and how you found this pattern.
