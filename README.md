📊 End-to-End Power BI Project: Sales Performance Dashboard (Google BigQuery Data Source)

🧾 Overview

    This project demonstrates how to build a complete data analytics pipeline using Google BigQuery as the data source and Power BI as the visualization tool. It involves loading, transforming, and analyzing sales performance data using SQL, Power Query Editor, and DAX (Data Analysis Expressions), ending with an interactive Power BI report published to a workspace.

⸻

🛠 Tools & Technologies Used

    	•	Google BigQuery (Data Storage & SQL Querying)
     
    	•	Power BI Desktop & Power BI Service (Data Visualization & Report Publishing)
     
    	•	Power Query Editor (ETL within Power BI)
     
    	•	DAX (Data Modeling & Measures)
     
    	•	SQL (BigQuery SQL for transformations)

⸻

📂 Project Sections

Section 1: Data Loading and Connection

	•	Creating Free Google Cloud Account
 
Set up GCP access and enable BigQuery.

	•	Loading Data into Google BigQuery & Connecting Power BI
 
Upload CSV or Excel datasets into BigQuery tables and connect them to Power BI for analysis.


⸻

Section 2: Data Understanding & Cleaning

	•	Using SQL in BigQuery
 
Perform initial data profiling, filtering, joins, and aggregations.

	•	Power Query Cleaning
 
Apply transformations such as data type changes, renaming columns, removing nulls, and shaping data.


⸻

Section 3: DAX Measures & Calculations

	•	YOY Sales Growth
 
Calculate year-over-year sales growth using CALCULATE, YEAR, MAX, IF, and BLANK functions.

	•	Offer Price Column & Scatter Plot
 
Add calculated columns and visualize offer prices against other metrics.

	•	MedianX DAX Function
 
Use MEDIANX to compute region-wise median sales price changes.

	•	Adding Units Sold & Last 12-Month Sales

Use CALCULATE, DATESINPERIOD, DISTINCTCOUNT, QUARTER, MAX, etc., to track performance over time.

	•	Sales by Region & Performance Page
 
Create insightful metrics like total regional sales and develop a centralized performance dashboard.

	•	TOTALYTD & Donut Charts
 
Visualize year-to-date sales and contribution per category.

	•	Age Column & Key Influencers Visual
 
Add demographic and AI visuals for richer insights.

⸻

Section 4: Publishing & Deployment

	•	Publishing the Report to Power BI Service
 
Move your Power BI report to the cloud for sharing and collaboration.

	•	Creating & Publishing the Report to New Workspace
 
Demonstrate deployment best practices using dedicated Power BI Workspaces.

⸻

📊 Final Output

The output of this project is a fully interactive Power BI dashboard that includes:

	•	YOY and Monthly sales trends
 
	•	Region-wise performance breakdown
 
	•	Median and total sales comparisons
 
	•	Age and demographic insights
 
	•	Key influencers visual powered by AI
 
	•	Beautiful donut and scatter charts
 
	•	Filterable and dynamic visuals
 

⸻

💡 Learning Outcomes

	•	End-to-end integration between Google BigQuery and Power BI
 
	•	Writing and optimizing SQL queries for BigQuery
 
	•	Cleaning and transforming data using Power Query Editor
 
	•	Creating advanced DAX measures and calculated columns
 
	•	Building rich Power BI visualizations and dashboards
 
	•	Publishing reports to Power BI Service and setting up workspaces
