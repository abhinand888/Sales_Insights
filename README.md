# Sales_Insights

### Problem Statement:-

A company with multiple branches across India provides computer hardware and peripherals to its clients.
However, the sales director is facing challenges in understanding the company’s current issues and performance,
as sales have been falling short of expectations. When seeking updates from regional managers, 
the director often receives overly optimistic reports and a flood of Excel files, 
which only adds to the frustration. 
This is understandable, as it's difficult to interpret numbers solely from Excel spreadsheets.

### Solution:-

As a data analyst, I propose a solution to address the sales director’s challenges at the company:
implementing PowerBI dashboards for data visualization and analysis. These dashboards can consolidate data
from various sources, including the company’s sales figures, market trends, and regional manager reports.
With these tools, the sales director can easily view the current business status, identify problem areas, 
and make informed, data-driven decisions.

By providing a clear, visual representation of the data, the sales director can move away from relying on 
Excel files and overly optimistic reports from regional managers, reducing misunderstandings and frustration.

### Data:-



### Tools used: MySQL, Microsoft Power BI, Power Query Editor, DAX

### Task:-

- Finding Profit Margin, Sales Quantity and Revenue made in each year/month
- Analyzing top 5 customers and product by revenue
- Finding the Revenue Margin Contribution, Profit Margin Contribution and Profit % by each customer
- Finding the Revenue Margin Contribution, Profit Margin Contribution and Profit % by each Market
- Finding the Revenue trend by years
- Analyzing Revenue contribution by customer type.

### Data Cleaning:-

- Removed zones which were left blank in market table
- Removed sales amount which were less than 0 in sales transaction table
- Created new table called Normalized sales price to convert the USD price to INR price in sales transaction table
- Removed duplicates from currency column in sales transaction table.

### Dashboarding:-




![Screenshot (454)](https://github.com/abhinand888/Sales_Insights/assets/87313645/978eefc8-2c08-4b86-ad54-e1fcbd2463dd)

### Insights:-

- There is a decrease in the revenue trend from 2017–2020
- Delhi NCR is the highest contributor in Revenue and Sales quantity by Market.
- E-commerce gives the highest revenue contribution by customer type
- Surat gives highest profit % by market
- Central Market contributes to more Revenue

### What I’ve Learned:-

- How to do basic DAX calculations in measures
- Importing data from SQL to Power BI
- Publishing report to Power BI service
- How to use basic charts for visualization
- How to use filters in charts


