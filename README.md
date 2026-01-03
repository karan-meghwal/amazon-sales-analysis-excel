# amazon-sales-analysis-excel
Business analysis of Amazon sales data using Excel





![amazon Logo PNG Vector (SVG) Free Download](https://github.com/user-attachments/assets/7dfb4199-028c-4602-9b39-94f646e9dfaf)












Project Overview

This project analyzes Amazon sales data to evaluate product performance, revenue trends, and category-level profitability. The objective is to transform raw transactional data into actionable business insights that support data-driven decision-making for an Amazon seller.

The analysis was performed entirely in Microsoft Excel, using structured data cleaning, pivot tables, and dashboard-style summaries.

## 📊 DATA 

## amazon_sales_raw.xlsx
Row data: https://www.kaggle.com/datasets/karanmeghwal/row-data-of-amazon-sales-analysis

BEFORE ANALYSIS , WE NEED TO CLEAN DATA 

Data Cleaning & Preparation (Excel)

The dataset was cleaned and prepared using standard Excel best practices:
	•	Removed duplicate transaction records
	•	Handled missing/null values
	•	Standardized date formats
	•	Corrected inconsistent category and product naming
	•	Converted raw data into structured tables for analysis

These steps ensured accuracy and reliability before performing any analysis.

CLEANED DATA: https://www.kaggle.com/datasets/karanmeghwal/cleaned-amazon-sales

## BUISNESS ANALYSIS 

 ## A. Overall Sales Performance
 Q1. What is the total revenue and how does it trend over time?
 Ans- first i clear cancelled payment in amount then i calculate "Sum of final revenue" in new column "Final revenue".

 TOTAL REVENUE -
 Total revenue is 6.95 Cr.
 
 <img width="1077" height="571" alt="Screenshot 2026-01-02 at 8 45 42 PM" src="https://github.com/user-attachments/assets/05f88619-b92b-44c8-8eeb-1678cc07420b" />

TREND BY MONTHS - 


<img width="1075" height="584" alt="Screenshot 2026-01-02 at 8 47 23 PM" src="https://github.com/user-attachments/assets/4b379dbf-36e9-4f9c-b373-578516fd6465" />
 We can see a downward trend from March to June.

DAILY TREND -
We can see in the image that the daily trend goes up and down
<img width="1135" height="704" alt="Screenshot 2026-01-02 at 8 49 49 PM" src="https://github.com/user-attachments/assets/cb775657-1c49-4631-b08f-59906a77a470" />

## B. Category Performance
Q2. Which product categories generate the highest revenue? 

we can see that "set" category generated highest revenue.

<img width="987" height="481" alt="Screenshot 2026-01-02 at 8 56 36 PM" src="https://github.com/user-attachments/assets/a6d5832a-a245-45d1-bcff-92bed7a4d70f" />

## C. Order Status Impact
 How do order statuses (Shipped vs Cancelled) impact total revenue?

PivotTable and chart showing revenue loss from cancellations and delivery performance.

<img width="1356" height="582" alt="Screenshot 2026-01-02 at 9 12 02 PM" src="https://github.com/user-attachments/assets/06ebc0eb-da4e-49e5-89f3-c05fae54372f" />


