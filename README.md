# **Excel Bike Sales Customer Analysis & Excel Dashboard**

[![Excel](https://img.shields.io/badge/Excel-Advanced%20Dashboard-green?logo=microsoft-excel)](https://github.com/atikasariri/excel-bike-sales-dashboard)
[![Domain](https://img.shields.io/badge/Domain-Retail%20&%20Consumer%20Analytics-orange)](#)
[![Role](https://img.shields.io/badge/Role-Business%20Analyst-blue)](#)

An end-to-end data analytics project exploring customer demographics and purchasing behavior for a bicycle retail dataset using Microsoft Excel. This project covers data cleaning, feature engineering, pivot table summaries, and an interactive dashboard.

_**Preview Dashboard**_

<p align="center">
<img width="616" height="446" alt="Bike Sales Dashboard" src="https://github.com/user-attachments/assets/8f72cefb-dbc4-4236-b24b-0cd1c5e87a7e" width="85%">
</p>

> _**How ​​to Use the Interactive Dashboard:**_
> 1. Download the Bike Sales Project.xlsx file from this repository.
> 2. Open the file in **Microsoft Excel** (Excel 2016 or later is recommended).
> 3. Click **"Enable Editing"** or **"Enable Content"** if a security warning appears.
> 4. Use the **Slicer/Filter** buttons at the top of the dashboard to interactively filter data by Year, Region, or Product Category.

_**Executive Summary**_

Understanding the target audience is crucial for optimizing marketing campaigns and product placement in retail sales. This project analyzes customer data containing demographics, commute habits, income levels, and purchasing history to identify key factors that influence whether a customer will buy a bicycle.

The final output is an interactive Excel dashboard that allows stakeholders to filter sales trends across regions, education levels, and marital status.


_**Project Workflow**_

1. Data Cleaning & Preparation (Working Sheet)
The raw dataset (bike_buyers) contained 1,026 records. Key cleaning and formatting steps included:
    - **Removing Duplicates:** Identified and removed 26 duplicate rows to ensure data integrity (reducing the dataset to 1,000 unique records).
    - **Standardizing Categorical Values:** Expanded abbreviated codes in "Marital Status" (M $\rightarrow$ Married, S $\rightarrow$ Single) and "Gender" (F $\rightarrow$ Female, M $\rightarrow$ Male) for better readability in dashboard charts.
    - **Currency & Column Formatting:** Applied currency formatting to the "Income" column.
    - **Feature Engineering (Age Brackets):** Binned the continuous "Age" variable into discrete categories (Middle Age, Adolescent, Old) using nested logic to enable clearer visual segmentation.


_**Business Overview & Problem Statement**_

Retail bicycle businesses often struggle to identify high-value customer segments, understand purchasing behaviors across demographics (such as age, income, and commute distance), and evaluate regional sales distribution. 

Without interactive data visualization, stakeholders face challenges in:
* Pinpointing core customer profiles that yield the highest conversion rates.
* Aligning inventory and marketing campaigns with customer income brackets and marital status.
* Tracking key performance indicators (KPIs) through a centralized, user-friendly dashboard.


_**Data Architecture & Tools Used**_

* **Data Processing & Modeling:** Microsoft Excel (Data Cleaning, Pivot Tables, Pivot Charts, and Slicers)
* **Dashboarding & Visualization:** Advanced Excel Interactive Dashboard
* **Core Analytics Focus:** Customer Demographics Segmentation, Income vs. Purchase Behavior, Commute Distance Analysis, Age Group Categorization


_**Key Business Insights**_

1. **Customer Income & Purchasing Power:** 
   * Higher average annual income correlates directly with a higher probability of bike purchases, highlighting clear target brackets for premium models.
2. **Age & Commute Demographics:** 
   * Middle-aged demographic groups (specifically working professionals) represent the largest volume of buyers, particularly those with short-to-moderate commute distances.
3. **Gender & Marital Status Trends:** 
   * Segmented analysis reveals specific purchasing preferences between married vs. single buyers across male and female categories, driving more tailored marketing campaigns.


_**Strategic Business Recommendations**_

* **Targeted Digital Marketing:** Direct premium bike advertising toward high-income customer segments identified through demographic filtering.
* **Commuter-Focused Product Positioning:** Promote practical, multi-use bicycle models tailored to urban professionals within active commuting ranges.
* **Interactive Filtering for Stakeholders:** Utilize Excel slicers to enable sales teams to dynamically review regional and demographic performance on demand.


_**Repository Structure**_

```text
├── assets/
│   ├── Bike Sales Dashboard.PNG
│   ├── Dashboard Preview.gif
│   └── working sheet.PNG
├── Bike Sales Project.xlsx     # Main Excel workbook (raw data, working sheet, pivots, & dashboard)
└── README.md                   # Project documentation
