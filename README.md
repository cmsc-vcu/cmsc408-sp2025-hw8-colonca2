# cmsc408-sp2025-hw8

## Homework 8 - World Bank Indicator Analysis

This project is part of CMSC 408 at VCU and focuses on analyzing global development data using SQL. The assignment utilizes the World Bank's World Development Indicators (WDI) database, which includes statistics on income groups, regions, and other country-level metrics.

### 📊 Project Objective

The goal of this assignment is to:
- Explore and clean large-scale international development data

- Practice SQL skills for aggregation, filtering, joins, and subqueries

- Create region-income summaries and pivot tables

- Calculate global and group-level statistics, including percentages

### 📁 Repository Contents

- `report.qmd`: The Quarto document containing all SQL code, results, and narrative explanation

- `README.md`: This file — a summary of the project

- `.env`: Stores credentials to connect to the hosted PostgreSQL database (**not included in this repo** for security reasons)

- No additional files are required for submission

### 🧠 Skills Demonstrated

- SQL querying and filtering (`SELECT`, `WHERE`, `LIMIT`)

- Aggregation and grouping (`COUNT`, `GROUP BY`)

- Table creation and filtering (`CREATE TABLE AS SELECT`)

- Conditional logic with `CASE` statements

- Pivot-style summaries using aggregation logic

- Working with missing values (`NULL`)

- Cross joins and set logic (`LEFT JOIN`, `CROSS JOIN`)

### 📝 Notes

- The cleaned working table `wdi_country` was created by filtering out aggregates and non-country entries.

- All queries were written directly in Quarto using Python code chunks and executed against the provided database.

### 🔄 Submission Instructions

- The `report.qmd` was rendered to HTML and submitted to Canvas.

- The GitHub repo (including this README) was submitted to Gradescope for autograding.




