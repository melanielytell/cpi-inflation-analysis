# U.S. CPI and Inflation Trends (1982–2026)

## Project Overview

This project analyzes changes in the U.S. Consumer Price Index (CPI) over time using Microsoft Excel. The goal is to explore long-term price trends and examine month-to-month changes in the CPI to better understand inflation patterns.

## Research Questions

* How has the Consumer Price Index changed over time?
* How much does the CPI change from month to month?
* During which periods were monthly CPI increases or decreases particularly noticeable?
* What can the trends reveal about changes in the overall price level?

## Data Source

The data comes from the U.S. Bureau of Labor Statistics (BLS), which publishes Consumer Price Index data.

* **Source:** [U.S. Bureau of Labor Statistics](https://www.bls.gov/cpi/data.htm)
* **Measure:** Consumer Price Index for All Urban Consumers (CPI-U)
* **Base period:** 1982–1984 = 100
* **Frequency:** Monthly
* **Period analyzed:** 1982 through the latest available observation included in the dataset

## Tools Used

* Microsoft Excel
* Excel formulas
* Line charts and time-series visualization

## Methodology

1. Organized monthly CPI observations chronologically.
2. Calculated month-to-month changes in the CPI index.
3. Calculated monthly inflation rates as percentage changes from the previous month's CPI.
4. Examined trends and fluctuations using line charts.
5. Reviewed missing observations and distinguished unavailable data from genuine zero changes.

### Monthly CPI Change

The change in CPI index points is calculated as:

`Current Month CPI - Previous Month CPI`

### Monthly Inflation Rate

The monthly inflation rate is calculated as:

`((Current Month CPI - Previous Month CPI) / Previous Month CPI) × 100`

A positive rate indicates an increase in the CPI, while a negative rate indicates a decrease.

## Visualizations

The project includes visualizations of:

* CPI index trends over time
* Month-to-month percentage changes in the CPI

See the `visuals/` folder for exported charts.

## Key Findings

See [`findings.md`](findings.md) for the main observations and economic interpretations from the analysis.

## Repository Contents

* `CPI_Inflation_Analysis.xlsx` — Excel workbook containing the data, calculations, and charts
* `findings.md` — Summary of the analysis and findings
* `visuals/` — Exported chart images
* `data/README.md` — Data source and data-handling documentation
* `data/cpi_data.csv` — Optional cleaned dataset, if included

## Limitations

The CPI measures changes in the average price level of a basket of consumer goods and services. It does not measure every household's personal cost of living.

Monthly changes can fluctuate, so a single month's rate should not be interpreted as a complete picture of the inflation trend. Missing observations are not treated as zero, and monthly inflation rates cannot be calculated when the required CPI observations are unavailable.

## Purpose

This project demonstrates the application of spreadsheet skills to an economic question through data organization, formula-based calculations, time-series visualization, and interpretation of inflation trends.
