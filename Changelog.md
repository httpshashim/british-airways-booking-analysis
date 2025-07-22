##Project: British Airways Booking Data Analysis
##Purpose: Improve user experience and conversion for a travel booking platform using airline booking data.

[v1.0.0] - 2025-07-22
🎯 Initial Project Planning
Defined project goal: Improve UX & conversion rates for travel booking platforms using British Airways booking data

Selected Kaggle dataset: Airline Passengers Booking Data

Outlined business-relevant KPIs:

Booking completion

Funnel drop-off

Channel usage

Booking patterns by day and country

[v1.1.0] - 2025-07-22
🧹 Data Cleaning & Preparation (Python / Pandas)
Dropped irrelevant columns (AB Test, User ID, Gender)

Renamed columns for clarity (e.g., Booking Completed → Booking_Complete)

Cleaned categorical fields (standardized case and formatting)

Handled missing values in key columns (e.g., dropped or imputed rows with nulls in Funnel Stage, Sales Channel)

Saved cleaned data to final_airline_booking_data.csv

[v1.2.0] - 2025-07-22
📊 Exploratory Data Analysis (EDA)
Conducted analysis on:

Funnel conversion rates

Trip type distribution (Round, One-Way, Circle)

Sales channel share (Internet vs Mobile)

Booking day patterns

Booking origin (Top 10 countries)

[v1.3.0] - 2025-07-22
📈 Tableau Dashboard Creation
Imported cleaned .csv into Tableau Public

Built individual visualizations:

Trip Type vs Passenger Count (bar chart)

Sales Channel vs Passenger Count (bar chart)

Funnel Stage vs Drop-off (bar chart)

Bookings by Day of Week (heatmap)

Top Countries by Booking Origin (horizontal bar chart)

Customized layout, legends, and colors for clarity

Exported final dashboard image: tableau_dashboard.png

[v1.4.0] - 2025-07-22
📦 Project Packaging for GitHub
Created project directory structure:

kotlin
Copy
Edit
├── data/
│   └── final_airline_booking_data.csv
├── notebooks/
│   └── booking_analysis.ipynb
├── dashboard/
│   └── tableau_dashboard.png
├── README.md
└── CHANGELOG.md
Wrote detailed README.md with:

Project summary

Tools used

Dashboard insights

Structure overview

[v1.5.0] - Upcoming
🚀 Future Enhancements (Optional)
Add Tableau Public dashboard link

Include interactive Tableau embed in GitHub Pages

Build predictive booking model (optional stretch goal)

Integrate time-based trend analysis

🔖 Versioning Note
This project uses Semantic Versioning — MAJOR.MINOR.PATCH:

MAJOR for big changes (new analysis, new data source)

MINOR for new visualizations, insights, or layout changes

PATCH for bug fixes or content polishing
