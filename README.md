# Credit Risk Analysis – Exploratory Data Analysis (EDA)

A complete Exploratory Data Analysis (EDA) project performed on a Credit Risk dataset to understand patterns related to loan approval, default behavior, and financial risk factors.

This project uses Pandas, NumPy, Matplotlib, Seaborn, and Python for detailed data exploration and visualization.

--------------------------------------------------------------------------------------------------------------------------------------------------
# 1. Project Overview
- The goal of this analysis is to examine:
- Applicant demographics
- Income and employment patterns
- Loan behavior
- Default tendencies
- Key relationships between variables
- Factors contributing to loan default

--------------------------------------------------------------------------------------------------------------------------------------------------
  
# 2. Dataset Description

The dataset contains information about loan applicants and their financial status.

  | Column                         | Type              | Description                                          |
| ------------------------------ | ----------------- | ---------------------------------------------------- |
| **person_age**                 | Numeric           | Age of the borrower                                  |
| **person_income**              | Numeric           | Annual income                                        |
| **person_home_ownership**      | Categorical       | RENT / OWN / MORTGAGE / OTHER                        |
| **person_emp_length**          | Numeric           | Years of employment                                  |
| **loan_intent**                | Categorical       | Purpose of loan (Personal, Medical, Education, etc.) |
| **loan_grade**                 | Categorical       | Loan grade (A = Best, G = Worst)                     |
| **loan_amnt**                  | Numeric           | Loan amount applied for                              |
| **loan_int_rate**              | Numeric           | Interest rate (%)                                    |
| **loan_status**                | Categorical (0/1) | 1 = Defaulted, 0 = Not Defaulted                     |
| **loan_percent_income**        | Numeric           | % of income used to pay loan (DTI)                   |
| **cb_person_cred_hist_length** | Numeric           | Credit history length (years)                        |

__________________________________________________________________________________________________________________________________________________

# 3. EDA Framework
A systematic approach to explore and understand the dataset.

# 3.1 Data Loading
- Load the dataset
- Display sample rows
- Check data types

# 3.2 Data Cleaning
- Handle missing values
- Remove duplicates
- Treat outliers
- Convert incorrect data types

--------------------------------------------------------------------------------------------------------------------------------------------------

# 4. Exploratory Data Analysis (EDA)
# 4.1 Univariate Analysis
- Age distribution
- Income distribution
- Loan intent distribution
- Home ownership distribution
- Loan grade distribution
- Loan amount & interest rate patterns

# 4.2 Bivariate Analysis
- Income vs Employment length
- Loan amount vs Interest rate
- Loan status vs Loan intent
- Loan status vs Home ownership
- Loan grade vs Loan amount

# 4.3 Multivariate Analysis
- Default rate across multiple dimensions
- Loan amount + interest rate + default status

--------------------------------------------------------------------------------------------------------------------------------------------------

# 5. Key Insights

- Higher loan amounts often correlate with higher interest rates
- Borrowers with shorter credit history tend to default more
- Loan purpose affects default probability (Medical & Personal show higher risk)
- Renters show higher default rates vs Owners/Mortgage holders
- Loan Grade F & G borrowers request larger loans due to financial stress
- Correlation among numerical columns is weak — default depends on multiple factors

--------------------------------------------------------------------------------------------------------------------------------------------------

# 6. Correlation Heatmap (Numerical Features)

- Most numerical relationships are weak
- Age and credit history show moderate positive correlation
- Income and loan amount show mild correlation
- Default is not strongly correlated with any single numeric feature

--------------------------------------------------------------------------------------------------------------------------------------------------

# 7. Visualizations Used
- Histograms
- Countplots
- Boxplots
- Scatterplots
- Barplots
- Heatmaps
- Pairplot (focused on important features)

--------------------------------------------------------------------------------------------------------------------------------------------------

# 8. Conclusion
This EDA provides a detailed understanding of credit risk patterns, highlighting that loan defaults are influenced by multiple factors, including:
!.Income level
2.Employment stability
3.Loan purpose
4.Loan grade
5.Credit history

The dataset reflects real-world lending behavior:
- High-risk borrowers request larger loans
- Renters & low-income applicants default more
- DTI & credit history are major indicators of risk
This analysis sets a strong foundation for building Machine Learning models for Credit Risk Prediction.

--------------------------------------------------------------------------------------------------------------------------------------------------

# 9. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
