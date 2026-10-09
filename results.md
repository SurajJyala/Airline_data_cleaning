# Airline Data Cleaning Using Python and Pandas

## 1. Project Overview

This project focuses on cleaning and preparing an airline dataset containing 103,000 records and 13 columns using Python, Pandas, and NumPy.

The objective was to improve data quality by handling missing values, removing duplicate records, and preparing the dataset for further analysis.

## 2. Dataset Description

The dataset contains flight-related information, including:

- Flight number and airline
- Aircraft type
- Origin and destination
- Flight date
- Flight distance and duration
- Ticket price and fuel cost
- Weather conditions
- Flight delays
- Passenger count

**Original dataset size:** 103,000 rows × 13 columns

## 3. Initial Data Quality Assessment

The initial inspection identified missing values in five numerical columns.

| Column | Missing Values | Missing Percentage |
|---|---:|---:|
| Ticket_Price | 5,136 | 4.99% |
| Duration_hours | 4,116 | 4.00% |
| Fuel_Cost | 3,081 | 2.99% |
| Distance_km | 3,077 | 2.99% |
| Delay_minutes | 2,061 | 2.00% |
| **Total** | **17,471** | **1.34% of all cells** |

The dataset contained 1,339,000 total cells before cleaning.

## 4. Data Cleaning Process

The following steps were performed:

1. Inspected the dataset structure, columns, and data types.
2. Identified missing values and examined their distribution.
3. Filled missing values in the affected columns using appropriate imputation methods.
4. Identified and removed duplicate records.
5. Prepared the cleaned dataset for subsequent analysis.
6. Exported the cleaned dataset to CSV format.

## 5. Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV

## 6. Project Deliverables

- **pandas.ipynb:** Python notebook containing the data cleaning and analysis workflow.
- **results.md:** Dataset overview, initial data quality findings, and cleaning methodology.
- **Cleaned CSV:** Exported dataset prepared for further analysis.

## 7. Final Outcome

The project transformed the original airline dataset into a cleaned, structured dataset by addressing missing values and removing duplicate records.

The exported CSV can be used for further exploratory data analysis, reporting, and visualization.

## 8. Future Improvements

- Validate the final dataset for remaining missing values and duplicates.
- Compare record counts before and after cleaning.
- Perform exploratory data analysis on airline performance, routes, ticket prices, and flight delays.

## Author

Suraj Singh

**Skills Demonstrated:** Python, Pandas, NumPy, Data Cleaning, Missing Value Imputation, Duplicate Removal, CSV Export.
