# Tamil Nadu Job Market Analytics Dashboard

A live data pipeline that fetches job listings across 7 districts in Tamil Nadu using the Adzuna API, processes the data in Python, and visualizes insights in an interactive Power BI dashboard.

## Features
- Automated fetching of live job data from the Adzuna API
- Data cleaning: deduplication and null value handling
- Export to CSV for downstream analysis
- Power BI dashboard with 9 visuals: district-wise distribution, top hiring companies, salary disclosure trends
- District and company-level slicers for interactive filtering
- Repeatable refresh workflow for updated job market data

## Tech Stack
Python, Pandas, Requests, Power BI

## Setup
1. Get a free Adzuna API key at developer.adzuna.com
2. Replace `YOUR_ADZUNA_APP_ID` and `YOUR_ADZUNA_API_KEY` in the script
3. Run the script to fetch live job data
4. Open the generated CSV in Power BI to explore the dashboard

## Author
Dravidarselvi T
