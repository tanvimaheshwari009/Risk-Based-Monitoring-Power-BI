# 📊 Risk-Based Monitoring (RBM) Dashboard | Power BI & SQL Server

## Overview

This project demonstrates the development of an interactive **Risk-Based Monitoring (RBM) Dashboard** for a simulated multicenter **Phase III Oncology Clinical Trial**.

The dashboard provides real-time insights into site performance, patient safety, and operational metrics that can support centralized clinical trial monitoring. It was created as a portfolio project to demonstrate skills in **Clinical Research Analytics**, **SQL Server**, **Power BI**, **DAX**, and **Data Visualization**.

---

## Dashboard Preview
<img width="835" height="542" alt="Screenshot 2026-07-15 153143" src="https://github.com/user-attachments/assets/5c2975c5-80ce-4da4-ad3e-5ef254fab770" />

---

## Project Objectives

The objective of this dashboard is to help clinical trial teams:

- Monitor overall study progress
- Identify high-risk clinical sites
- Track Serious Adverse Events (SAEs)
- Monitor open clinical queries
- Evaluate average query resolution time
- Recommend monitoring strategies based on site risk
- Provide interactive filtering for better decision making

---

## Business Problem

Clinical trials generate large volumes of operational and safety data from multiple investigational sites. Reviewing this information manually is time-consuming and may delay identification of high-risk sites.

This dashboard demonstrates how **Risk-Based Monitoring (RBM)** principles can be applied using Power BI to visualize important Key Risk Indicators (KRIs) and support data-driven monitoring decisions.

---

## Dashboard Components

### KPI Cards

- Total Sites
- Total Patients
- Total Serious Adverse Events (SAEs)
- High Risk Sites
- Open Queries
- Average Query Resolution Time (Days)

---

### Visualizations

✔ Risk Distribution (Donut Chart)

Displays the proportion of:

- Low Risk Sites
- Medium Risk Sites
- High Risk Sites

---

✔ Top High-Risk Sites (Bar Chart)

Ranks clinical sites according to their calculated risk score.

---

✔ Monitoring Recommendation

Displays recommended monitoring strategy:

- Remote Monitoring
- Targeted Monitoring
- On-site Monitoring

---

✔ Site Summary Table

Includes:

- Site Name
- Region
- Patient Count
- Risk Score
- Risk Category
- Monitoring Recommendation

Conditional formatting is used to highlight different risk levels.

---

✔ Interactive Filters (Slicers)

Users can filter dashboard results by:

- Site Name
- Region
- Risk Category

---

✔ Key Insights

Automatically summarizes important findings from the dashboard.

Example:

- High Risk Site requires immediate attention.
- Majority of sites are Low Risk.
- Average Query Resolution Time is 6.29 days.
- Remote Monitoring recommended for most sites.

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| SQL Server | Database creation and querying |
| Power BI Desktop | Dashboard development |
| Power Query | Data transformation |
| DAX | KPI calculations and measures |
| Microsoft Excel | Initial dataset preparation |

---

## Skills Demonstrated

- Clinical Trial Analytics
- Risk-Based Monitoring (RBM)
- SQL Querying
- Data Cleaning
- Power Query
- DAX Measures
- Dashboard Design
- Data Visualization
- KPI Development
- Interactive Reporting

---

## Dataset

This project uses a **simulated clinical trial dataset** created for learning and portfolio purposes.

The dataset includes:

- Site Information
- Patient Count
- SAE Count
- Risk Score
- Risk Category
- Query Metrics
- Monitoring Recommendation

No real patient or clinical trial data has been used.

---

## Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Sites | Number of participating clinical sites |
| Total Patients | Total enrolled patients |
| Total SAEs | Total Serious Adverse Events |
| High Risk Sites | Sites categorized as High Risk |
| Open Queries | Outstanding clinical queries |
| Average Query Resolution Time | Average days required to close queries |

---

## Risk Classification

Sites are categorized into:

🟢 Low Risk

🟡 Medium Risk

🔴 High Risk

Monitoring recommendations are generated based on the overall site risk.

---

## Project Workflow

1. Created simulated clinical trial dataset.
2. Imported data into SQL Server.
3. Queried and validated data.
4. Connected SQL Server to Power BI.
5. Performed data transformation using Power Query.
6. Created DAX measures.
7. Designed dashboard layout.
8. Added interactive visuals and slicers.
9. Generated monitoring insights.

---

## Repository Contents

```
Risk-Based-Monitoring-Power-BI/
│
├── README.md
├── Dashboard.png
```

*SQL scripts and Power BI (.pbix) file are not included in this public repository.*

---

## Learning Outcomes

Through this project I gained hands-on experience in:

- Clinical trial data visualization
- Risk-Based Monitoring concepts
- Power BI dashboard development
- SQL Server integration
- DAX calculations
- Interactive report design

---

## Future Improvements

Future versions may include:

- Patient enrollment trends
- SAE trends over time
- Protocol deviation analysis
- Site performance scorecards
- Global site risk map
- Time-series analysis
- Advanced DAX measures
- Drill-through pages

---

## Author

**Tanvi Maheshwari**

Bachelor of Pharmacy (B.Pharm)

Interested in:

- Clinical Research
- Clinical Data Management
- Risk-Based Monitoring (RBM)
- Clinical Data Analytics
- SQL
- Power BI

 ---

## Disclaimer

This project is created solely for educational and portfolio purposes using simulated clinical trial data. It does not represent any real clinical study or patient information.

*(SQL scripts and PBIX file are not included in this public repository.)*

## Author
Tanvi Maheshwari
B.Pharm | Clinical Research | Power BI | SQL


Interested in Clinical Research, Clinical Data Management, Risk-Based Monitoring and Data Analytics.
