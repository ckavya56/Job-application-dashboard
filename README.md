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

### XLOOKUP

XLOOKUP was used to retrieve company-related information from the Company Master table.

```excel
=XLOOKUP([@Company],Table1[Company],Table1[Industry])
