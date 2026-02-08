# Inventory Risk Monitoring & Analytics Dashboard

## Project Overview
This project demonstrates an end-to-end inventory analytics solution built using Snowflake and Tableau. The goal was to analyze inventory trends, identify excess stock risks, and provide actionable insights for supply chain decision-making across multiple plants.

Raw operational inventory data was transformed into analytical fact tables using SQL, followed by business-rule-based risk classification and executive-level reporting.



## Tech Stack
- Snowflake (Cloud Data Warehouse)
- SQL (Data Modeling & KPIs)
- Tableau (Dashboards & Visual Analytics)
- GitHub (Documentation)



## Data Architecture
RAW → MODELED → REPORTING

- RAW: Inventory transactions and operational data
- MODELED: Daily inventory fact table with calculated KPIs
- REPORTING: Aggregated KPI marts and risk monitoring views



## Key Metrics
- Total Inventory Value
- Days of Supply
- Units Purchased vs Consumed
- Excess Inventory Risk Level (Low / Medium)



## Tableau Dashboard
The interactive dashboard includes:
- Inventory Value Trend by Plant
- Days of Supply Comparison Across Plants
- Excess Inventory Risk Heatmap over time



## Business Impact
This solution helps supply chain teams:
- Detect overstocking risks early
- Compare inventory health across plants
- Reduce capital tied up in excess inventory
- Enable data-driven inventory optimization decisions
