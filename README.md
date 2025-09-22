# Medical-Appointment-NoShow-DataCleaning\

This task focused on Data Cleaning and Preprocessing using the Medical Appointment No Shows dataset. The main objective was to identify and fix common issues such as missing values, duplicates, inconsistent formats, and incorrect data types to prepare a clean dataset for further analysis.

**Steps Performed:**

Removed Duplicates

Checked for duplicate rows and removed them to ensure unique records.

Handled Missing / Blank Values

Verified all columns for blanks and removed any unnecessary white spaces.

Confirmed that no null values remained.

Standardized Gender Column

Converted inconsistent values:

"M" → "Male"

"F" → "Female"

Converted Data Types

Ensured columns had correct formats:

Age → Integer

Dates (ScheduledDay, AppointmentDay) → DateTime format

Created Separate Columns for Date & Time

From ScheduledDay, extracted and separated:

Scheduled Date

Scheduled Time

Did the same for AppointmentDay where required.

Added a Derived Column for Validation

Created a new column to check whether the appointment date was correctly scheduled (by comparing ScheduledDay and AppointmentDay).

Cleaned Column Names

Renamed column headers to be more uniform (lowercase, no spaces).

**Final Output:**
A cleaned dataset with consistent, standardized, and properly formatted values.

Dataset is now ready for further exploratory analysis, visualization, or modeling.
A cleaned dataset with consistent, standardized, and properly formatted values.

Dataset is now ready for further exploratory analysis, visualization, or modeling.
