📊 Power BI Dashboard Project — HR & Workforce Insights
📁 Project Overview

This project demonstrates a complete end-to-end data analytics workflow using a raw HR dataset.
The goal was to clean the data using Excel, prepare it for analysis, and build an interactive Power BI Dashboard to uncover insights about employee workforce patterns.

🔧 Tools & Technologies Used

Excel – Data cleaning, preprocessing

Excel Formulas – VLOOKUP, IF, TRIM, CLEAN, TEXT functions, etc.

Power BI Desktop – Data modelling, DAX, interactive visualizations

Power Query – Data transformation

🛠️ Steps Performed
1. Raw Dataset Collection

The project begins with a raw employee dataset exported in Excel format.
Issues identified in the raw data:

Missing values

Inconsistent formatting

Duplicate records

Mixed data types

Text inconsistencies (spaces, special characters)

2. Data Cleaning in Excel

Performed structured cleaning using formulas and transformation tools:

✔ Handling Missing / Incorrect Values

Replaced blanks using IF()

Filled missing fields with reference tables using VLOOKUP()

Used TEXT() to standardize date formats

✔ Removing Duplicates

Applied Excel Remove Duplicates feature

✔ Correcting Formatting

Trimmed unnecessary spaces using TRIM()

Removed invisible characters using CLEAN()

Standardized categorical fields (Department, Gender, Job Role)

✔ Data Validation

Added Data Validation lists to avoid inconsistent future entries

3. Importing Clean Data to Power BI

Loaded the cleaned dataset into Power BI

Applied additional transformations in Power Query (type conversion, column extraction, calculated columns)

4. Data Modelling

Created relationships between tables

Added calculated fields using DAX (e.g., Attrition Rate, Hiring Trend, Tenure Group)

5. Dashboard Development

Built an interactive and professional Power BI Dashboard showcasing:

📌 Key Insights Visualized

Workforce Distribution

Employee Attrition Analysis

Hiring Trends

Salary & Performance Overview

Department-wise Employee Metrics

Gender Diversity & Experience Breakdown

📌 Features

Slicers for dynamic filtering (Department, Education, Job Role, Age Group)

Clean, professional UI design

KPI cards for quick insight

📷 Dashboard Preview
![Dashboard Preview](dashboard.png)


📂 Project Files Included

Hr and workforce insight.pbix — Power BI Dashboard

Employee Sample Data.xlsx — Cleaned dataset

README.md — Project documentation

🚀 How to Use This Project

Clone the repository

Open Hr and workforce insight.pbix in Power BI Desktop

Review dashboard and use filters to explore insights

📌 Key Learnings

End-to-end analytics workflow

Excel-based data cleaning techniques

Power Query transformations

DAX for creating business metrics

Building professional dashboards in Power BI

🤝 Contact

If you’d like to collaborate or provide feedback, feel free to connect!
