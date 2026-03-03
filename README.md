# 📊 HR Analytics Dashboard -- Case Study

------------------------------------------------------------------------

## 1️⃣ Business Problem

Employee attrition is one of the most critical challenges faced by HR
departments.
High turnover increases recruitment costs, reduces productivity, and
impacts organizational stability.

The objective of this project was to:

-   Analyze employee attrition patterns
-   Identify high-risk employee segments
-   Provide data-driven insights for retention strategies
-   Enable leadership to make strategic HR decisions

------------------------------------------------------------------------

## 📊 Dashboard Preview

### 🔹 Power BI Overview
<img src="Screenshots/powerbi_dashboard.png" width="900">

---

### 🔹 Excel Overview
<img src="Screenshots/excel_dashboard.png" width="900">
## 2️⃣ Project Objective

-------------------------------------------------------------------------------

HR-Analytics-Dashboard/
│
├── PowerBI/
│   └── HR_DATA_DASHBOARD.pbix
│
├── Excel/
│   └── HR_DATA_Excel_DASHBOARD.xlsx
│
├── Screenshots/
│   ├── PowerBI_Overview.png
│   ├── Excel_Overview.png
│   ├── Filtered_Female_View.png
│   └── Filtered_Male_View.png
│
└── README.md

---------------------------------------------------------------------------------

To design and develop an interactive HR Analytics Dashboard using
**Power BI and Excel** that:

-   Tracks key workforce KPIs
-   Identifies attrition trends by department, age, gender, education,
    and job role
-   Provides actionable insights for HR leadership

------------------------------------------------------------------------

## 3️⃣ Tools & Technologies Used

-   Power BI (Data Modeling & Visualization)
-   Microsoft Excel (Pivot Tables & Dashboard Design)
-   DAX (Data Analysis Expressions)
-   Data Cleaning & Transformation
-   Interactive Slicers and Filters

------------------------------------------------------------------------

## 4️⃣ Dataset Overview

The dataset includes:

-   Employee Demographics (Age, Gender, Marital Status)
-   Department & Job Role
-   Education Level
-   Attrition Status
-   Job Satisfaction Ratings

### Key Metrics:

  KPI                Value
  ------------------ --------
  Total Employees    1470
  Total Attrition    237
  Attrition Rate     16.12%
  Active Employees   1233
  Average Age        37

------------------------------------------------------------------------

## 5️⃣ Data Cleaning & Preparation

-   Removed duplicate records
-   Standardized categorical fields (Department, Education, Job Role)
-   Created calculated columns for:
    -   Age Bands
    -   Attrition Flag (Yes/No → 1/0)
-   Built relationships between tables (where applicable)
-   Created DAX measures for KPI calculations

------------------------------------------------------------------------

## 6️⃣ Data Modeling Approach

-   Fact Table: Employee Data
-   Dimension Attributes:
    -   Department
    -   Gender
    -   Education
    -   Job Role
    -   Marital Status
    -   Age Group

Star schema modeling principles were applied for performance
optimization.

------------------------------------------------------------------------

## 7️⃣ Key Insights & Findings

### 🔹 Attrition Analysis

-   Overall attrition rate: **16.12%**
-   Sales and R&D departments show highest attrition
-   HR department shows relatively lower attrition

### 🔹 Age Group Analysis

-   Highest attrition observed in **25--34 age group**
-   Employees above 55 show lowest attrition
-   Indicates early-career mobility trend

### 🔹 Gender Insights

-   Male employees form majority of workforce
-   Slightly higher attrition rate observed among males

### 🔹 Education-wise Attrition

-   Bachelor's degree holders show highest attrition
-   Doctoral degree holders show lowest attrition

### 🔹 Job Role Analysis

-   Highest attrition in:
    -   Laboratory Technician
    -   Sales Executive
    -   Research Scientist

### 🔹 Marital Status Insight

-   Single employees exhibit higher attrition
-   Married employees show stronger retention

------------------------------------------------------------------------

## 8️⃣ Business Recommendations

Based on insights:

1.  Improve retention programs for employees aged 25--34
2.  Implement engagement initiatives in Sales & R&D
3.  Develop targeted retention strategies for single employees
4.  Improve career progression pathways for Bachelor's degree holders
5.  Conduct job satisfaction surveys in high-risk job roles

------------------------------------------------------------------------

## 9️⃣ Dashboard Features

-   Interactive slicers (Department, Gender, Education)
-   KPI Cards for quick executive view
-   Dynamic visualizations
-   Drill-down analysis
-   Clean and executive-level UI design

------------------------------------------------------------------------

## 🔟 Sample DAX Measure

``` dax
Attrition Rate =
DIVIDE([Total Attrition], [Total Employees]) * 100
```

------------------------------------------------------------------------

## 1️⃣1️⃣ Business Impact

This dashboard enables:

-   Predictive workforce planning
-   Reduced attrition costs
-   Strategic hiring decisions
-   Improved HR policy formulation
-   Data-driven leadership reporting

------------------------------------------------------------------------

## 1️⃣2️⃣ Future Enhancements

-   Predictive attrition modeling using Machine Learning
-   Integration with live HR database
-   Department-level profitability analysis
-   Advanced drill-through reports
-   Automated email alerts for high-risk segments

------------------------------------------------------------------------

## 👨‍💻 Author

Bhaskar Kushwah
Master of Computer Applications (MCA)
Aspiring Data Analyst | Cloud & DevOps Enthusiast

------------------------------------------------------------------------

⭐ If you found this case study insightful, consider giving the
repository a star!
