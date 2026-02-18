# DVA Capstone 1 - Group 13 (Section E)

> **Course:** Data Visualization & Analytics (DVA)  
> **Institution:** Newton School of Technology  
> **Team:** G-13, Section E  
> **Academic Year:** 2026

## 👥 Team Members

| Name | Enrollment Number | Section |
|------|------------------|---------|
| Akshat Agrawal | 2401010054 | E |
| Aman | 2401010060 | E |
| Ishita Thakur | 2401010195 | E |
| Pranavi Mathur | 2401020046 | E |
| Khushi Jain | 2401010227 | E |
| Ritesh Kumar | 2401010384 | E |


---

## 📋 Project Overview

**Project Title:** Crime Trend Analysis in Los Angeles

**Industry Sector:** Home Affairs & National Security

**Problem Statement:** 
[Los Angeles experiences a significant number of reported crimes each year. Without structured analysis, it becomes difficult to identify the highest-risk areas, major crime drivers, and operational gaps. This project analyses crime trends from 2020–2024 to surface actionable insights that can support crime reduction strategies and improve public safety planning]

**Objectives:**
- [The objective of this project is to
identify year-wise crime trends,
dominant crime categories,
hotspot areas, peak time windows,
and case closure performance
using crime data from 2020–2024.]
- [These insights will support
targeted decision-making to
reduce crime and improve
operational efficiency in high-risk
zones.]

**Tools & Technologies:**
- **Primary:** Google Sheets (Mandatory)
- **Version Control:** GitHub

---

## 📊 Dataset Analysis

### Dataset Information

**Dataset Name:** [Crime_Data_from_2020_to_Present_20260211]

**Source:** [data.lacity.org](https://data.lacity.org/)

**Size:** 
- Number of Records: [10,000 rows]
- Number of Features: [30 columns]

**Time Period:** [February 2026]

### Google Sheets Links

**Main Project Sheet:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?usp=sharing]

**Cleaned Data Sheet:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?gid=97077233#gid=97077233]

**KPI Dashboard Sheet:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?gid=167284618#gid=167284618]

**Pivot Analysis Sheet:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?usp=sharing]


### Key Fields Explanation

**[Dangerous Zone (Top
Crime Area)]:** [Identifies the highest
crime area to prioritize
hotspot deployment and
resource allocation.]
**[Case_Status]:** [Identifies status of case whether it is solved or not]


### Statistical Insights

- **Total Records Analyzed:** [~10000]
- **Time Period Covered:** [2020 to 2024]

### Trend Analysis

- **[Serious Crimes]:** [60%]
- **[Less Serious Crimes]:** [40%]


## 🔍 Analysis Suggestions

### Recommended Analysis Approaches

1. **Descriptive Analysis**
   - Summary statistics for all numerical fields
   - Frequency distributions for categorical variables
   - Time-based trend analysis

2. **Comparative Analysis**
   - Segment comparison (e.g., Region A vs Region B)
   - Time period comparison (Year-over-Year, Month-over-Month)
   - Performance benchmarking

3. **Diagnostic Analysis**
   - Root cause analysis for outliers
   - Factor analysis for key metrics
   - Correlation studies

4. **Predictive Analysis (Optional)**
   - Trend extrapolation
   - Seasonal pattern identification
   - Simple forecasting models

### Pivot Table Recommendations

1. **[Analysis Name]:** [Rows] × [Columns] → Analyze [Metric]
2. **[Analysis Name]:** [Rows] × [Columns] → Analyze [Metric]
3. **[Analysis Name]:** [Rows] × [Columns] → Analyze [Metric]

### Visualization Recommendations

- **Bar Charts:** For comparing categories (e.g., Sales by Region)
- **Line Charts:** For time series trends (e.g., Monthly Revenue)
- **Pie Charts:** For composition analysis (e.g., Market Share)
- **Scatter Plots:** For correlation analysis (e.g., Price vs Sales)
- **Heat Maps:** For pattern identification (e.g., Sales by Day/Hour)

---

