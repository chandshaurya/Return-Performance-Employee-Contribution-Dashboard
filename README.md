# Return-Performance-Employee-Contribution-Dashboard

# Objective
The objective of this project was to design a Power BI dashboard that analyzes product return performance and employee contribution across regions. The goal was to track return trends over time, evaluate employee-level performance using year-over-year (YoY) comparisons, and generate actionable insights that can help optimize return management, employee productivity, and business decision-making.

# Dataset
•	Orders Dataset: Contains details of customer orders including order date, region, and sales information.
•	Returns Dataset: Captures records of returned items with corresponding order details.
•	People Dataset: Includes employee information mapped to regions.
•	Date Table: A custom date dimension created to enable time intelligence functions such as YoY difference, monthly trends, and period comparisons.

# Approach
•	Data Preparation: Cleaned and transformed raw data in Power Query, ensuring date formats were consistent and removing errors.
•	Data Modeling: Built a star schema model linking Orders (fact table) with Returns, People, and the Date table (dimension tables).
•	DAX Measures: Created calculated measures for key KPIs including Return Count, Return Rate %, Average Return Value, and YoY % change using CALCULATE, DIVIDE, and SAMEPERIODLASTYEAR.
•	Visualization Design: Developed a professional dashboard featuring:
1.	KPI cards for Return Count, Return Rate %, and Avg Return Value with YoY indicators.
2.	Employee-level performance table with Return Count YoY difference and Monthly YoY %.
3.	Bar chart of top employees by returns with YoY comparison.
4.	Line chart overlaying Monthly Return Count vs Last Year.
5.	Donut chart highlighting % contribution by employee.
•	Interactivity: Added slicers for Date, Region, and Employee to allow drill-down analysis.

# Key Insights
•	Return Growth: Return Count increased by 40.8% YoY, with the Return Rate reaching 11.5%, showing a consistent upward trend.
•	Value Impact: Despite higher return volumes, the Average Return Value dropped by 5.8%, suggesting customers are increasingly returning lower-value items.
•	Employee Contribution: Anna from the West region accounted for 62% of all returns, with a 43% YoY growth, making her the dominant contributor. Other employees such as Magee (16%) and Kelly Williams (13%) showed smaller contributions.
•	Regional/Seasonal Trends: Returns peak strongly in Q4 (Oct–Dec), highlighting a seasonal effect that requires better planning during year-end.
•	Performance Variation: While Anna and Cassandra Brandow show strong positive YoY changes, other employees have flatter or negative trends, indicating areas for review.

# Dashboard 
 <img width="900" height="501" alt="image" src="https://github.com/user-attachments/assets/00e25402-761d-4557-95f9-137ff7d11b0a" />





