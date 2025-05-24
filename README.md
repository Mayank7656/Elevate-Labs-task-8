# Elevate-Labs-task-8

🧾 Project Title:
Simple Sales Dashboard Using Power BI

🎯 Objective:
To create an interactive dashboard that visualizes sales performance across different months, regions, and product categories, using the Superstore_Sales.csv dataset.

🛠 Tools Used:
Power BI Desktop (for dashboard creation)

(Optional) Microsoft Excel or Notepad (to preview CSV data)

📁 Dataset Used:
File: Superstore_Sales.csv
Main Columns Used:

Order Date (for monthly trend analysis)

Region (for geographic analysis)

Category (for product-level analysis)

Sales, Profit (for performance KPIs)

✅ Steps to Build the Dashboard:
1. Load the Dataset
Open Power BI Desktop

Click Get Data → Text/CSV

Load the file Superstore_Sales.csv

2. Create Month-Year Column
To track sales over time:

Go to Modeling → New Column

Use this DAX formula:

DAX
Copy
Edit
MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM YYYY")
3. Create Visualizations
📈 Line Chart – Sales Over Time
Visual: Line Chart

X-Axis: MonthYear

Y-Axis: Sales

Sort by: Order Date (for correct month sequence)

📊 Bar Chart – Sales by Region
Visual: Bar Chart

Axis: Region

Values: Sales

🍩 Donut Chart – Sales by Category
Visual: Donut Chart

Legend: Category

Values: Sales

4. Add Filters/Slicers
Visual: Slicer

Field: Region or Category

Allows users to filter the dashboard dynamically

5. Format & Highlight
Use the Format pane to adjust:

Color themes (highlight top performers)

Titles and labels for each chart

6. Export Dashboard
Click File → Export → PDF
OR

Use Snipping Tool to capture a screenshot

📈 Insights (Example):
West region had the highest sales in Q3.

Technology category outperforms Furniture and Office Supplies.

Sales consistently peaked in December across years.

Central region shows steady but moderate performance.

📦 Deliverables:
📊 Dashboard (PDF or Screenshot)

📄 Insights Report (Text or Slide)

📁 README File (This documentation)

