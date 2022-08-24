# Introduction

Financial management is one of the things that is a concern in today's society. Therefore, a lot of tips and tricks have sprung up on how to manage finances effectively. There is also a proportion of expenditure based on daily needs, investment, insurance, taxes and others. However, there is a lot of barries to reach financial target especially by the people are the sandwich generation who have dependents outside themselves, lack of financial control, and low financial literacy.
Are you wondering how much money you spend on coffee? At what point you have to limit yourself to buy unnecessary thing? For you who still in phase of financial mess or financial security. Well, this project contains a data visualization of financial transactions to find out your spending habits and how to take wise decision for future financial planning.

# Content
1.	Aim
2.	Data Sourcing
3.	Tools
4.	Data Cleaning
5.	Exporatory Data Analysis
6.	Data Visualization
7.	Conclusion

# Aim
-	Gives the rough ideas of specific time to show any trends in spending habits.
-	Shows net worth based on total income and expenses.
-	Finds out any kind transactions that would be reduced.

# Data Sourcing
Your financial history records or if you haven’t made it, I recommend you to start your own and set sometimes to schedule your monthly evaluation. 
For this project, the dataset I will use is from [Kaggle](https://www.kaggle.com/datasets/bukolafatunde/personal-finance) which a have modified a little bit. Then, the columns were made of:
-	Date
-	Description
-	Amount
-	Transaction Type
-	Category
-	Account Name

# Tools
-	Google Sheets 
-	Google Data Studio

# Data Cleaning
After downloading dataset from Kaggle, I needed to clean the data in order to perform an Exploratory data analysis. Since the data contains small number of rows and columns, I only need to do data cleaning in Google Sheets.
1.	Firstly, I imported data to Google Sheets and validated every type of data then change into related data type.
2.	Checked if there is missing data. 
3.	After that, I checked and droped if there is any duplicates data.
4.	Deleted column ‘Account Name’ since it won’t be used for this project

# Exploratroy Data Analysis
-	Calucated field for Balance Scorecard: How’s the amout of current balance?
-	Scorecard for counting #Transactions, Total Income, Total Expense, Current Income and Current Expense for this month: How’s the quick overview of transactions?
-	Bar Chart by Category and Expense Amount: What category have the highest expense?
-	Bar Chart by Category and Income Amount: What category have given the highest income?
-	Pie Chart by Amount: How’s the proportion between income vs expense?
-	Table by Category and Amount: Which category has the highest count of transactions?
-	Table by Decription, Transaction Type, Date and Amount: What transactions have been made recently?
-	100% Stacked Column by Date, Transaction Type and Amount: How’s the pattern of income vs expense based on time?

# Data Visualization
After exploring the data, I then visualized it on Google Data Studio. Checkout the full project [here](https://datastudio.google.com/reporting/c99b0d95-c99a-4966-a7dc-cdbe2e0f78e5).
 ![Screenshot_4](https://user-images.githubusercontent.com/65482851/186356230-f04335a2-ff08-42c9-a2a6-362f56715036.jpg)


# Conlcusion
By reviewing your transactions history, hopefully it can at least help you to be more aware about your spending habits and go into the next month with more intention.
