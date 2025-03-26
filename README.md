# CleaningNotebook - Data Cleaning Guide

## Overview

This Jupyter Notebook is designed for cleaning manually entered trip data. It applies various preprocessing techniques to ensure data consistency, correctness, and usability.

## Data Description

The dataset contains manually recorded trip data, which may include inconsistencies such as:

- Misspellings or incorrect formats
- Irregular date/time entries
- Duplicates or missing values
- Non-standardized text inputs

## Libraries Used

The following Python libraries are required to run the notebook:

- `pandas` - For data manipulation and preprocessing
- `numpy` - For numerical operations and handling missing values
- `re` (Regular Expressions) - For pattern matching and text cleaning

## Features

- Handling missing and duplicate values
- Standardizing formats (e.g., date/time, text fields)
- Cleaning and transforming manually entered data
- Applying regex-based cleaning for textual inconsistencies

## Usage Instructions

1. Install the required libraries if not already installed:
   ```bash
   pip install pandas numpy
   ```
2. Open the notebook using Jupyter:
   ```bash
   jupyter notebook CleaningNotebook.ipynb
   ```
3. Run the notebook cells sequentially to clean the dataset.
4. Review and export the cleaned data for further processing.

## Notes

- Ensure that the dataset is correctly formatted before running the notebook.
- Modify regex patterns as needed based on specific data inconsistencies.
- Validate the cleaned data before proceeding with any analysis.

## Author

Fares Ahmed Albadrawi

