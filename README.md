# Data_analyst_intern_task1
Task 1 - Data Cleaning and Preprocessing (Excel)

Dataset: Medical Appointment No Shows

--Cleaning Steps:--
- No missing values found in any column.
- Removed 10 duplicate rows using Excel's Remove Duplicates.
- Standardized text values in gender, no_show, and neighbourhood columns.
- Reformatted scheduled_day and appointment_day to DD-MM-YYYY format.
- Renamed all column headers to lowercase with underscores for consistency.
- Verified and corrected data types:
  - age as number
  - scheduled_day, appointment_day as date
  - Text fields in proper case

--Tools Used:--
- Microsoft Excel 2016+
- Filter, Find & Replace, Formulas (=PROPER(), =ISBLANK())
- Format Cells, Remove Duplicates

--Output:--
- Cleaned Excel File: cleaned_medical_appointments.xlsx
- Ready for analysis or modeling.
