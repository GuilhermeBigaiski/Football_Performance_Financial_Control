# Football Performance & Financial Control

End-to-end project focused on football performance statistics, attendance tracking, and financial control and management.

---

## TL;DR
End-to-end data solution using PostgreSQL, Streamlit, SQL, and Power BI to automate football performance tracking, attendance control, and financial management through structured data ingestion and analytical dashboards.

---

## Project Overview
This project consists of an end-to-end data solution developed to improve data update and maintenance processes, increase data reliability, and bring more agility and structure to information ingestion.

The solution was designed to be simple, scalable, and easy to maintain, allowing continuous evolution as the system moves into real-world usage.

---

## Problem Statement
The main challenge faced by the group regarding player performance tracking and financial management was the reliance on manual spreadsheets. This approach led to data inconsistencies, difficulties in updating information, and a lack of transparency around the group’s overall financial situation.

---

## Solution Overview
To address these challenges, a relational database was modeled in Supabase using PostgreSQL. Subsequently, two data ingestion forms — statistics and financial — were developed using Python and Streamlit, with initial scripting support from ChatGPT.

With a centralized database and an automated, secure, and standardized data ingestion process in place, a Power BI dashboard was created to clearly present all the information required for performance analysis and financial control.

---

## Architecture


---

## Project Modules

- **Statistics Data Ingestion (Streamlit + Python)**  
  https://github.com/GuilhermeBigaiski/Estatisticas_Pelada

- **Financial Data Ingestion (Streamlit + Python)**  
  https://github.com/GuilhermeBigaiski/Financeiro_Pelada

---

## Technologies Used
- Supabase
- PostgreSQL
- GitHub
- Streamlit
- Python
- Power BI
- DAX
- Excel
- Relational Data Modeling

---

## Current Status
The dashboard does not yet contain real match data (matches played, goals scored, attendance), as the first official match is scheduled for February 5th. The data currently available was inserted exclusively for testing and validation of the dashboard, database, and data ingestion forms.

---

## Related Links

- **Portfolio / Documentation**  
  https://www.notion.so/Football-Performance-Financial-Control-End-to-End-Data-Project-2f03bca111ad80d88bf7c9f00543b6c4

- **Dashboard (Power BI)**  
  https://app.powerbi.com/view?r=eyJrIjoiYzlhZjMxYjEtYjUzYS00YjJiLWExMWEtYWRhYTYzZWM3ZjMxIiwidCI6IjNhNzhiMGNkLTdjOGUtNDkyOS04M2Q1LTE5MGE2Y2MwMTM2NSJ9
