# 🚍 Urban Transport Ridership Analysis – Chicago & Philadelphia

## 📌 Project Overview
This project aims to analyze and compare urban public transport ridership in **Chicago** and **Philadelphia** using historical data.  
The objective is to build an **interactive Power BI dashboard** that enables stakeholders to:
- Monitor ridership trends over time
- Compare performance by route and by transport mode
- Detect anomalies and seasonality
- Support strategic decision-making for service optimization

---

## 🎯 Business Context
Urban transport agencies collect large volumes of historical and operational data.  
To ensure effective reporting and analysis, it is necessary to:
- Combine heterogeneous data sources (RDF, CSV, Excel, APIs)
- Apply statistical analysis and predictive modeling
- Build a reliable data model for BI reporting

---

## 🧩 Data Sources

### Chicago
- **RDF files**: Daily Ridership by Route
- **Excel**: CTA Daily Boarding Totals (Bus / Rail / Total)

### Philadelphia
- **CSV files**: Monthly Average Ridership by Mode and Route

---

## 🛠️ Technical Stack
- **Python**: pandas, numpy, scipy, statsmodels, matplotlib
- **Power BI Desktop**: Power Query, Data Modeling, DAX
- **Version Control**: Git & GitHub
- **Project Management**: Jira, Confluence

---

## 🔄 ETL & Data Preparation
- Conversion of RDF files to CSV using Python
- Cleaning and normalization of datasets
- Aggregation of Chicago daily data into **monthly averages**
- Standardization of Philadelphia data (already monthly averages)
- Export of clean datasets for Power BI

---

## 🧱 Data Model
Star schema with:
- **Fact tables**
  - Fact_mode_chicago
  - Fact_route_chicago
  - Fact_mode_phila
  - Fact_route_phila
- **Dimension tables**
  - Dim_year
  - Dim_month

All fact tables are connected only through time dimensions to ensure consistent filtering and granularity.

---

## 📊 Dashboards
### Page 1 – Ridership by Route
- Top 10 routes by average monthly ridership (Chicago & Philadelphia)
- Monthly trends for selected routes
- Key KPIs (min, max, average ridership)

### Page 2 – Ridership by Mode
- Comparison of Bus vs Rail ridership
- Chicago vs Philadelphia
- Monthly trends and mode distribution
- Interactive filters by year and month


---

## 📦 Deliverables
- Python Notebook (ETL & statistical analysis)
- Power BI file (.pbix)
- GitHub repository with documentation
- Project presentation (PPT)

---

