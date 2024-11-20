# Credit-Card-Spending-Financial-Insights-Dashboard

## Project Objective

The objective of this Power BI dashboard is to analyze a dataset and generate a comprehensive report to facilitate strategic decision-making for stakeholders. By leveraging the insights provided, stakeholders can identify patterns and trends in credit card usage, enabling them to optimize features to potentially increase revenue.

## Dataset Overview

This project utilizes an American credit card transaction dataset from January 2023 to December 2023. The dataset consists of two Excel sheets: "credit_card.xls" and "customers.xls", which contain crucial information regarding credit card transactions and customer details.

### Data Description

#### credit_card.xls

- **Client_Num**: Unique customer identification number.
- **Card_Category**: Category of the credit card (e.g., Blue, Gold, Platinum).
- **Annual_Fees**: Annual fee for the credit card.
- **Activation_30_Days**: Whether the card was activated within 30 days (0 or 1).
- **Customer_Acq_Cost**: Cost of acquiring the customer.
- **Week_Start_Date**: Start date of the week.
- **Week_Num**: Week number.
- **Qtr**: Quarter of the year (Q1, Q2, Q3, Q4).
- **current_year**: Year of the data.
- **Credit_Limit**: Maximum credit allowed.
- **Total_Revolving_Bal**: Total outstanding balance.
- **Total_Trans_Amt**: Total transaction amount.
- **Total_Trans_Vol**: Total number of transactions.
- **Avg_Utilization_Ratio**: Credit card balance to credit limit ratio.
- **Use Chip**: Whether the transaction was made using a chip (Chip or Swipe, Online).
- **Exp Type**: Type of expense (e.g., Travel, Entertainment, Bills, Grocery, Fuel).
- **Interest_Earned**: Interest earned on the outstanding balance.
- **Delinquent_Acc**: Whether the account is delinquent (1 or 0).

#### customers.xls

- **Client_Num**: Unique customer identification number.
- **Customer_Age**: Age of the customer.
- **Gender**: Gender of the customer (M for Male, F for Female).
- **Dependent_Count**: Number of dependents.
- **Education_Level**: Highest education level of the customer.
- **Marital_Status**: Marital status (Single, Married, Divorced).
- **state_cd**: State code where the customer resides.
- **Zipcode**: Zip code.
- **Car_Owner**: Whether the customer owns a car (yes/no).
- **House_Owner**: Whether the customer owns a house (yes/no).
- **Personal_loan**: Whether the customer has a personal loan (yes/no).
- **contact**: Preferred contact method.
- **Customer_Job**: Job role of the customer.
- **Income**: Annual income of the customer.
- **Cust_Satisfaction_Score**: Satisfaction score of the customer.

## Dashboard Overview

The Power BI dashboard is composed of two main pages, each focused on specific aspects of the analysis:

### 1. Customers Demographic Page
This page provides an in-depth analysis of customer demographics.

#### Key Performance Indicators (KPIs):

- **Total Customers**: 10,110 customers.
- **Male Customers**: 4,228.
- **Female Customers**: 5,880.
- **Average Customer Satisfaction Score**: 3.19.

#### Additional Visualizations:

- **Car Ownership**: 6,044 customers do not own a car, and 4,064 own one.
- **Marital Status**: 5,128 married, 4,236 single, 744 unknown marital status.
- **Customers by State Code and Gender**: Depicts the distribution of customers across states like California, Texas, New York, Florida, and New Jersey.
- **Customers by Job Type and Gender**: Shows the number of customers by job type.
- **Customers by Age Group**: Highest concentration in the 40-50 age group.
- **Customers by Income Group**: Most customers belong to the low-income group.
- **Customers by Education Level**: Most customers hold a graduate degree.

### 2. Customers Transaction Page
This page focuses on transaction-related KPIs and insights.

#### Key Performance Indicators (KPIs):

- **Total Revenue**: $55 million.
- **Total Transactions**: 656,000.
- **Transaction Amount**: $45 million.
- **Interest Earned**: $7.8 million.

#### Additional Visualizations:

- **Revenue Trend by Date**: A line chart showing revenue fluctuations over time.
- **Quarterly Revenue by Transaction Count**: Q3 generated the highest revenue of $14.2 million.
- **Revenue by Card Category**: The Blue card category generates the highest revenue, transaction amount, and interest.
- **Revenue by Use Method**: Swipe transactions generated the highest revenue.
- **Revenue by Gender**: $30 million from male customers and $25 million from female customers.
- **Revenue by Marital Status**: Married customers contributed the highest revenue ($28 million).
- **Revenue by Expenditure Type**: Bills generated the highest revenue ($14 million).
- **Revenue by Customer Job**: Business owners and white-collar workers generate the highest revenue.
- **Revenue by State Code**: Texas ($12.8 million) and New York ($12.7 million) are the highest revenue-generating states.

## Target Customer Segments

Based on the analysis, the following customer segments are identified as potential targets:

- **Graduate Degree Holders**: Majority of customers have a graduate degree.
- **Middle-Aged Individuals (40-50 age group)**: The highest number of customers are in this age group.
- **Low to Middle-Income Group**: Most customers belong to the low-income group.
- **Blue Card Category Holders**: This category generates the most revenue.
- **Business/White-Collar Job Holders**: Customers in these sectors generate the highest revenue.

## Recommendations

- **Promote Rewards and Benefits**: Market rewards, cashback, and benefits associated with the Blue card to increase customer engagement.
- **Targeted Marketing Campaigns**: Focus on middle-aged individuals, emphasizing tailored financial solutions.
- **Financial Education and Planning**: Offer financial education workshops to help low-income customers improve financial literacy.
- **Personalized Offers**: Use data analytics to provide offers based on customer preferences and behavior.
- **Customer Retention Strategies**: Implement loyalty programs, personalized communication, and proactive customer service to improve retention.

By implementing these strategies, the company can target the right customers, enhance engagement, and drive sustainable revenue growth.

