# Sales_Insights

### Problem Statement:-

A hardware company with multiple branches across India is struggling with declining sales. The sales director receives overly optimistic reports and numerous Excel files from regional managers, making it difficult to understand the company's issues and performance.
### Solution:-

Implementing PowerBI dashboards for data visualization and analysis. These dashboards will consolidate data from sales figures, market trends, and regional manager reports, allowing the sales director to easily view the business status, identify issues, and make informed decisions.

With clear visual representations of data, the sales director can move away from Excel files and overly optimistic reports, reducing misunderstandings and frustration.

### Data:-
I have been provided with the SQL dataset which contains Sales customers,Sales date,Sales transactions,Sales Markets,Sales Products from CodeBasics.

![Screenshot (459)(1)](https://github.com/abhinand888/Sales_Insights/assets/87313645/6952a7c5-da21-459b-a891-38b5d6fe8e7c)

### Tools used: MySQL, Microsoft Power BI, Power Query Editor, DAX

### Task:-

- Finding Revenue and Sales Quantity  made in each year/month
- Analyzing top 5 customers by revenue
- Analying top 5 products by revenue
- Finding the Revenue trend by years
- Analyzing Revenue and sales Qty by markets.

### Data Cleaning:-

- Removed data which were left blank in market table
- Removed sales amount which were less than 0 in sales transaction table
- Created new table called Norm_amount to convert the USD price to INR price in sales transaction table
- Removed duplicates from currency column in sales transaction table.

### Data Modeling:-
- The dataset was cleaned and transformed, it was ready for the data model.
### Dashboarding:-



![Screenshot (454)(1)(1)](https://github.com/abhinand888/Sales_Insights/assets/87313645/86b32969-5ec4-4dd9-b92e-ebc92f8147c9)
#### 2018 Revenue 
![2018-revenue](https://github.com/abhinand888/Sales_Insights/assets/87313645/d6990d6f-59d4-4077-b407-9c6b753b6cbe)
#### Mobile Layout Version
![mobile-layout](https://github.com/abhinand888/Sales_Insights/assets/87313645/1777bc40-3c2d-4057-93ec-4748df8901d1)


### Insights:-

- The Highest Revenue is the year 2018.
- Delhi NCR is the highest contributor in Revenue and Sales quantity by Market.
- Electricalsara stores is the highest revenue contributor by customer type.
- There is a decrease in the revenue trend from 2017–2020

### Key Learnings:-

- How to do  DAX calculations in measures
- Importing data from SQL to Power BI
- PowerBI in mobile layout
- How to use charts for visualization
- How to use filters in charts


