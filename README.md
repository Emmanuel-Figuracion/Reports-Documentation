# E-Commerce Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights assess the profitability of their loan portfolios by analysing data related to interest income, loan origination costs, default rates, and collection efforts.

![Summary](https://github.com/Emmanuel-Figuracion/Reports-Documentation/blob/main/Bank%20Loan%20Report%20Summary.PNG)
![Overview](https://github.com/Emmanuel-Figuracion/Reports-Documentation/blob/main/Bank%20Loan%20Overview%20Report.PNG)
![Details](https://github.com/Emmanuel-Figuracion/Reports-Documentation/blob/main/Bank%20Loan%20Report%20Details.PNG)


### Data Sources

Bank Loan Data: The primary dataset used for this analysis is the "financial_loan_final.csv" file, containing detailed information about each loan lend by the company.

### Tools

- Excel - Data Cleaning and Validation
  - [Download here](https://github.com/Emmanuel-Figuracion/Reports-Documentation/blob/main/financial_loan_final.csv)
- SQL Server - Data Query Analysis
- Looker Studio - Creating reports


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection, profiling
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA Exploratory data analysis involved exploring the sales data to answer key questions, such as:

- What is the company's performance overall, MTD, MoM?
- Which products are top sellers?
- What are the peak sales periods?

### Data Analysis

Include some interesting code/features worked with

```sql
SELECT * FROM table1
WHERE cond = 2;
```

### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References

1. SQL for Businesses by werty.
2. [Stack Overflow](https://stack.com)

😄

💻

|Heading1|Heading2|
|--------|--------|
|Content|Content2|
|Python|SQL|

`column_1`

**bold**

*italic*
