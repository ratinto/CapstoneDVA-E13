# Raw Dataset - LAPD Crime Data (2020–2024)

## About This Folder

This folder contains the original, unmodified LAPD crime dataset used for the Los Angeles Crime Analytics Capstone project. This dataset forms the foundation of our public safety analysis and dashboard.

---

## 📂 Files

- `Crime_Data_from_2020_to_Present.csv` - Original LAPD crime records dataset
- `data_source_info.txt` - Detailed information about data acquisition and source documentation

---

## 📊 Dataset Information

### Overview

**Dataset Name:** Crime Data from 2020 to Present

**Source:** Los Angeles Police Department (LAPD) Open Data Portal

**Data Provider:** City of Los Angeles

**Date Obtained:** February 2026

**Original File Size:** ~195 MB

**Number of Records:** ~10,000 (subset used for analysis)

**Number of Columns:** 28

**Data Format:** CSV (Comma-Separated Values)

**Time Period Covered:** January 1, 2020 – December 31, 2024

---

## 🗂️ Dataset Structure

### Column Details

| Column Name (Original) | Data Type | Description | Example |
|---|---|---|---|
| `DR_NO` | Text | Division of Records Number (Unique ID) | 200100501 |
| `Date Rptd` | Date | Date crime was reported | 01/08/2020 |
| `DATE OCC` | Date | Date crime occurred | 01/08/2020 |
| `TIME OCC` | Integer | Time crime occurred (24hr format) | 2230 |
| `AREA` | Integer | Geographic area code | 01 |
| `AREA NAME` | Text | Geographic area name | Central |
| `Rpt Dist No` | Integer | Reporting district number | 0111 |
| `Part 1-2` | Integer | Crime classification (1=Serious, 2=Less Serious) | 1 |
| `Crm Cd` | Integer | Crime code | 624 |
| `Crm Cd Desc` | Text | Crime code description | BATTERY - SIMPLE ASSAULT |
| `Mocodes` | Text | Modus operandi codes | 0344 0913 |
| `Vict Age` | Integer | Victim's age | 36 |
| `Vict Sex` | Text | Victim's sex (M/F/X) | M |
| `Vict Descent` | Text | Victim's ethnicity code | H |
| `Premis Cd` | Integer | Premise code | 101 |
| `Premis Desc` | Text | Premise description | STREET |
| `Weapon Used Cd` | Integer | Weapon used code | 400 |
| `Weapon Desc` | Text | Weapon description | STRONG-ARM |
| `Status` | Text | Case status code | IC |
| `Status Desc` | Text | Case status description | Invest Cont |
| `Crm Cd 1-4` | Integer | Additional crime codes | Various |
| `LOCATION` | Text | Street address | 700 S HILL ST |
| `Cross Street` | Text | Nearest cross street | 7TH ST |
| `LAT` | Decimal | Latitude coordinate | 34.0448 |
| `LON` | Decimal | Longitude coordinate | -118.2545 |

---

## 📍 Data Source Details

### Provider Information

**Organization:** Los Angeles Police Department (LAPD)

**Platform:** City of Los Angeles Open Data Portal

**Data Portal URL:** https://data.lacity.org/

**Dataset ID:** Crime Data from 2020 to Present

**License:** Open Data Commons Public Domain Dedication and License (PDDL)

**Usage Rights:** Public domain — free to use, modify, and distribute

**Update Frequency:** Updated weekly by LAPD

---

### Data Collection Methodology

- **Primary Source:** LAPD Incident Reporting System
- **Collection Method:** Official police reports filed by officers
- **Data Entry:** Manual and automated systems
- **Quality Control:** LAPD data verification procedures
- **Geocoding:** Addresses converted to latitude/longitude coordinates
- **Privacy Protection:** Personal identifiable information removed

---

### Coverage Details

**Geographic Coverage:** All 21 LAPD Community Police Stations

**Temporal Coverage:** January 1, 2020 – December 31, 2024 (5 years)

**Crime Types:** All Part I and Part II crimes as defined by FBI UCR standards

**Reporting Standard:** Uniform Crime Reporting (UCR) classification

---

## ⚠️ Important Notes

### Data Integrity

🔒 **DO NOT modify files in this folder.**  
This is the original dataset and must remain unchanged for:
- Reference and comparison purposes
- Audit trail documentation
- Reproducibility of analysis
- Academic integrity requirements

### Data Processing

✅ For cleaned and processed data, refer to the `Cleaned/` folder

✅ All transformations and cleaning operations are documented in `Cleaned/LOGS`

✅ Original-to-cleaned mapping available in project documentation

---

## 🔍 Data Quality Notes

### Known Limitations

1. **Missing Values:**
   - Some records contain blank fields for victim demographics
   - Weapon descriptions may be missing for certain crime types
   - Geographic coordinates may be generalized for privacy

2. **Data Entry Variations:**
   - Text fields may have inconsistent capitalization
   - Some codes may require lookup tables for interpretation

3. **Time Precision:**
   - TIME OCC rounded to nearest minute
   - Some historical records may have estimated times

4. **Privacy Considerations:**
   - Addresses may be rounded to nearest hundred block
   - Exact locations may be obscured for sensitive crime types

---

## 📚 Related Documentation

- **Data Dictionary:** See `Documentation/data_dictionary.md`
- **Cleaning Log:** See `Cleaned/LOGS`
- **Analysis Methods:** See `Calculations_Pivots/README.md`
- **Dashboard Guide:** See `Dashboard/README.md`

---

## 📞 Data Source Contact

**Organization:** Los Angeles Police Department

**Open Data Team:** data.lacity.org

**Technical Support:** For dataset inquiries, visit the LA Open Data Portal

---

## 📅 Dataset Version Control

| Version | Date Obtained | Records | Notes |
|---|---|---|---|
| v1.0 | Feb 11, 2026 | ~10,000 | Initial dataset for Gate 1 approval |
| Current | Feb 11, 2026 | 9,995 | Final subset for analysis (5 records removed during cleaning) |

---

## ✅ Validation Checklist

- [x] Dataset downloaded from official source
- [x] File integrity verified
- [x] Record count validated
- [x] Column structure documented
- [x] Source attribution complete
- [x] Usage rights confirmed
- [x] Original file preserved
- [x] Documentation updated

---

*This raw dataset is maintained in its original state as part of the Los Angeles Crime Analytics Capstone Project (Group 13, Section E). All analysis and transformations are performed on copies in the `Cleaned/` folder.*
