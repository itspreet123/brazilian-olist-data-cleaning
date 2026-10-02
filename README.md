# brazilian-olist-data-cleaning
Data cleaning and preprocessing of the Brazilian Olist e-commerce dataset.

Brazilian Olist E-Commerce Dataset – Data Cleaning
Project Overview

This project contains the cleaned version of the Brazilian Olist E-Commerce Dataset.

The dataset contains information about orders, customers, products, sellers, payments, reviews, and order delivery details from the Brazilian e-commerce platform Olist.

The main objective of this task was to clean and prepare the raw data for further analysis and reporting.

Dataset

Source: Brazilian E-Commerce Public Dataset by Olist
Domain: E-Commerce / Sales Analytics
Country: Brazil

The dataset consists of multiple related tables, including:

Orders
Customers
Order Items
Products
Sellers
Payments
Reviews
Geolocation
Product Category Translation
Data Cleaning Performed

The following cleaning steps were performed:

1. Removed Duplicate Records
Checked the datasets for duplicate rows.
Removed duplicate records where applicable.
Ensured that key identifiers remained unique where required.
2. Handled Missing Values
Identified columns containing missing/null values.
Evaluated missing values based on the meaning of each column.
Removed or handled missing records where appropriate.
Kept valid missing values where they represented unavailable information rather than errors.
3. Corrected Data Types
Converted date/time columns into appropriate date/time formats.
Checked numerical columns and converted them into appropriate numeric data types.
Ensured ID and categorical columns were stored consistently.
4. Standardized Text Data
Cleaned unnecessary spaces and inconsistent text formatting.
Standardized categorical values where required.
Ensured consistent formatting across related fields.
5. Checked Data Quality
Checked for invalid or inconsistent values.
Reviewed primary keys and related identifiers.
Checked relationships between tables to ensure the cleaned data remained suitable for analysis.
6. Prepared Final Dataset
Saved the cleaned datasets as CSV files.
Organized the files into separate tables.
The cleaned data is ready for SQL analysis, Power BI dashboards, and further business analysis.
Output

The cleaned datasets are available in the data folder of this repository.

The cleaned data can be used for:

Sales analysis
Customer analysis
Product analysis
Order and delivery analysis
Seller performance analysis
Review analysis
Power BI dashboard development
SQL analysis
Tools Used
Microsoft Excel
GitHub
Data Quality Checks

Before finalizing the cleaned datasets, the following checks were performed:

Duplicate records
Missing values
Data types
Invalid values
Inconsistent text
Unique identifiers
Table relationships
Conclusion

The raw Olist dataset was cleaned and structured to improve data quality and make it suitable for further analysis. The cleaned datasets provide a consistent foundation for SQL queries, business analysis, and visualization.

Author: Preeti
Project: Data Cleaning Task
