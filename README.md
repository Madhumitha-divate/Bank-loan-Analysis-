 Bank Loan Analysis – Finance Domain

SQL | Power BI | Data Modelling | Dashboarding

 Project Overview:

This project focuses on analysing a bank’s loan portfolio to identify trends, customer risk patterns, loan performance, and business insights.
Using My SQL for data cleaning & KPI extraction, and Power BI for dashboard development, this project provides an end-to-end 
analytical solution for financial decision-making.

 Problem Statement:

The bank receives thousands of loan applications every month, but the data is unstructured and spread across multiple fields.
The goal is to:
Analyse loan performance over time,Identify high-risk loansCheck the impact of interest rate, DTI, home ownership,
and loan purpose,Compare regional performance,Provide an interactive Power BI dashboard for business users


Tools & Technologies:
 SQL Server – Data Cleaning, KPI Extraction
 Power BI – Data Modelling, DAX, Dashboard Creation
 Power Query – Data Transformation

Steps Taken:
1.Data Understanding & Exploration:
 Reviewed raw loan dataset structure
 Understood finance domain metrics (Loan Status, DTI, Interest Rate, Loan Purpose, Home Ownership)

2. Data Cleaning in SQL:
 Removed duplicates and nulls, Standardized date formats, Cleaned loan status labels
 Verified numerical fields (DTI, interest rate, funded_amount)

3. KPI Extraction:
 SQL queries used to calculate:
 Total Loan Applications, Total Funded Amount, Average Interest Rate,Average DTI
 Good vs Bad Loan Ratio, Loan Purpose Summary, Regional Loan Distribution

4.Power BI Data Modelling:
 Connected SQL database to Power BI, Created Date Table using DAX
 Built relationships between fact and dimension tables
 Added calculated columns & measures

5. Dashboard Development
  Designed interactive visuals:
  KPIs: Applications, Funded Amount, Interest Rate, DTI
  Trend Analysis: Month-wise loan applications
  Regional Map: State-wise performance
  Loan Purpose Analysis
  Home Ownership Impact
  Good vs Bad Loan Analysis
  Filters/Slicers: State, Purpose, Ownership, Loan Status

6. Interactivity Enhancements
  Navigation buttons, Drill-throughs, Field parameters, Slicer sync across pages

Key Insights:
  Loan applications and funded amounts show strong seasonal and state-wise variations.
  Higher DTI and interest rates correlate with increased default (bad loan) probability.
  Certain loan purposes (e.g., small business loans) show higher risk.
  Homeowners tend to have better repayment performance compared to non-homeowners.
  The dashboard enables business teams to explore specific customer segments and risk categories.

 Outcome:
   A comprehensive Power BI dashboard that provides the bank with:
   Visibility into loan performance,Customer risk assessment
   Regional and purpose-based trends,Actionable insights for better decision-making