## 🧹 Data Cleaning Notes

### Data Quality Assessment

**Initial Data Quality Issues:**
- [ ] Missing values
- [ ] Duplicate records
- [ ] Inconsistent formatting
- [ ] Outliers
- [ ] Data type mismatches
- [ ] Invalid entries

### Cleaning Steps Performed

1. **Missing Value Handling**
   - **Field:** [Column name]
   - **Issue:** [X% missing values]
   - **Action:** [Imputed with mean/median/mode, or removed rows]
   - **Justification:** [Why this approach was chosen]

2. **Duplicate Removal**
   - **Records Before:** [Number]
   - **Duplicates Found:** [Number]
   - **Records After:** [Number]
   - **Criteria:** [How duplicates were identified]

3. **Data Type Corrections**
   - **Field:** [Column name]
   - **Original Type:** [e.g., Text]
   - **New Type:** [e.g., Date]
   - **Conversion Method:** [How it was converted]

4. **Standardization**
   - **Field:** [Column name]
   - **Action:** [e.g., Converted all text to uppercase, standardized date format]
   - **Impact:** [Number of records affected]

5. **Outlier Treatment**
   - **Field:** [Column name]
   - **Method:** [e.g., IQR method, Z-score]
   - **Outliers Identified:** [Number]
   - **Action Taken:** [Capped, removed, or retained with justification]

6. **Feature Engineering**
   - **New Field:** [Name]
   - **Formula:** [How it was calculated]
   - **Purpose:** [Why it was created]

### Data Quality Metrics

| Metric | Before Cleaning | After Cleaning | Improvement |
|--------|----------------|----------------|-------------|
| Completeness | [%] | [%] | [%] |
| Accuracy | [%] | [%] | [%] |
| Consistency | [%] | [%] | [%] |
| Duplicates | [count] | [count] | [-count] |

### Cleaning Scripts/Formulas Used

```
[List key Google Sheets formulas or Python scripts used for cleaning]
Example:
- Remove duplicates: =UNIQUE(A2:Z1000)
- Fill missing values: =IFERROR(A2, AVERAGE($A$2:$A$1000))
- Standardize text: =UPPER(TRIM(A2))
```

---

## 📈 Dashboard Summaries

### Dashboard 1: [Dashboard Name]

**Purpose:** [What business question does this dashboard answer?]

**Key Metrics Displayed:**
- [Metric 1]: [Description and value]
- [Metric 2]: [Description and value]
- [Metric 3]: [Description and value]

**Visualizations:**
1. [Chart Type]: [What it shows]
2. [Chart Type]: [What it shows]
3. [Chart Type]: [What it shows]

**Insights:**
- [Key insight 1]
- [Key insight 2]
- [Key insight 3]

**Access:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?usp=sharing]

---

### Dashboard 2: [Dashboard Name]

**Purpose:** [What business question does this dashboard answer?]

**Key Metrics Displayed:**
- [Metric 1]: [Description and value]
- [Metric 2]: [Description and value]

**Visualizations:**
1. [Chart Type]: [What it shows]
2. [Chart Type]: [What it shows]

**Insights:**
- [Key insight 1]
- [Key insight 2]

**Access:** [Link]

---

## 📊 Forecasting (Optional)

### Forecasting Methodology

**Target Variable:** [What you're forecasting]

**Method Used:** [e.g., Moving Average, Trend Analysis, Regression]

**Time Horizon:** [e.g., Next 6 months, Next quarter]

**Data Used:** [Time period of historical data]

### Forecast Results

| Period | Forecasted Value | Confidence Level |
|--------|-----------------|------------------|
| [Period 1] | [Value] | [e.g., 85%] |
| [Period 2] | [Value] | [e.g., 80%] |
| [Period 3] | [Value] | [e.g., 75%] |

### Assumptions & Limitations

- [Assumption 1]
- [Assumption 2]
- [Limitation 1]
- [Limitation 2]

---

## 🚀 Key Recommendations

Based on our analysis, we recommend the following actions:

1. **[Recommendation 1]**
   - **Action:** [Specific action to take]
   - **Expected Impact:** [Quantified expected outcome]
   - **Priority:** [High/Medium/Low]
   - **Timeline:** [When to implement]

2. **[Recommendation 2]**
   - **Action:** [Specific action to take]
   - **Expected Impact:** [Quantified expected outcome]
   - **Priority:** [High/Medium/Low]
   - **Timeline:** [When to implement]

3. **[Recommendation 3]**
   - **Action:** [Specific action to take]
   - **Expected Impact:** [Quantified expected outcome]
   - **Priority:** [High/Medium/Low]
   - **Timeline:** [When to implement]

---

## 🌐 Project Website

**Live Demo:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?usp=sharing]

