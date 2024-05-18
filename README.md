# Sales_Insights

### Problem Statement:-

A Hardware company with multiple branches across India provides computer hardware and peripherals to its clients.
However, the sales director is facing challenges in understanding the company’s current issues and performance,
as sales have been falling short of expectations. When seeking updates from regional managers, 
the director often receives overly optimistic reports and a flood of Excel files, 
which only adds to the frustration. 
This is understandable, as it's difficult to interpret numbers solely from Excel spreadsheets.

### Solution:-

Proposed a solution to address the sales director’s challenges at the company:
Implementing PowerBI dashboards for data visualization and analysis. These dashboards can consolidate data
from various sources, including the company’s sales figures, market trends, and regional manager reports.
With these tools, the sales director can easily view the current business status, identify problem areas, 
and make informed, data-driven decisions.

By providing a clear, visual representation of the data, the sales director can move away from relying on 
Excel files and overly optimistic reports from regional managers, reducing misunderstandings and frustration.

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

### Dashboarding:-



![Screenshot (454)(1)(1)](https://github.com/abhinand888/Sales_Insights/assets/87313645/86b32969-5ec4-4dd9-b92e-ebc92f8147c9)
![2018-revenue](https://github.com/abhinand888/Sales_Insights/assets/87313645/d6990d6f-59d4-4077-b407-9c6b753b6cbe)


### Insights:-

- The Highest Revenue is the year 2018.
- There is a decrease in the revenue trend from 2017–2020
- Delhi NCR is the highest contributor in Revenue and Sales quantity by Market.
- E-commerce gives the highest revenue contribution by customer type
- Electricalsara stores is the top customer by revenue.
- Central Market contributes to more Revenue

### Key Learnings:-

- How to do basic DAX calculations in measures
- Importing data from SQL to Power BI
- Publishing report to Power BI service
- How to use basic charts for visualization
- How to use filters in charts


