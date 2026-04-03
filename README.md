# 🔬 MedLab Analytics Dashboard — Power BI Project

## Project Overview
A complete end-to-end data analytics dashboard built in Power BI
for a medical laboratory. This project analyses lab booking records,
revenue performance, patient behaviour and operational efficiency
to help lab management make data-driven decisions.

## Business Problem
The medical laboratory had collected booking and test records but
was not using the data to drive decisions. The goal was to build
an interactive dashboard that answers key business questions about
revenue, patients, referrals and test turnaround times.

## Dataset
- Source: Medical Laboratory booking records (Med_Lab_Cleaned.csv)
- Period: 2024
- Records: 155 clean test records
- Columns: Date, Patient ID, Test Type, Test Category,
  Price (GHS), Result Time (Hrs), New/Returning Patient,
  Peak/Off-Peak, Referral Source

## Key Findings
- Total Revenue: GHS 22,780 across 155 test records
- Average Turnaround Time: 4.45 hours per test
- New Patient Rate: 70.32% of all patients
- Returning Patient Rate: 29.68% retention
- Top Test Category: Biochemistry — GHS 6,270
- Top Referral Source: Hospital A & Hospital C
- Longest Turnaround: COVID-19 PCR — 8 hours

## Dashboard Visuals Built
1. KPI Cards — Total Revenue, Total Tests, Avg Turnaround
2. Line Chart — Monthly Revenue Trend
3. Bar Chart — Revenue by Test Category
4. Bar Chart — Revenue by Referral Source
5. Bar Chart — Avg Turnaround Time by Test Type
6. Donut Chart — New vs Returning Patients
7. Donut Chart — Peak vs Off-Peak Volume
8. Interactive Slicer — Date, Category, Referral Source

## Tools Used
- Microsoft Power BI Desktop (Dashboard & Visualisations)
- Power Query (Data Cleaning & Transformation)
- DAX — Data Analysis Expressions (Measures & Calculations)
- PDF File (Dashboard Explanation Report)

## DAX Measures Created
- Total Revenue = SUM of all test prices
- Total Tests = Count of all records
- Avg Turnaround = Average result time in hours
- New Patients = Count where Patient Type = New
- Returning Patients = Count where Patient Type = Returning
- Retention Rate % = Returning / Total x 100

## Project Deliverables
1. Power BI Dashboard (.pbix)
2. Dashboard Explanation Report (.pdf)

## Skills Demonstrated
- Data Cleaning & Transformation in Power Query
- Data Modelling & DateTable Creation
- DAX Measure Writing
- Dashboard Design & Visualisation
- Healthcare Data Analysis
- Business Reporting & Documentation

## Author
Lawrence Koomson
Aspiring Data Analyst | Data Scientist | Prompt Engineer
Accra, Ghana
