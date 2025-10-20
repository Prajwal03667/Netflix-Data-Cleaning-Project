# Netflix Data Cleaning Project

## Overview
This project demonstrates data cleaning on the Netflix dataset (`netflix_titles.csv`).  
The goal is to remove duplicates, fix missing values, and standardize the data.

## Before Cleaning
- Raw data contains missing values in `director` and `cast` columns.  
- Duplicate rows exist.  
- `date_added` column has inconsistent formats.  

## After Cleaning
- Duplicates removed.  
- Missing values filled with default placeholders (`Unknown` or `Not Specified`).  
- `date_added` standardized to datetime format.  

## Files
- `netflix_titles.csv` → Original dataset  
- `netflix_titles_cleaned.csv` → Cleaned dataset  
- `before.png` → Screenshot of raw data  
- `after.png` → Screenshot of cleaned data  
- `data_cleaning.py` → Python script for cleaning

## How to Run
1. Install Python and Pandas library:
```bash
pip install pandas
