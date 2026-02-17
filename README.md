# 🧹 Advanced Data Cleaning & Visualization (ETL)

## 📌 Project Overview
This project focuses on the most critical aspect of data analytics: **Data Cleaning (ETL)**. 
I took a "dirty" real-world dataset (`project.csv`) containing inconsistencies, null values, and formatting errors, and transformed it into a clean, actionable dataset using **Power Query (M Language)** and Power BI.

---

## ⚠️ The Challenge (Dirty Data)
The initial dataset suffered from several common data quality issues:
* **Inconsistent naming conventions** (e.g., "U.S.A" vs "USA").
* **Significant missing values (Nulls)** in critical columns.
* **Incorrect data types** preventing accurate calculation.

## ⚙️ The Solution (Power Query Transformation)
I utilized advanced Power Query techniques to clean the data without manual intervention:
1.  **Data Profiling:** Analyzed column quality and distribution to identify error patterns.
2.  **Conditional Logic:** Applied M-code logic to impute missing values based on related data points.
3.  **Transformation:**
    * Split delimited columns for granular analysis.
    * Unpivoted tables to normalize the data structure.
    * Created custom calculated columns for specific KPIs.

---

## 📊 Final Visualization
The cleaned data was loaded into **Power BI** to build a comprehensive dashboard (`project_2.pbix`) that visualizes the true trends hidden behind the messy data.

## 🛠️ Tech Stack
* **ETL Tool:** Power Query (M Language)
* **Visualization:** Power BI
* **Data Source:** CSV (Flat File)

## 📂 How to View
1.  Download `project.csv` to see the "Before" state (Raw Data).
2.  Open `project_2.pbix` in Power BI Desktop to see the "After" state (Transformation Steps & Dashboard).
