# Cleaned_Data_Hameedat_Olanrewaju

*Cleaned_Data_Hameedat_Olanrewaju.xlsx (3 sheets).*

*Tasks performed*

*Sheet 1: Raw Data*
- Removed blank cells (missing values)
- Removed duplicates
- Created a table, sorted data by year (smallest to largest)
- Conditional formatting:
    - Unique years (green)
    - Duplicate years (red)
    - Top 10% total sales (red)

*Sheet 2: Sorted&Filtered_Data*
- Copied dataset from Raw Data (Sheet 1)
- Filtered data: 1955-1960, sorted by year (smallest to largest)
- Conditional formatting:
    - Unique years (green)
    - Duplicate years (red)
    - Top 2% total sales (highlighted)

*Sheet 3: Cleaned Text Data*
- Converted text file to Excel
- Text functions applied:
    - Extracted "Employee Names" (CONCATENATE, LEFT, MID) to Column B From Column A
    - Extracted "Hire date, salary, dept, job title" from Column A to Column G (hidden) using RIGHT function 
    - Extracted "Hire date", "Salary" From Column G to Columns C, D (using Flash Fill)
    - Extracted "Dept", "Job title" From Column G to Columns E, F (using MID)
- Created a table
- Conditional formatting: Top 10 salaries highlighted
- NOTE COMMENT (H1): Columns A & G hidden for Organization (G has RIGHT function output)
