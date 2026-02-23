# Calculations & Pivot Tables

## About This Folder

This folder contains all Key Performance Indicator (KPI) calculations, pivot table analyses, and analytical computations performed on the cleaned crime dataset.
The objective of this analysis is to extract meaningful insights related to crime trends, area distribution, case resolution patterns, and demographic impact.

---

## Files

- LOGS: Contains all KPI formulas, intermediate calculations, and verification sheets.
---

# Key Performance Indicators (KPIs)

## KPI 1: Crime_Type_Yearly

Formula: =ROUND(Total_Crime/Year_Total,2)
Purpose: Calculates the percentage contribution of each crime type within a specific year.
Insight: Identifies dominant crime categories and year-over-year trend shifts.

---

## KPI 2: Crime_Per_Area

Formula: =INDEX(Range,MATCH(Value,Lookup_Range,0))
Purpose: Dynamically retrieves crime count for a specific area.
Insight: Helps identify high-crime zones.

---

## KPI 3: Crime_Time

Formula: =SUM(Range)
Purpose: Calculates total crimes occurring within specific time intervals.
Insight: Reveals peak crime hours.

---

## KPI 4: Case_Status_Yearly

Formula: =SUMIF(Range,Criteria,Sum_Range)
Purpose: Calculates total cases per status (Open, Closed, Pending) for each year.
Insight: Evaluates case resolution performance over time.

---

## KPI 5: Case_Yearly_Reported

Formula: =INDEX(Range,MATCH(Year,Year_Range,0))
Purpose: Retrieves total reported cases per year.
Insight: Tracks annual crime reporting trends.

---

## KPI 6: Yearly_GenderWise_Crime_Reported

Formula: =SUM(Range1)-SUM(Range2)
Purpose: Compares crime reports between genders.
Insight: Identifies demographic crime trends.

---

# Pivot Table Analyses

## Pivot 1: Crime_Type_Yearly

Rows: Crime_Type  
Columns: Year_Occured  
Values: Count of Records  
Insight: Shows distribution of crime types across years and identifies rising or declining trends.

---

## Pivot 2: Crime_Per_Area

Rows: Area_Name  
Columns: None  
Values: Count of Records  
Insight: Highlights geographical crime concentration.

---

## Pivot 3: Crime_Time

Rows: Time_Occured_Hour  
Columns: None  
Values: Count of Records  
Insight: Identifies high-risk time periods.

---

## Pivot 4: Case_Status_Yearly

Rows: Case_Status  
Columns: Year_Occured  
Values: Count of Records  
Insight: Compares case resolution status across years.

---

## Pivot 5: Case_Yearly_Reported

Rows: Year_Reported  
Columns: None  
Values: Count of Records  
Insight: Displays yearly crime reporting patterns.

---

## Pivot 6: Yearly_GenderWise_Crime_Reported

Rows: Year_Reported  
Columns: Victim_Gender  
Values: Count of Records  
Insight: Analyzes gender-based reporting trends over years.

---

# Calculation Methodologies

## Data Aggregation

- Removed duplicate records  
- Handled missing values  
- Standardized categorical fields  
- Extracted Year_Occured and Year_Reported  
- Extracted Time_Occured_Hour  
- Used Pivot Tables for grouped aggregation  
- Cross-verified totals using SUM validation  

---

## Statistical Methods Used

- Percentage contribution analysis  
- Year-over-year comparison  
- Conditional aggregation (SUMIF, COUNTIFS)  
- Lookup functions (INDEX + MATCH)  
- Manual total reconciliation  

---

## Core Excel Functions Used

SUM()  
SUMIF()  
SUMIFS()  
COUNTIFS()  
INDEX()  
MATCH()  
ROUND()  
AVERAGEIF()  

---


# Validation Status

[✔] All calculations verified  
[✔] Pivot tables reviewed  
[✔] Results cross-checked  
[x] KPIs documented