**Features:**
- Interactive dashboard
- Data exploration tools
- Download reports

---

## 📚 Additional Resources

### Documentation
- [Data Dictionary](https://data.lacity.org/)
- [Analysis Report](https://www.canva.com/design/DAHBpRq_eqY/LsIckeAq8rokjP74N03Y7Q/edit?utm_content=DAHBpRq_eqY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

### Presentation Materials
- [Final Presentation](https://www.canva.com/design/DAHBgnX95oc/hAPZIetUzR-FQlYHQukAvg/edit?utm_content=DAHBgnX95oc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 👥 Team Contributions

| Team Member | Responsibilities | Contributions |
|-------------|------------------|---------------|
| [Name 1] | [Role] | [Key contributions] |
| [Name 2] | [Role] | [Key contributions] |
| [Name 3] | [Role] | [Key contributions] |

---

## 📝 Project Timeline

| Phase | Duration | Status | Completion Date |
|-------|----------|--------|-----------------|
| Dataset Selection & Approval | [X weeks] | ✅ Completed | [Date] |
| Data Cleaning | [X weeks] | ✅ Completed | [Date] |
| KPI Design | [X weeks] | ✅ Completed | [Date] |
| Pivot Analysis | [X weeks] | 🔄 In Progress | [Date] |
| Dashboard Development | [X weeks] | ⏳ Pending | [Date] |
| Final Presentation | [X weeks] | ⏳ Pending | [Date] |

---

## 🔗 Important Links

- **GitHub Repository:** [https://github.com/ratinto/CapstoneDVA-E13](https://github.com/ratinto/CapstoneDVA-E13)
- **Google Sheets - Main Project:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?usp=sharing]
- **Google Sheets - Cleaned Data:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?gid=97077233#gid=97077233]
- **Google Sheets - KPI Dashboard:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?gid=167284618#gid=167284618]

---

## 📞 Contact Information

For questions or collaboration:
- **Team Lead:** [Name] - [Email]
- **GitHub:** [@ratinto](https://github.com/ratinto)

---

## 📄 License

This project is part of the Capstone DVA course and is intended for educational purposes.

---

## 🙏 Acknowledgments

- Course Instructors: [Names]
- Data Source: [Organization/Platform]
- Tools: Google Sheets, Looker Studio (optional), Python (optional)

---

**Last Updated:** February 15, 2026

**Status:** 🔄 In Progress

---

## ✅ Project Checklist

### Data & Cleaning
- [ ] Approved dataset obtained
- [ ] Raw data uploaded to RawDataset folder
- [ ] Data cleaning completed
- [ ] Cleaned data uploaded to Cleaned folder
- [ ] Cleaning log documented

### Analysis
- [ ] KPIs designed and calculated
- [ ] Pivot tables created
- [ ] Statistical analysis completed
- [ ] Insights documented

### Deliverables
- [ ] Dashboard created in Google Sheets
- [ ] Optional: Looker Studio dashboard
- [ ] Documentation completed
- [ ] Data dictionary created
- [ ] Final presentation prepared

### Repository
- [ ] All folders properly structured
- [ ] README.md completed with all sections
- [ ] Regular commits maintained
- [ ] Repository kept updated
- [ ] Links verified and working

---

*This README follows the mandatory requirements for Capstone 1 DVA project.*
