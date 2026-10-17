# google-sheets-sales-tracker
A Google Sheets sales tracker with daily, weekly, and monthly sales summaries, data validation, and sample data verification
# Google Sheets Sales Tracker

A lightweight sales tracker built in Google Sheets. It summarizes sales by day, week, and month from raw sales entries.

## Features

- Separate raw data and summary tabs
- Daily, weekly, and monthly sales totals using `SUMIFS`
- Date and quantity validation
- Product dropdown sourced from a separate product list
- Protected summary formula cells

## Google Sheets Setup

1. Import the dataset into Google Sheets.
2. Keep the original data in the `Raw data` tab.
3. Use the `Summary` tab to view daily, weekly, and monthly totals.
4. Add new sales rows to `Raw data`; update the summary dates as needed.

## Verification

Sample sales totals were checked against the raw data manually.
