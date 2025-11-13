# Sales-Performance-dashboard
This Project contains Sales Dashboard creation using Power BI . ETL Process and DAX functions are used for Data Analysing and Processing and Looker Studio used for Dashboard Creation. 
                                             

1. Objective
The objective of this analysis is to study sales data for June-July 2022, identify key trends, track revenue performance, and provide actionable insights to improve overall sales and conversion rates.
________________________________________
2. Data Overview
•	Data Source: Sample Data 2.xls

•	Two Tables : Product Language , Sales Data.

•	Columns: User ID, Product Code, Payment Status, Source, Product Amount, Payment Mode, Currency Code,Coupon code, Transaction Bank, Product Language

•	Total Records: 9514
________________________________________
3. Data Preparation
•	I used MS Power BI for data cleaning , Transformation and visualisation .
	Handled null values in Coupon Code, Payment Mode, and Transaction Bank.
•	Clean and Standardized date and currency formats.
•	Added new calculated columns: Lead Registered Month, Lead Registered Time, Sales Month.
•	Created DAX measures for:
o	Total Orders
o	Total Revenue
o	Total Sales
o	Conversion Rate (%)
o	Average Order Value
•	Added filters for Top performing products and Coupon Codes .
•	Intiated Key performance indicator for Sales by Month.
•	Merge the two Tables Product Language and Sales Data .
5. Key Insights
Overall Performance
•	Total Orders: 9514
•	Paid Orders: 1691
•	Total Revenue: 2.21 M(Paid orders value)
•	Conversion Rate: 17.77%
•	Total Sales : 2.26 M
•	Average of Sales : 2.34 Lakhs
 Monthly Trends
•	July recorded higher revenue compared to July.
•	Consistent growth in paid transactions.
Product Performance
•	Product1 contributed 0.5M of total revenue.
•	Product2 showed high order volume but low payment completion rate.
 Source Insights
•	Direct Source generated High Sales of total orders.
•	Paid/Referral channels can be explored for diversification.
 Payment Insights
•	UPI and Credit Card were top payment modes.
•	High “Unknown” payments indicate incomplete or failed transactions.
 Product Language insights
•	English language earns more Orders
•	Malayalam has low orders.
Coupon Code Analysis 
•	No coupon earned more Sales.
•	Coupon 1 has high  number of Sales.

________________________________________
5. Actionable Recommendations
Area	Recommendation
Conversion	Send reminders to users with Initiated but unpaid orders.
Refunds	Review refund cases to identify recurring issues.
Marketing	Promote low-performing products through bundled offers.
Channel Optimization	Increase marketing through top-performing sources.
Payment Gateway	Resolve “Unknown” payment mode issues to improve success rate.
________________________________________
6. Conclusion
The dashboard provides a clear view of sales performance for June–July 2022. Product1 drives most revenue, while conversion improvement and refund management can further enhance total sales. With better marketing focus and payment optimization, overall revenue can grow in the next quarter.

