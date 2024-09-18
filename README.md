# data-cleaning-using-SQL
This project focuses on cleaning and transforming a real-world dataset from the Nashville housing market to prepare it for further analysis. The primary objective is to ensure data consistency, handle missing values, and standardize various fields to make the dataset suitable for use in reporting and analytical tasks.

Project Overview
Dataset: Nashville Housing Data
Technologies: SQL (Microsoft SQL Server)
Key Data Cleaning Steps
Standardizing Date Formats:

Converted inconsistent date formats in the SaleDate column to a standardized Date type using the CONVERT function.
Created a new SaleDateConverted column to store the cleaned dates.
Handling Missing Property Addresses:

Identified records with missing PropertyAddress values and populated them by cross-referencing available data using ParcelID.
Address Standardization:

Standardized address formats for consistency across the dataset.
Removing Duplicates:

Identified and removed duplicate records based on the ParcelID to ensure data integrity.
Handling Null Values:

Replaced or updated null values in various fields, especially in property-related columns.
Populating New Columns:

Created additional columns as needed for analysis, such as converted date fields and clean property address fields.
Project Structure
The SQL file includes all the scripts used to clean and transform the data, ensuring that each step is clearly commented and easy to follow.
