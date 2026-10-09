# Data Documentation

## Source

The Consumer Price Index data used in this project comes from the U.S. Bureau of Labor Statistics (BLS).

* **Dataset:** Consumer Price Index for All Urban Consumers (CPI-U)
* **Source website:** https://www.bls.gov/cpi/data.htm
* **Frequency:** Monthly
* **Base period:** 1982–1984 = 100

## Data Description

The dataset contains monthly CPI observations used to examine changes in the U.S. consumer price level over time.

The analysis uses the CPI index to calculate month-to-month index changes and monthly inflation rates.

## Data Preparation

The following preparation steps were performed in Excel:

1. Organized observations by month and year.
2. Reviewed missing CPI observations.
3. Calculated monthly changes using consecutive CPI observations.
4. Calculated monthly inflation rates using the percentage change from the previous month.

## Missing Data

Missing CPI observations are left blank rather than replaced with zero. Monthly inflation rates are not calculated when the current or previous month's CPI observation is unavailable.

The first observation in the analysis period does not have a monthly inflation rate unless the preceding month's CPI is also available.

## Files

* `cpi_data.csv` — Optional cleaned dataset used in the analysis, if included in this folder.

The primary workbook containing the analysis and calculations is stored in the repository's root directory.
