## **Exploratory Data Analysis on Credit Card Dataset**

### **Project Overview**

This project performs Exploratory Data Analysis (EDA) on a credit card dataset to understand customer financial behavior and credit risk patterns.The analysis focuses on cleaning raw financial data and identifying patterns related to spending behavior, debt ratio, credit utilization, and payment delays.
The goal is to extract meaningful insights that help understand factors influencing credit risk and Non-Performing Assets (NPA). 


### **Introduction**

Credit card data contains information about customer spending, payment history, and credit usage behavior.This project focuses on applying Exploratory Data Analysis techniques to understand customer financial patterns and identify potential credit risk indicators.EDA helps transform raw data into useful 
insights for financial analysis and decision making. 


### **Why This Project?**

This dataset was chosen because credit risk analysis is an important real-world problem in the banking industry.

#### **The project helps analyze:**

- Customer spending patterns

- Credit utilization behavior

- Payment delay patterns

- Financial risk indicators

- It also strengthens data cleaning and EDA skills which are important for data analyst roles. 


### **Dataset Details**

- Dataset Type: Credit Card Default Data

- Records: ~150,000 rows

- Features: 18 columns

- Data Types: Numerical & Categorical


### **Key Columns:**

- NPA Status – Indicates non-performing assets

- RevolvingUtilizationOfUnsecuredLines – Credit usage ratio

- Age – Customer age

- MonthlyIncome – Monthly income

- DebtRatio – Debt to income ratio

- Late Payment Variables – 30–59, 60–89, 90 days late


### **Technologies & Libraries Used**

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook 


### **Data Cleaning & Preparation**
- Steps Performed

- Loaded dataset using Pandas

- Checked dataset structure and shape

- Identified missing values

- Handled missing values in MonthlyIncome and NumberOfDependents

- Checked duplicate records

- Verified and corrected data types

- Prepared the dataset for analysis

- These steps ensured data consistency and accurate analysis. 


## **Exploratory Data Analysis**

### **Univariate Analysis:**
Univariate analysis studies individual variables to understand their distribution.

Visualizations Used:

- Pie Chart – categorical distribution

- Box Plot – numerical variable analysis

- Count Plot – frequency of categorical variables

### **Key Observations:**

- Monthly income shows high-value outliers

- Income distribution is right-skewed

- Professional and Graduate education categories dominate

- Dataset shows gender imbalance

    - Male ≈ 61.5%

    - Female ≈ 38.5% 


### **Bivariate Analysis:**

Bivariate analysis studies the relationship between two variables.

Visualizations Used:

- Count Plot (Categorical vs Categorical)

- Violin Plot (Categorical vs Numerical)

- Scatter Plot (Numerical vs Numerical)


### **Key Observations:**

- Male customers dominate both own-house and rented categories

- Customers living in own houses are more than renters

- Non-NPA customers are mostly in the middle-age group

- Age alone does not strongly determine NPA risk

- Higher credit utilization appears with fewer open credit lines 



### **Multivariate Analysis:**

Multivariate analysis examines relationships among multiple variables simultaneously.

- Techniques Used

- Correlation Heatmap

- Violin Plot

### **Key Observations:**

- Age shows very weak correlation with income and debt ratio

- Debt ratio has weak correlation with income

- Number of dependents shows negative correlation with age

- Bad customers tend to have higher and more spread debt ratios 


## **Key Insights**

From the analysis:

- Most customers are good customers (non-NPA)

- Some customers have very high debt compared to income

- Customers with late payment history are more likely to become NPA

- Income alone does not determine financial risk

- Credit utilization and payment behavior are stronger indicators of risk 



## **Conclusion:**

This project applied Exploratory Data Analysis on a credit card dataset to understand customer financial behavior.After cleaning the dataset, different analytical techniques such as univariate, bivariate, and multivariate analysis were used to uncover patterns.

The analysis shows that debt ratio, credit utilization, and payment delays play a significant role in determining credit risk, while income alone is not a strong indicator of default risk. 

