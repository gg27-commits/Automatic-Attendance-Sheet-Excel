# Automatic-Attendance-Sheet-Excel
Automated Employee Attendance Management System developed in Microsoft Excel using formulas, conditional formatting, and monthly attendance reporting.


## Overview

This project is an automated Employee Attendance Management System developed in Microsoft Excel.

The workbook automatically tracks employee attendance and generates monthly attendance summaries using Excel formulas and conditional formatting.

## Features

- Daily Attendance Tracking
- Employee-wise Attendance Monitoring
- Automatic Present Count
- Automatic Absent Count
- Holiday Tracking
- Weekday Identification
- Monthly Attendance Summary
- Conditional Formatting for Easy Visualization

## Dataset Structure

### Employee Information
- Employee ID
- Employee Name

### Attendance Data
- Daily Attendance Status
  - P = Present
  - A = Absent
  - H = Holiday

### Summary Section
- Total Days
- Present Days
- Holidays
- Weekdays
- Absent Days

## Excel Functions Used

### COUNTIF()

Used to count:

- Present Days
- Absent Days
- Holidays

Example:

```excel
=COUNTIF(C5:AF5,"P")
```

### IF()

Used for attendance logic.

Example:

```excel
=IF(C5="P",1,0)
```

### TEXT()

Used to display weekday names.

Example:

```excel
=TEXT(C$3,"ddd")
```

### SUM()

Used for total calculations.

Example:

```excel
=SUM(A1:A30)
```

## Conditional Formatting

Applied to:

- Present (P)
- Absent (A)
- Holiday (H)

to improve readability and data analysis.

## Project Output

The system automatically generates attendance summaries for each employee at the end of the month.

    
## Benefits

- Reduces manual attendance calculations
- Improves accuracy
- Saves time
- Easy monthly reporting
- User-friendly interface

