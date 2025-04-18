# Forcast-Sales-Data-for-2014-2016-Sales-Data

## Overview
This project features an interactive Excel dashboard designed to forecast short-term sales (2-3 weeks) using a Brazilian company’s sales data from 2014-2016. It compares six forecasting methods—Last Period Demand, Simple Average, Four-Period Moving Average, Exponential Smoothing, Regression Analysis, and Holt-Winters—allowing users to select methods, years, and weeks via dropdowns, and analyze error metrics (Forecast Error, Absolute FE, Mean Absolute Deviation, Mean Error) to optimize supply chain decision-making.

## Features
- **Dynamic Dashboard**: Dropdowns for selecting forecasting method, year, and week to compare actual vs. forecasted sales and error metrics.
- **Forecasting Methods**: Implements six methods to predict sales, including Holt-Winters and Regression Analysis.
- **Error Analysis**: Calculates FE, Absolute FE, MAD, and ME to evaluate forecast accuracy.
- **Excel Functions**: Utilizes XLOOKUP, CHOOSE, MATCH, and INDEX for dynamic data retrieval and calculations.

## Setup
1. **Prerequisites**: Microsoft Excel (2016 or later recommended) to support XLOOKUP and dashboard features.
2. **Download**: Clone or download the repository:
3. **Open the File**: Open `Retail Sales for 2014-2016 Dashboard.xlsx` in Excel. Ensure macros are enabled if prompted (no macros used in this version, but enable for compatibility).
4. **Data**: The Excel file includes a sanitized dataset (2014-2016 sales) with a hidden table containing year, week, actual, forecast values, and error metrics.

## Usage
1. **Select Options**:
- Use the dropdown in cell E3 to choose a forecasting method (e.g., Holt-Winters).
- Select the year and week from adjacent dropdowns to filter data.
2. **View Results**:
- The dashboard updates to display actual vs. forecasted sales for the selected period.
- Error metrics (FE, Absolute FE, MAD, ME) are shown for the chosen method.
3. **Analyze**:
- Review visualizations (charts) and error metrics to identify the best-performing forecasting method for supply chain planning.

## File Structure
- `Retail Sales for 2014-2016 Dashboard.xlsx`: Main Excel file with the dashboard, data, and calculations.
- `README.md`: This file.

## Limitations
- **Excel Dependency**: Requires Microsoft Excel; functionality may vary in other spreadsheet software (e.g., Google Sheets).
- **Sanitized Data**: Original dataset is anonymized to protect privacy, limiting direct applicability to other datasets.
- **Static Methods**: Forecasting methods are pre-implemented; users cannot add new methods without modifying formulas.
