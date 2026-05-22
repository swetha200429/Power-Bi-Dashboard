# Power-Bi-Dashboard

# Chain Snatching Crime Analysis using Power BI

## Project Overview
This project focuses on analyzing chain snatching crime data using Power BI.  
The dashboard helps visualize crime trends, dangerous areas, recovery status, victim demographics, and police investigation performance.

The main goal of this project is to transform raw crime data into meaningful visual insights for better understanding and decision-making.

---

## Objectives
- Analyze chain snatching incidents across different areas
- Identify high-risk locations
- Study victim demographics
- Monitor FIR and recovery status
- Visualize monthly crime trends
- Improve crime data understanding through interactive dashboards

---

## Tools & Technologies Used
- Power BI
- Microsoft Excel / CSV
- DAX (Data Analysis Expressions)
- Data Visualization Techniques

---

## Dataset Information
The dataset contains synthetic crime records with the following fields:

- Case ID
- Date & Time
- Area
- Victim Age
- Victim Gender
- Chain Weight
- Estimated Value
- Snatching Type
- Vehicle Used
- Police Station
- FIR Filed
- Status
- Suspect Count
- Recovery Days

---

## Dashboard Features
### KPI Cards
- Total Cases
- FIR Filed Cases
- Recovered Cases
- Total Estimated Loss

### Visualizations
- Monthly Crime Trend Analysis
- Area-wise Crime Distribution
- Snatching Type Analysis
- Gender-wise Victim Analysis
- FIR Status Analysis
- Recovery Status Analysis
- Dangerous Areas Table

### Interactive Features
- Area Filter
- Date Filter
- Gender Filter
- Snatching Type Filter
- Status Filter

---

## Key Insights
- Identified areas with high chain snatching incidents
- Observed monthly increase/decrease in crimes
- Compared FIR filed vs non-filed cases
- Analyzed recovery performance
- Studied common snatching methods

---

## Steps Performed
1. Imported dataset into Power BI
2. Cleaned and transformed data
3. Created DAX measures
4. Designed interactive dashboard
5. Added charts, cards, and slicers
6. Generated crime insights

---

Recovered Cases =
CALCULATE(
    COUNT(Status),
    Status = "Recovered"
)

Total Loss = SUM(Estimated_Value_INR)

## DAX Measures Used
```DAX
Total Cases = COUNT(Case_ID)

Author

Swetha
