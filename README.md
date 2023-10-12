# Collecting_Debts_by_Analyzing_Statute-Barred
#Problem Statement:
In the realm of debt collection, the ability to discern which accounts are statute-barred—thus potentially unrecoverable—holds immense significance. This project endeavors to develop a sophisticated machine-learning model aimed at accurately predicting the probability of successfully collecting debts by meticulously examining the statute-barred status of each account.
Given a dataset encompassing a multitude of attributes including original creditor information, account IDs, current balances, purchase dates, and a wealth of other pertinent features, the objective is to construct a predictive model that excels in identifying accounts where the statute barred status may influence the likelihood of debt retrieval.
The focal point of this endeavor centers on the IsStatBarred field, which serves as the pivotal target variable for classification. 


#Data Definition
EntityID: Unique identifier for each entry.
OriginalCreditor[Redacted]: Name of the original creditor, with sensitive information redacted.
AccountID: Unique identifier for the account.
CurrentBalance: The current balance of the account.
DebtLoadPrincipal: The principal amount of the debt load.
BalanceAtDebtLoad: The balance at the time of debt load.
PurchasePrice: The price at which the debt was purchased.
8. ProductOrDebtType: Type of product or debt.
9.CollectionStatus: Status of the debt collection
10.IsStatBarred: Indicates if the debt is statute-barred. (target variable)
11.CloseDate: The date when the account was closed.
12. Closure Reason: Reason for closing the account.
13. InBankruptcy: Indicates if the account is involved in bankruptcy.
14. AccountInsolvencyType: Type of insolvency related to the account.
15. CustomerInsolvencyType: Type of insolvency related to the customer.
16. IsLegal: Indicates if legal action has been taken.
17. Interest Rate: Interest rate associated with the debt.
18. LastPaymentAmount: Amount of the last payment made.
19. LastPaymentMethod: Method used for the last payment.
20. NumLiableParties: Number of liable parties associated with the account.
21. CustomerAge: Age of the customer.
22. NumPhones: Number of phone contacts associated with the customer.
23. NumEmails: Number of email contacts associated with the customer.
24. NumAddresses: Number of addresses associated with the customer.

