# Excel Data Cleaning Project

## Project Overview

This project demonstrates the process of cleaning, organizing, validating, and documenting a messy sales dataset using Microsoft Excel.

The goal was to improve data quality and prepare the dataset for accurate analysis and reporting while documenting data-quality issues that required further review.

## Project Objective

* Clean and organize a messy sales dataset
* Standardize inconsistent data formats
* Identify duplicates and data-quality issues
* Handle missing and invalid values
* Validate data for accuracy and consistency
* Document issues that could not be reliably corrected
* Prepare a clean dataset for analysis and reporting

## Data Cleaning & Validation

The following tasks were performed:

* Removed completely blank rows
* Identified duplicate and potentially duplicate records
* Removed extra spaces and standardized text values
* Standardized name formatting
* Reviewed and cleaned email formatting
* Standardized phone number formatting
* Reviewed and standardized City and Country values
* Identified inconsistent and invalid date values
* Used **Power Query** to convert and standardize the `Order_Date` field
* Left dates blank when the correct value could not be reliably determined
* Reviewed and standardized Product names
* Standardized Category values
* Converted Quantity, Unit_Price, and Total_Sales to numeric formats
* Investigated unusual or negative Quantity values
* Validated `Total_Sales` against `Quantity × Unit_Price`
* Reviewed and standardized `Order_ID` formatting
* Identified remaining missing values
* Documented unresolved issues in the **Review Notes** column

## Workbook Structure

The project is provided as one Excel workbook:

**`Excel_Data_Cleaning_Project.xlsx`**

The workbook contains three worksheets:

### 1. Original Messy Data

Contains the original messy dataset before cleaning. This worksheet was preserved as the starting point for comparison.

### 2. Cleaned Data

Contains the cleaned and standardized dataset.

This worksheet also includes a **Review Notes** column for documenting data-quality issues that require additional verification rather than making unsupported changes.

### 3. Data Cleaning Checklist

Documents the cleaning, validation, and quality-checking steps performed during the project.

## Tools & Techniques

* Microsoft Excel
* Power Query
* Excel Tables
* Excel Functions
* Sorting and Filtering
* Data Validation
* Data Cleaning
* Data Standardization
* Data Quality Checks

## Data Quality Approach

The cleaning process focused on accuracy and consistency rather than simply changing values to make the dataset look uniform.

When the correct value could not be determined with confidence, the issue was documented in the **Review Notes** column for further investigation.

## Project Outcome

The final dataset is cleaner, more consistent, and better organized for analysis and reporting. The project also demonstrates a structured approach to identifying, validating, and documenting data-quality issues.

## Skills Demonstrated

**Excel Data Cleaning | Power Query | Data Validation | Data Standardization | Data Quality Checks | Duplicate Identification | Missing Data Handling | Data Preparation**
