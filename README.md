# Job Application Dashboard

## Overview

The **Job Application Dashboard** is an Excel-based data analysis project developed to track and analyze job applications across different stages of the recruitment process.

The project uses a structured job application dataset and Excel features such as **XLOOKUP, PivotTables, PivotCharts, formulas, conditional formatting, and data visualization** to convert raw data into meaningful insights through a centralized dashboard.

> **Dataset Note:** The dataset used in this project is a simulated/sample dataset created for learning, analysis, and dashboard development purposes.

---

## Objectives

- Track job applications across different recruitment stages
- Analyze applications by company, role, location, and source
- Analyze salary information
- Monitor application activity over time
- Analyze applications by work mode
- Calculate recruitment outcome metrics
- Present the analysis through an easy-to-understand Excel dashboard

---

## Dataset

The main **Applications** table contains the following fields:

- Application_ID
- Company
- Role
- Location
- Salary
- Applied_Date
- Status
- Source
- Work_Mode
- Experience
- Degree
- Job_Type
- Month

A separate **Company_Master** table was created with:

- Company
- Industry
- Company_Size

---

## Excel Features Used

This project demonstrates practical use of several Microsoft Excel features:

- **Excel Tables** – Used to organize and manage the application dataset in a structured format.
- **XLOOKUP** – Used to retrieve company information from the Company Master table and connect related datasets.
- **Excel Formulas** – Used functions such as AVERAGE, MAX, MIN, COUNT, COUNTIF, COUNTIFS, IF, and TEXT for calculations and analysis.
- **PivotTables** – Used to summarize and analyze application data across different categories.
- **PivotCharts** – Used to create visual representations of PivotTable results.
- **Sorting and Filtering** – Used to organize application data and identify patterns more easily.
- **Conditional Formatting** – Used to improve readability and highlight important information.
- **Date and Month Analysis** – Used application dates to analyze monthly application trends.
- **KPI Calculations** – Created metrics such as total applications, interview rate, offer rate, rejection rate, average salary, highest salary, and lowest salary.
- **Data Visualization** – Used Column, Bar, Line, and Doughnut charts to present insights.
- **Dashboard Design** – Combined KPIs, charts, and analysis into a centralized interactive dashboard.
