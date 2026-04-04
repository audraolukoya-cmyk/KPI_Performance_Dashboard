
# KPI Performance Dashboard & iReady Automation Pipeline

## Overview
A data engineering and visualization project that automates the merging of student achievement data and tracks core competency metrics to support data-driven leadership decisions.

## Objective
To develop a dynamic tracking system monitoring baseline performance metrics for **400 active stakeholders**. The primary goal was to isolate performance gaps in core competencies and implement data-driven strategies to ensure a higher rate of benchmark achievement.

## Tools Used
* **Programming & Automation:** Python 3
* **Data Modeling:** Pandas
* **Visualization & Dashboards:** Power BI / Excel

## Process & Technical Execution
* **Automated Data Pipeline:** Developed a custom Python script (`iready_ready_folder_report.py`) to eliminate manual data processing.
* **Data Merging & Cleaning:** The script automatically pulls the raw Math and ELA CSV exports, joins the datasets, and isolates records for students enrolled across grades K-5.
* **Conditional Filtering:** Programmed specific logic to filter and identify stakeholders who successfully met benchmark criteria (passing 2 or more lessons in both targeted subjects).
* **Automated Reporting:** Configured the script to automatically compile, structure, and export the cleaned data into a production-ready `.xlsx` format.
* **Dashboard Design:** Connected the cleaned data output to an interactive visual canvas with left-rail navigation, high-level summary cards, and drill-through tables.

## Dashboard Features & Visualizations
* **Executive Summary Cards (KPIs):** Positioned at the top to give decision-makers an immediate, high-level view of total stakeholders, overall proficiency rates, and benchmark averages.
* **Segmented Performance Chart:** A stacked column visual that breaks down achievement by specific categories, allowing for quick comparison across groups.
* **Interactive Slicers & Filters:** Dropdown menus that empower users to dynamically drill down into the data by specific dates, categories, or performance tiers.
* **Drill-Through Data Table:** A detailed, sortable grid at the bottom of the canvas providing row-level transparency on individual stakeholder performance.

## Key Insights
* Uncovered specific performance trends across measured intervals to track growth.
* Pinpointed exact sub-groups requiring targeted resource allocation to maximize proficiency.
* Streamlined executive decision-making by replacing static, manual reports with automated visual summaries.
