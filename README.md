# In-Depth-Analysis-of-Prosper-Loan-Data-
A thorough Exploratory Data Analysis (EDA) of the loan dataset was conducted to reveal critical trends, patterns, and relationships among different loan attributes. Through data visualization and in-depth analysis, the objective is to derive meaningful insights into loan performance, borrower profiles, and market dynamics. 📊🏦


> **_NOTE:_** In order to Run the Project you need to unzip prosperLoanData.csv and LoanDataCleaned.csv    

# Introduction
This dataset contains the customer's data from a loan company known as Prosper. This dataset comprises of 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

# Dataset Description
This dataset contains the customer's data from a loan company known as Prosper. This dataset comprises of 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> **_NOTE:_** You can get detailed information about each variable from [Here](https://github.com/shantiNaser/In-Depth-Analysis-of-Prosper-Loan-Data/blob/main/Part_I_exploration_template.ipynb)


# Example from code for question-visualization-observations pattern

### What is the distribution of the Loan Original Amount?

![image](https://github.com/user-attachments/assets/070df578-0bee-4554-a6b4-d82dd9adbfc1)

> The loan amounts are mostly small and have a right-skewed distribution with a few large loans standing out. This suggests there are different groups of borrowers. Even though there are some large, less common loans, they are valid and don’t need any special treatment.


### Does employment status affect the Credit Score Range?

![image](https://github.com/user-attachments/assets/5266030e-27c8-48e8-ae4d-95b7944d6b57)

  > Employed borrowers exhibit a broad range of credit scores, including some high outliers, which suggests that while most have moderate to high credit scores, a few have exceptionally high ones. Borrowers categorized as "Other" and "Full-time" generally have higher credit scores compared to employed borrowers, with similar distributions and some notable high outliers, indicating that some within these groups possess excellent credit. On the other hand, self-employed borrowers tend to have lower credit scores, characterized by a narrower range and fewer outliers. Not employed borrowers show the lowest and least variable credit scores, pointing to potential financial instability or limited credit history.

  
### How does the number of investors relate to the loan amount?
![image](https://github.com/user-attachments/assets/07e8626f-1412-4e01-9e10-a099d0941609)

  > There is a positive correlation between the number of investors and the Loan Amount, with a correlation of 0.32 This indicates that as the number of investors increases, the loan amount also tend to increase.

  > Some outliers are observed, with loans having over 600 investors and Loan amount exceeding 25000.


### How does the original loan amount vary across different income ranges and loan statuses?

![image](https://github.com/user-attachments/assets/2483a151-8713-4f99-b070-f5fd725c1a9b)

  > People with higher incomes tend to borrow more money. This is shown by the taller bars for higher income groups. However, the biggest loans are not always taken by the richest people. It might be because people with higher incomes are less likely to default on their loans. We should look into this further. In general, people with incomes over $100,000 borrow the most, no matter if they’ve paid back their loan or not.

### How do loan amount, monthly payment, and credit score vary across different borrower states and employment statuses?

![image](https://github.com/user-attachments/assets/108a4d86-8845-46e5-89e8-f3292554ed82)




