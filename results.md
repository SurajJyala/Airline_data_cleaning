# Airline Data Cleaning and Quality Assessment

## Project Overview
This project uses Python, Pandas, and NumPy to inspect, clean, and prepare airline data for analysis.

## Dataset Summary
- **Total Records:** 103,000
- **Total Columns:** 13
- **Columns with Missing Values:** 5
- **Total Missing Cells:** 17,471

## Data Quality Assessment

| Column | Missing Values | Missing Percentage |
|---|---:|---:|
| Ticket_Price | 5,136 | 4.99% |
| Duration_hours | 4,116 | 4.00% |
| Fuel_Cost | 3,081 | 2.99% |
| Distance_km | 3,077 | 2.99% |
| Delay_minutes | 2,061 | 2.00% |

The remaining eight columns contain no missing values.

## Tools and Technologies
- Python
- Pandas
- NumPy
- VS CODE

## Key Findings
- Identified missing values across five numerical columns.
- Found that Ticket_Price has the highest number of missing values.
- Inspected column data types and dataset structure.
- Identified data quality issues requiring further preprocessing.

## Project Files
- `pandas.ipynb` — Notebook containing the analysis code.
- `README.md` — Project introduction and overview.
- `results.md` — Dataset summary and data quality findings.

## Next Steps
Handle missing values using appropriate methods, validate duplicate records, standardize data types, and verify the final cleaned dataset.

## Author
Suraj Singh
