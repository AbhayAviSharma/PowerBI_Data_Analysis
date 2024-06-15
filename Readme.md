# Case Study: Unlocking Financial Insights in Banking Data

![banks](https://github.com/AbhayAviSharma/PowerBI_Data_Analysis/assets/131509148/9ae43750-9d71-4b64-8ce2-1d588cfc2c97)

## BACKGROUND :
As a data analyst at FinInsight Group, a consultancy specializing in banking analytics, we are equipped with two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The 'Banking Transactions' dataset records detailed transaction data, including types, amounts, dates, and branch information. The 'Customer Account Details' dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, and loan amounts. Our expertise is crucial in a sector where financial data drives strategic decisions in customer relationship management, risk assessment, and product offerings.

## OBJECTIVE :
Our task is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. 
Our goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. This analysis should include understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. Our insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively. 

## About the Data :

**Banking Dataset 1** ->

The "BankingDataset1.xlsx" file contains the following columns:
1. **TransactionID**: A unique identifier for each transaction. 
2. **AccountNumber**: The account number associated with the transaction. (Foreign Key)
3. **TransactionType**: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4. **Amount**: The amount of money involved in the transaction.
5. **TransactionDate**: The date when the transaction occurred.
6. **BranchCode**: The code of the bank branch where the transaction took place.
7. **Currency**: The currency in which the transaction was made.
8. **TransactionTime**: The time of day when the transaction occurred (in hours).

**Banking Dataset 2** ->

The "BankingDataset2.xlsx" file contains the following columns:
1. **AccountNumber**: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)
2. **AccountHolder**: The name of the account holder.
3. **AccountType**: The type of account (e.g., Credit, Loan, Checking).
4. **Balance**: The current balance of the account.
5. **InterestRate**: The interest rate applicable to the account.
6. **CreditScore**: The credit score of the account holder.
7. **OpeningDate**: The date when the account was opened.
8. **LoanAmount**: The amount of loan associated with the account (if applicable).
9. **AccountHolderDetails:** Details about account holders - employment sector, years at current residence, and city of residence etc.

## Dashboard Development (This is how our dashboard looks like) :

![PowerBI_db](https://github.com/AbhayAviSharma/PowerBI_Data_Analysis/assets/131509148/25c83873-0063-42f0-8fb8-3bd3333ff5bc)

### We can also see the working of interactive features in our dashboard :

![PowerBI_db2](https://github.com/AbhayAviSharma/PowerBI_Data_Analysis/assets/131509148/e791dc70-1870-46ed-b8c2-65a993e8f8ac)

- This Power BI project focused on data cleaning, modeling, and advanced analysis within the banking domain. The initial steps involved importing and examining datasets, merging data, handling missing values, and standardizing data types. Categorization of transaction types, analysis of account balances, currency exchange rate impact, and branch activity were explored. 
- Using DAX, correlations between interest rates and balances, loan amounts and credit scores, as well as account age and balance were analyzed. Advanced DAX techniques were applied to develop a risk assessment model, predict account growth, and identify unusual transactions. 
- The dashboard built in Power BI showcased key metrics, time-based analysis, interactive loan data exploration, and visualizations of transaction and account data. Overall, this project enhanced skills in data cleaning, modeling, DAX usage, dashboard design, and storytelling with data insights in the banking sector.

# Link to the project :
### https://drive.google.com/file/d/1M1BLLBanM13pV2PLvVZ7aHdeSk8uDvta/view?usp=sharing
