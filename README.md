# **Bike Sales Customer Analysis & Excel Dashboard**

An end-to-end data analytics project exploring customer demographics and purchasing behavior for a bicycle retail dataset using Microsoft Excel. This project covers data cleaning, feature engineering, pivot table summaries, and an interactive dashboard.


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


_**Key Insights & Analytics (Pivot Table)**_

Using Pivot Tables, several key drivers of bike purchases were uncovered:

1. **Income vs. Purchase Decision:**
   - On average, customers who purchased a bicycle had higher income levels ($57,962) compared to non-buyers ($54,874).
   - Male buyers in particular had the highest average income ($60,124).

2. **Commute Distance Impact:**
   - Customers with short commute distances (**0–1 miles**) showed the highest purchase conversion rate (200 buyers vs. 166 non-buyers).
   - As commute distance increased beyond 5 miles, purchase rates dropped significantly, indicating that bikes are predominantly bought for short-distance commutes or casual riding.

3. **Demographics & Age Groups:**
   - The **Middle Age** group (31–54 years old) represents the vast majority of bike purchasers.


_**Interactive Dashboard Feature**_

The dashboard provides a visual overview of customer patterns:
- **Income by Gender Chart:** Clustered column chart comparing average income between buyers and non-buyers grouped by gender.
- **Commute Distance Trend Line:** Line chart showing how purchase likelihood decreases as daily commute distance increases.
- **Age Group Breakdown:** Bar chart illustrating purchasing trends across different age brackets.
- **Interactive Slicers:** Allows filtering of all dashboard visualizations by **Marital Status**, **Region**, and **Education Level**.


_**Repository Structure**_

```text
├── Bike Sales Project.xlsx       # Main Excel workbook containing raw data, working sheet, pivots, & dashboard
├── data/
│   ├── raw_bike_buyers.csv       # Original dataset
│   └── cleaned_bike_data.csv     # Exported clean dataset
└── README.md                     # Project documentation
