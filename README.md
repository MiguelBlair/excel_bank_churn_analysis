# Excel Customer Churn Analysis

## Project Overview
This project focuses on analyzing customer churn in the banking sector, utilizing a dataset to derive insights from customer demographics and purchasing behaviors. The goal is to understand how different customer groups influence retention and profitability, aiding banks in refining marketing strategies and enhancing customer engagement.

## Data Collection
The dataset, provided by Radheshyam Kollipara, is in CSV format. The initial step involved loading the data into Excel for previewing and identifying key insights.

### Initial Data Preview
```python
import pandas as pd

df = pd.read_csv('Data_sets/bank_data.csv')
df
```
The dataset consists of 10,000 rows and 18 columns:
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited
- Complain
- Satisfaction Score
- Card Type
- Point Earned

## Goals
1. **Credit Score Distribution by Geography**: Analyze regional credit score trends.
2. **Impact of Age and Tenure**: Investigate how age and tenure affect product usage.
3. **Correlation Analysis**: Explore the correlation between customer balance, credit score, geography, and tenure.
4. **Gender Comparison**: Assess differences in credit score, balance, and product usage between male and female customers.

## Data Cleaning
The data was relatively clean but required better formatting and a staging copy to ensure data integrity.

### Steps Taken
- Created a duplicate of the original table for analysis.
- Checked for duplicates and null values.
- Filtered relevant columns into a new table.

## Data Analysis
### 1. Credit Score Distribution
Used a pivot table to analyze average credit scores by geography. The findings show that Germany has the highest average credit score at 651.45.

### 2. Age and Tenure Impact
Added columns for age and tenure ranges. The analysis indicated that younger age groups and customers with 1-2 years of tenure tend to use more products.

### 3. Correlation Analysis
Examined correlations between balance and credit score, geography, and tenure. Results highlighted that customers with longer tenure generally have higher balances.

### 4. Gender Differences
Analyzed average credit scores, balances, and product usage between genders, revealing that female customers have slightly higher engagement metrics.

## Summary of Findings
- **Credit Score Distribution**: Slightly higher creditworthiness in Germany and Spain compared to France.
- **Product Usage Trends**: Tenure plays a significant role in product adoption.
- **Balance Correlation**: Longer tenure correlates with higher balances, especially in Germany.
- **Gender Engagement**: Female customers show higher engagement than male customers.

## Conclusion
This project provides insights that can help banks tailor their marketing strategies and improve customer engagement efforts.

## Acknowledgements
Thank you for your time. If you have any suggestions for improving this project, feel free to comment.

[enter closing here]