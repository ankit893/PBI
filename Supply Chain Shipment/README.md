![image](https://github.com/user-attachments/assets/dbb2168a-beae-4365-84a7-1a282eee67c0)
Project Overview
•	Supply chain analysis is the process of evaluating every stage of a supply chain starting from the time the business acquires raw materials or supplies from its suppliers to the delivery of final products to the customers.
•	The purpose of the analysis is to determine which part of the supply chain can be improved or shortened to deliver the product more quickly and efficiently to the customers.

Business Problem 🚩

Each of these supply chain analytics can increase the overall efficiency of business operations, which can lead to sizable cost savings.
1.	Descriptive Analytics focuses on understanding what happened in the past by analyzing historical data. It can provide insights on key performance metrics, such as inventory levels, lead times, and delivery performance. Descriptive analytics can help identify patterns and trends in past supply chain operations, allowing organizations to make informed decisions about future strategies.
2.	Diagnostic Analytics goes beyond descriptive analytics by identifying the root causes of supply chain issues. By analyzing data from different sources, such as suppliers, logistics providers, and customers, organizations can identify the factors that contribute to delays, disruptions, or quality issues in their supply chain. This can help them take corrective actions to prevent similar problems from happening in the future.
3.	Predictive Analytics uses statistical models and machine learning algorithms to forecast future supply chain events. By analyzing historical data, organizations can identify patterns and trends that can help predict demand, inventory levels, and delivery performance. This can help organizations optimize their supply chain operations, reduce costs, and improve customer satisfaction.
4.	Prescriptive Analytics takes predictive analytics one step further by providing recommendations on how to optimize supply chain operations. By using optimization algorithms and simulations, prescriptive analytics can help organizations identify the best course of action to improve supply chain performance. This can help organizations make better decisions and improve their overall supply chain efficiency.

How to conduct supply chain analysis 🎯

The above analytics should be used when conducting supply chain analysis. The basic steps of an analysis are:
•	Define your objectives.
•	Research the market.
•	Conduct in-depth supplier analysis.
•	Identify key market indicators
•	Pull together your findings and outline final suggestions.

Expected Outcomes
The expected outcome of this Project is to develop a well-structured Supply Chain database, generate insightful business intelligence through Power BI visualizations, and uncover key Supply Chain performance metrics—such as top-performing countries, best-selling products, revenue trends.

🛠️ Technologies Stack

Excel - Initial data exploration and preprocessing.
Power BI - Data Cleaning with Power Query, Data Modelling, DAX, Data visualization and interactive reporting.

Data Source

Here is a dataset we collected from a Fashion and Beauty startup. The dataset is based on the supply chain of Makeup products. Below are all the features in the dataset:
Product Type
SKU
Price
Availability
Number of products sold
Revenue generated
Customer demographics
Stock levels
Lead times
Order quantities
Shipping times
Shipping carriers
Shipping costs
Supplier name
Location
Lead time
Production volumes
Manufacturing lead time
Manufacturing costs
Inspection results
Defect rates
Transportation modes
Routes
Costs

Project Structure
1. Data Preparation (Microsoft Excel):
Data understanding, exploration, data loading, and data importing.
Check dataset structure using Column Headers & Data Types
Import the CSV. Data from Excel Into Powerbi’s Power Query Editor
2. Data Cleaning & Transformation in Power BI (Power Query)
Introduction
Data cleaning is crucial before analysis, ensuring accuracy, consistency, and completeness. This project uses Power BI’s Power Query Editor to clean and transform the retail sales dataset. This document outlines the detailed steps taken to prepare the data for analysis.

Step 1: Removing Duplicates
Identify key columns where duplicates should not exist (e.g., ID , Product Code, PQ, Country).
Select the column → Click Remove Duplicates in the ribbon.
Verify the row count before and after removal.

![image](https://github.com/user-attachments/assets/87eb472d-e09e-47a8-aa20-6286ddb4a626)

Step 2: Standardizing Data Formats
Ensure numerical fields (e.g., Sales, Quantity) are in Decimal Number format.
Convert categorical fields (e.g., Product Name) to Text format.
Convert date fields (Transaction Date) to Date format.
Home → Data Type → Select Date
Standardize text formatting: Convert to Proper Case (e.g., "laptop" → "Laptop") using:

![image](https://github.com/user-attachments/assets/72a0a431-dc3c-4c40-b757-28c8dce37ee7)

Step 3: Handling Missing Values
Identifying Missing Data
Click on each column and check for null values in the data preview.
Use Filter to check missing entries.
Step 4: Loading Clean Data into Power BI
Click Close & Apply to load the cleaned dataset into Power BI for visualization.

🧮 Key DAX Measures

Average Pack Price
avg_pack_price = AVERAGE(Supply_Chain[Pack Price])

Average Unit Price
avg_unit_price = AVERAGE(Supply_Chain[Unit Price])

Frequency Of Supply
Frequency of Supply = COUNT(Supply_Chain[Country])

Shipment Frequency
Shipment frequency = COUNT(Supply_Chain[Shipment Mode])

🏆 Dashboard Visuals

![image](https://github.com/user-attachments/assets/3b6b5549-e42c-4ecd-9f73-4ca5bc83d853)



More work Coming Soon...







📈 Key Insights

Coming Soon......



📌 About Me

Hi, I'm Ankit Sharma, a Data Analyst skilled in SQL, Power BI, and Excel. I enjoy turning complex datasets into actionable insights through data visualization and business intelligence techniques.

🔹 Key Skills: Data Analysis | SQL Queries | Power BI Dashboards | Data Cleaning | Reporting
🔹 Passionate About: Data storytelling, problem-solving, and continuous learning

🚀 Always learning and improving—driven by curiosity and a passion for analytics.

📫 Let’s connect!

📩 ankitsharmaaa893@gmail.com

🔗 : https://www.linkedin.com/in/ankitsharma893/

🌐 : https://linktr.ee/ankitsharma893



