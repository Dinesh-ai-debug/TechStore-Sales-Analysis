# TechStore-Sales-Analysis
"End-to-end sales analysis project using SQL for data querying and Power BI for executive dashboarding."
I recommend focusing marketing efforts on the 'Accessories' category, as it currently only contributes 9% of total revenue. Increasing the average order value in this segment is key to hitting the $10,000 Super Goal.
The Business Problem (The "Why")
TechStore’s management lacked a centralized way to monitor daily sales performance against their monthly growth targets. They needed a solution that would allow them to identify top-performing products instantly and see if the business was on track to hit its $10,000 "Super Goal."
The Technical Stack (The "How")
•	Database: MySQL (Local Host). I managed the AnalystTraining database and performed data extraction.
•	Cleaning: Power Query. Used for data types, removing nulls, and filtering columns.
•	Modeling: Star Schema. Created relationships between Sales data and Product categories.
•	Calculations: DAX (Data Analysis Expressions). I developed custom measures for:
•	Total Revenue (Sum of sales).
•	Average Order Value (Transaction health).
•	Goal Tracking % (Performance against $10k target).
The "Aha!" Moment (The Insight)
After building the dashboard, it became clear that while the Macbook Air is the primary revenue driver, the store is currently at only 72% of its monthly goal. This visualization allows management to see that they need an additional ~$2,800 in sales to hit the target, focusing specifically on high-margin items in the "Electronics" category.
Key Features & Design
•	The Traffic Light System: Implemented conditional formatting on KPI cards. The numbers turn Red if under 50% of the goal and Green if over, allowing for "at-a-glance" executive decision-making.
•	Hidden Insights: Created custom Report Page Tooltips that reveal a breakdown of sales by category when hovering over any product bar chart.
