# Hospital Waitlist Analysis Dashboard – Inpatient & Outpatient Insights (Power BI)
## Project Objective

The objective of this project is to build an interactive Power BI dashboard to analyze hospital patient waitlist data with a strong focus on Inpatient, Outpatient, and Day Case categories.

This dashboard helps healthcare stakeholders monitor patient volumes, waiting times, specialty demand, and long-term trends, enabling better resource planning and patient flow optimization.

## Datasets used 
<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/IN_WL%202018.csv">Inpatient Waitlist 2018</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/IN_WL%202019.csv">Inpatient Waitlist 2019</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/IN_WL%202020.csv">Inpatient Waitlist 2020</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/IN_WL%202021.csv">Inpatient Waitlist 2021</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Op_WL%202018.csv">Outpatient Waitlist 2018</a>


<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Op_WL%202019.csv">Outpatient Waitlist 2019</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Op_WL%202020.csv">Outpatient Waitlist 2020</a>

<a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Op_WL%202021.csv">Outpatient Waitlist 2021</a>


## Business Questions & KPIs
- What is the total waitlist size and how is it distributed across Inpatient, Outpatient, and Day Case?
- How does the current waitlist compare to the previous year?
- Which case type contributes the most to the backlog?
- What are the waiting time patterns across different time bands (0–3 months, 3–6 months, etc.)?
- Which specialties have the highest patient load?
- How do age groups impact waiting times?
- What are the monthly trends for each case type?

- Dashboard Interaction - <a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/summary.png">Summary Dashboard</a> - <a href ="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Detailed%20view.png">Detailed View</a> - <a href="https://github.com/pavanijadhav08/Hospital-Waitlist-Analysis-Dashboard/blob/main/Drilldown.png">DrillDown</a>


## Key Performance Indicators (KPIs)

- Total Waitlist Patients (Overall)
- Latest Month Waitlist vs Previous Year
- Average Waiting Time
- Case Type Distribution
   - Outpatient
   - Inpatient
   - Day Case
- Top 5 Specialties by Waitlist
- Time Band Distribution (0–3, 3–6, 6–9, 9–12, 12–18, 18+ months)
- Age Group Distribution (0–15, 16–64, 65+)
- Monthly Trend Analysis by Case Type



## Process

1. Data Collection
- Collected structured hospital data including:
- Archive Date
- Case Type (Inpatient, Outpatient, Day Case)
- Specialty Name
- Age Profile
- Waiting Time Bands

2.  Data Cleaning & Transformation
- Handled missing and inconsistent values
- Standardized date formats
- Created meaningful categories for:
- Age groups
- Time bands
- Developed calculated measures using DAX for KPIs and comparisons

3. Data Modeling
- Built relationships between datasets
- Optimized model for performance and filtering
- Enabled drill-down capabilities

4. Dashboard Development

- Created 3 interactive views:

- Summary View
  - KPI cards (Total Waitlist, Comparison)
  - Case type distribution (Donut chart)
  - Time band vs Age profile (Stacked bar chart)
  - Top specialties
    
- Detailed View
  - Tabular breakdown of:
  - Inpatient
  - Outpatient
  - Day Case
  - Drillable hierarchy (Date → Age → Time Band)
    
- Drilldown View
 - Specialty-wise waitlist distribution
 - Deep insights into backlog contribution

5.  Visualization Design
- Donut chart → Case type distribution
- Line chart → Monthly trends
- Stacked bar chart → Time band vs age
- KPI cards → High-level metrics
- Applied a dark-themed, professional UI for clarity

  ## Dashboard
 <img width="1211" height="679" alt="summary" src="https://github.com/user-attachments/assets/e302e779-2904-4a11-879f-d62fbd5ff238" />
  <img width="1378" height="777" alt="Detailed view" src="https://github.com/user-attachments/assets/4338ca19-f39b-474c-b192-916fe91e354a" />
  <img width="1703" height="675" alt="Drilldown" src="https://github.com/user-attachments/assets/b08c0173-4593-4d11-96ac-0d728bf4c357" />




## Conclusion

- This dashboard provides a comprehensive and structured analysis of hospital waitlist data across Inpatient, Outpatient, and Day Case categories.

- It enables decision-makers to:

  - Identify high-pressure areas in patient care
  - Reduce long waiting times
  - Allocate resources efficiently
  - Improve hospital operational planning

- Overall, the project demonstrates how Power BI and data analytics can transform raw healthcare data into actionable  insights for better decision-making.

 
 ## Tools & Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization
