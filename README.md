# Financial Data Cleaning Case Study using Power BI & Power Query

## Project Overview

This project focuses on cleaning and preparing a messy financial transactions dataset using **Power BI** and **Power Query**. Rather than building a dashboard from unreliable data, the objective was to identify data quality issues, apply appropriate cleaning techniques, and evaluate whether the dataset was suitable for business analysis.

This case study reflects a real-world scenario where analysts spend a significant amount of time preparing data before any meaningful analysis can be performed.

---

## Business Problem

The provided financial transactions dataset contained numerous data quality issues that made it unsuitable for reliable reporting and decision-making. The goal was to improve the dataset by applying data cleaning techniques and assessing its readiness for analysis.

---

## Dataset

The dataset contains financial transaction records, including:

* Transaction details
* Product information
* Quantity
* Price
* Payment method
* Transaction type
* Customer information
* Other financial attributes

The dataset intentionally contained significant inconsistencies, making it an excellent case study for practicing data cleaning techniques.

---

## Data Quality Issues Identified

During the data profiling process, the following issues were identified:

* Inconsistent product names due to different spellings, missing characters, and mixed letter casing.
* Missing values across multiple columns.
* Prices stored as text with currency symbols (`$`), causing data type conversion errors.
* Negative and unrealistic values in quantity and price fields.
* Invalid and unknown transaction types.
* Inconsistent payment method values (e.g., Cash, cash, CASH, PayPal, paypal).
* Incorrect data types.
* Duplicate and inconsistent categorical values.
* Records containing logical inconsistencies, such as missing prices with available quantities.
* Poor overall data quality that affected business reporting.

---

## Data Cleaning Process

The following transformations were performed using Power Query:

* Applied **Trim** and **Clean** functions to remove unnecessary spaces and non-printable characters.
* Standardized text values using conditional columns and proper formatting.
* Corrected inconsistent product names.
* Standardized payment method values.
* Removed currency symbols from the Price column.
* Converted text fields into appropriate numeric data types.
* Identified and handled missing values.
* Created conditional columns to classify valid and invalid records.
* Reviewed invalid records for business relevance.
* Performed data profiling before and after cleaning.
* Improved overall dataset consistency and usability.

---

## Challenges Encountered

Although the dataset was successfully cleaned from a technical perspective, several business logic issues remained.

Examples included:

* Unrealistic transaction quantities.
* Missing prices for completed transactions.
* Invalid transaction records.
* Financial values that were not suitable for meaningful business analysis.

These issues highlighted an important lesson:

> A technically clean dataset is not always a business-ready dataset.

---

## Tools Used

* Power BI
* Power Query
* Data Profiling
* Conditional Columns
* Data Transformation
* Data Validation



---

## Key Learning

This project demonstrated the importance of data preparation in the analytics process. While Power Query can effectively clean and transform messy datasets, analysts must also validate whether the cleaned data is logically consistent and suitable for business reporting.

The project strengthened my practical skills in:

* Data Cleaning
* Data Profiling
* Power Query Transformations
* Data Validation
* Problem Solving
* Business Data Assessment

---

## Repository Contents

* Original dataset
* Cleaned dataset
* Power BI (.pbix) project
* Project screenshots
* Documentation

---

## Future Improvements

Possible future enhancements include:

* Applying additional business validation rules.
* Automating data quality checks.
* Integrating SQL-based data cleaning workflows.
* Building a financial dashboard using a business-ready dataset.

---

## Author

**Abdullah Ghauri**


