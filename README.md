# INTERNSHIP-DAY-2-TASK

Step-by-Step Power BI Visual Plan

1. Executive Summary Page

Visuals: 3 KPI Cards
	•	Total Sales → Total Sales = SUM('train'[Sales])
	•	Total Orders → Total Orders = DISTINCTCOUNT('train'[Order ID])
	•	Total Customers → Total Customers = DISTINCTCOUNT('train'[Customer ID])

Tip: Use a slicer for Order Date to make it dynamic.

⸻

2. Sales Over Time

Visual: Line Chart
	•	Axis: Order Date (set as Month/Year)
	•	Values: Total Sales
	•	Slicer: Segment or Region

Insight: Spot seasonal patterns or growing/declining trends.

⸻

3. Regional Performance

Visual: Filled Map or Bar Chart
	•	Location: Region or State
	•	Values: Total Sales

Bonus: Add tooltip with Total Orders and Average Sales per Order

⸻

4. Sales by Product Category

Visual: Treemap or Stacked Bar
	•	Group: Category & Sub-Category
	•	Values: Total Sales

Insight: Which products are driving most of the revenue?

⸻

5. Shipping Impact

Visual: Clustered Column or Pie Chart
	•	Legend: Ship Mode
	•	Values: Total Sales, Total Orders

Insight: Which shipping method is most used? Fast shipping vs. sales?

⸻

6. Top 10 Customers

Visual: Bar Chart
	•	Axis: Customer Name
	•	Values: Total Sales
	•	Filter: Top 10 by Sales

⸻

7. Filters/Slicers for Interactivity
	•	Segment
	•	Category
	•	Region
	•	Ship Mode
	•	Date Range (Order Date)





![image](https://github.com/user-attachments/assets/b64a8089-5fac-4c9d-b81e-6f06b8abb8c2)
Key Insights Slide

Summarize insights from all visuals:



	•	“West region contributes 35% of revenue”
	•	“Office Supplies has most volume but Furniture has higher avg order value”
	•	“Standard Class shipping dominates but 2-day shipping is growing”

