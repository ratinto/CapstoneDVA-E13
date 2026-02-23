# Cleaned Dataset

## About This Folder

This folder contains the cleaned and processed version of the raw dataset, ready for analysis.

## Files

- `New Cleaned Dataset` - Cleaned dataset
- `LOGS` - Detailed log of all cleaning operations performed

## Cleaning Overview

### Data Quality Improvements

| Aspect | Before | After | Improvement |
|--------|--------|-------|-------------|
| Total Records | ~10,000 | 9,995 | 5 rows removed |
| Missing Values | 40% | 0% | 100% resolved |
| Duplicates | 0 | 0 | None found |
| Invalid Entries | 0 | 0 | None found |

### Major Cleaning Steps

1. **Renamed all columns** to meaningful, human-readable names (Manual Renaming)
2. **Removed rows with empty `dr_number` values** to ensure record integrity
3. **Formatted date columns** (`Date_Occured`, `Date_Reported`) and derived new `Year` and `Month` columns using `=YEAR()` / `=MONTH()`
4. **Converted numeric time in `Time_Occured`** to proper HH:MM time format using `=TIME(LEFT(...), RIGHT(...), 0)`
5. **Standardized `Reporting_District_Number`** to proper text format using `=TEXT()`
6. **Replaced numeric codes in `Crime_Type`** (1 → "Serious", 2 → "Less Serious") using `=IF()`
7. **Converted `Crime_Code_Description`** to proper case using `=PROPER()`
8. **Replaced missing values in `Mocodes`** with "NA"
9. **Replaced negative and zero values in `Victim_Age`** with "NA"
10. **Expanded `Victim_Gender` codes** to full names (M → Male, F → Female, X → NA) using `=IFERROR(IFS(...))`
11. **Decoded `Victim_Ethnicity` single-letter codes** to full ethnicity names (e.g., H → Hispanic, W → White) using `=SWITCH()`
12. **Formatted `Premise_Description`** to proper case and handled errors with `=IFERROR(PROPER(...))`
13. **Replaced blanks in `Weapon_Used_Code`** with "NA"
14. **Replaced blanks in `Weapon_Description`** with "NA" and applied proper case formatting
15. **Decoded `Case_Status` codes** to meaningful labels (e.g., AA → Adult Arrest, IC → Investigation Continued) using `=SWITCH()`
16. **Handled missing values in Crime Code columns** and `Cross_Street` by replacing blanks with "NA"
17. **Created new derived column `Hourly_Crime_Reported`** using `=HOUR(Time_Occured)`

## Google Sheets Link

**Cleaned Data Sheet:** [https://docs.google.com/spreadsheets/d/16M1RjcCEKq5YiyMkyH-rGxttXs5jKLU536N0zey8K9Y/edit?gid=97077233#gid=97077233]

## Validation

- [ ] All cleaning steps documented
- [ ] Data quality metrics calculated
- [ ] Cleaned data verified
- [ ] Ready for analysis
