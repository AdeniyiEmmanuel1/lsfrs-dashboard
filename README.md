# **Lagos State Fire and Rescue Service (LSFRS) - Emergency Response Dashboard (2019–2026)**

An end-to-end data analytics project analysing 7 years of emergency response data from the Lagos State Fire and Rescue Service. The project covers data cleaning, restructuring, and interactive dashboard visualisation in Tableau.

## **Project Overview**

This project transforms raw LSFRS operational data into a professional Tableau dashboard. The dashboard tracks emergency call trends, victim outcomes, false call rates, and financial impact of fire incidents across seven operational periods from May 2019 to May 2026.

---------------------------------

**Dashboard Preview**

![Dashboard Screenshot](https://github.com/AdeniyiEmmanuel1/lsfrs-dashboard/blob/main/Dashboard%201%20(3).png?raw=true)

--------------------------------

## **Key Metrics & Findings**

•	**Total Fire Calls (2019–2026):** 9,359 - rising from 1,115 to 1,634 per year (+46%)

•	**False Call Rate:**  Grew from ~5% (2019-20) to ~33% (2025-26) - a critical operational challenge

•	**Victims Rescued Alive:** 1,715 out of 2,302 total victims (74.5% rescue success rate)

•	**Victims Recovered Suspected Dead:** 587 (25.5%)

•	**Estimated Properties Saved:** ₦659 billion (86% property protection rate)

•	**Estimated Properties Lost:** ₦110 billion

•	**Total Rescue Calls (2019–2026):** 916

•	**Total Salvaged Situations: 599**

## **Tools & Technologies**

•	Microsoft Excel - Source data format

•	Python (pandas) - Data cleaning, restructuring from wide to long/tidy format, date formatting

•	Tableau Desktop - Dashboard design and interactive visualisation

•	GitHub - Version control and project hosting

## **Project Structure**

•	lsfrs_raw_uncleaned.xlsx - Raw source data

•	lsfrs_clean_tableau.csv - Cleaned, tidy-format data ready for Tableau

•	Dashboard_1.png - Final Tableau dashboard screenshot

•	README.md - Project documentation

## **Data Cleaning Steps**

10.	Removed blank rows and standardised all metric labels
    
11.	Stripped currency symbols and converted NGN values to plain numeric billions
    
12.	Converted wide-format data (one column per period) to long/tidy format (one row per metric per period)
    
13.	Added Start_Date and End_Date columns in DD/MM/YYYY format for each operational period
    
14.	Added Period_Order field for correct chronological sorting in Tableau

    
## **Dashboard Features**


•	KPI Cards with year-on-year change indicators and sparkline trend lines

•	Rescue Victims donut chart - Rescued Alive vs Recovered Suspected Dead

•	Property Protection Rate donut chart - Properties Saved vs Lost

•	Incident type breakdown bar chart (Collapsed Buildings, Explosions, Salvaged)

•	Summary of Calls Received bar chart - Fire, False, and Rescue Calls over 7 years

•	Date-filtered views using Start_Date and End_Date fields


## **How to Use**


20.	Clone the repository: git clone [https://github.com/YOUR-USERNAME/lsfrs-dashboard.git](https://github.com/AdeniyiEmmanuel1/lsfrs-dashboard)
    
22.	Open Tableau Desktop and connect to lsfrs_clean_tableau.csv
    
24.	Set Start_Date and End_Date as Date fields (format: DD/MM/YYYY)
    
26.	Set Period_Order as a Dimension for correct sorting
    
28.	Rebuild or explore the dashboard using the cleaned data
    
## **Author**

Created by **Aden Emmanuel**

**LinkedIn:** linkedin.com/in/aden-emmanuel-117440142

**Data Source:** Lagos State Fire and Rescue Service (LSFRS)

