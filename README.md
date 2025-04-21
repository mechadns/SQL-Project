# 📊 Layoffs Data Cleaning Project

### This project is focused on cleaning and preparing layoffs data using SQL. The goal is to safely work with raw data by using a staging environment and eliminating duplicate entries before any analysis is performed.

## 📁 Project Structure
### layoffs: The original/raw data table

### layoffs_staging: A staging table created to prevent any modifications to the raw data during the cleaning process

## 📌 Notes
### The script uses ROW_NUMBER() to handle duplicates effectively.

### Staging ensures that the original data remains untouched.

### Manual inspection steps are included for transparency.

# #✅ Next Steps
### Further clean columns (e.g., standardize date formats, handle null values)

### Add indexing for performance

### Use the cleaned data for analysis or visualization
