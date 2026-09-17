# Pizza Sales Dashboard

An interactive Power BI dashboard for exploring pizza sales performance, customer ordering patterns, and product-level results.

## Contents

- `Pizza Sales Dashboard.pbix` — Power BI Desktop report containing the data model, measures, and dashboard visualizations.
- `pizza_sales.csv` — Source sales dataset used by the report.

## Dashboard overview

The dashboard can be used to analyze:

- Total revenue and order volume
- Pizza sales by category, size, and individual product
- Daily and monthly ordering trends
- Average order value and average pizzas per order
- Best-selling and underperforming pizzas
- Peak ordering periods and customer purchasing patterns

## Getting started

1. Clone or download this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open `Pizza Sales Dashboard.pbix`.
4. If Power BI prompts for a missing data source, point the source to `pizza_sales.csv` in the repository.
5. Refresh the report to load the latest CSV data.

## Data

The CSV file contains the underlying pizza order records used by the report. The report may include calculated measures and transformations built on top of this data.

When replacing the dataset, keep the expected columns and data types consistent so that the existing model and visuals continue to work correctly.

## Requirements

- Windows
- Power BI Desktop
- Access to the CSV file included in this repository

## Notes

The `.pbix` file is a binary Power BI project file and is best viewed or edited in Power BI Desktop. Changes made in Power BI should be saved back to the report file before committing them to the repository.

## License

No license has been specified for this repository. Unless a license is added, all rights are reserved by the repository owner.
