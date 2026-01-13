📦 Supply Chain Optimization End-to-End Analytics Project
📌 Project Overview

This project presents an end-to-end supply chain analytics solution, covering data cleaning, exploratory analysis, and interactive dashboarding.

The objective is to analyze warehouse inventory, refill behavior, and logistics issues to uncover inefficiencies and support data-driven supply chain optimization.

The project follows a real-world analytics workflow:

Raw Data → Data Cleaning (Python) → Analysis → Power BI Dashboard

🧩 Business Problem

Supply chain operations face challenges such as:

Inventory imbalance across warehouse capacities

Frequent refill requests indicating demand stress

Transport and infrastructure-related issues

Difficulty in identifying high-risk warehouses

This project helps decision-makers identify problem areas and optimize supply chain operations.

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib)

Jupyter Notebook – Data cleaning & EDA

Power BI – Data modeling & dashboard creation

CSV Dataset – Supply Chain Management data

📓 Data Cleaning & Preprocessing (Python Notebook)

All data preparation was performed in a Jupyter Notebook before importing the data into Power BI.

✔ Steps Performed:

Imported and explored raw supply chain dataset

Checked column data types and corrected inconsistencies

Handled missing values logically based on business context

Converted binary indicators (e.g. transport issues, flood impact) into numeric format

Treated outliers using IQR (Interquartile Range) method

Removed irrelevant or inconsistent columns

Performed basic exploratory analysis using Matplotlib

Exported a clean, analysis-ready dataset for Power BI

📂 Notebook file: Supply Chain Management.ipynb

📊 Power BI Dashboard Overview

The final dashboard provides an interactive view of supply chain performance.

🔑 Key KPIs

🏭 Total Warehouses – Unique count of warehouses

📦 Total Inventory – Total product weight handled

🔄 Average Refill Requests – Mean refill frequency (last 3 months)

🚚 Transport Issue % – Warehouses impacted by transport issues

📈 Visualizations Included
🔹 Inventory Analysis

Inventory distribution by Warehouse Capacity Size (Small / Mid / Large)

🔹 Refill Behavior Analysis

Distribution of refill requests across warehouses

Helps identify warehouses with higher demand pressure

🔹 Interactive Filters

Zone (North, South, East, West)

Location Type (Urban / Rural)

Warehouse Capacity Size

These slicers allow dynamic analysis across regions and warehouse types.

🔍 Key Insights

Large and Mid-size warehouses handle the majority of inventory

Higher refill frequency indicates demand pressure in specific warehouse segments

Transport issues affect a significant percentage of warehouses

Warehouse capacity and location strongly influence operational efficiency

💼 Business Impact

This analysis can help organizations:

Optimize inventory allocation

Reduce refill frequency through better planning

Identify high-risk warehouses

Improve logistics and transport decision-making

📁 Project Structure
📦 Supply Chain Optimization
 ┣ 📓 Supply Chain Management.ipynb   # Data Cleaning & EDA
 ┣ 📊 Power BI Dashboard (.pbix)
 ┣ 📄 Cleaned Dataset (.csv)
 ┗ 📘 README.md

 
 👤 Author

Insha Farhan
Aspiring Data Analyst | Python | Power BI | SQL
📊 Data Analytics & Business Intelligence Enthusiast
