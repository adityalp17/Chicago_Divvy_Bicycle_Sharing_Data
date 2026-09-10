# Chicago Divvy Bike Share Analysis — Power BI

An interactive Power BI dashboard analyzing ride patterns, station usage, rider demographics, and weather impact for Chicago's Divvy bike-share program.

**Capstone Project 2**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## Overview

This project explores Divvy trip data to answer questions like: When do people ride the most? Which stations are busiest? Who's riding — members or casual users, men or women? And how much does weather affect ridership?

The report is built as a 3-page Power BI dashboard:

| Page | Focus | Key visuals |
|------|-------|-------------|
| **1. Overview** | High-level KPIs and ride volume | Total trips, station count, avg. trip duration, total trip duration (cards) · Trips by hour & day (bar) · Trips by hour (area) · Slicers for filtering |
| **2. Stations & Riders** | Where rides start and who's riding | Top 10 stations by trips (bar) · Trips by hour (bar) · Trip start locations (map) · User type split (pie) · Gender split (donut) |
| **3. Weather Impact** | How conditions affect ridership | Trips vs. average temperature by day (line) · Trips by weather event (column) · Trip duration vs. temperature (scatter) |

## Dataset

The underlying data is Chicago's Divvy bike-share trip data, merged with daily weather data (temperature and weather events), at the individual trip level. Key fields include trip ID, start/end station, trip duration, user type (member/casual), gender, and weather conditions.

> 📁 The raw CSV(s) used to build this report should be placed in the `data/` folder — see [`data/README.md`](data/README.md).

## Tools & Skills

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures (total trips, average trip duration, etc.)
- Data visualization design (KPI cards, geo maps, time-series, distribution charts)

## Repository Structure

```
Chicago-Divvy-Bikeshare-PowerBI/
├── README.md                  # This file
├── LICENSE
├── .gitignore
├── report/
│   └── Chicago_Divvy.pbix     # Power BI report file
├── data/
│   ├── README.md              # Notes on the dataset / where to source it
│   └── (your .csv file(s) go here)
├── screenshots/               # Dashboard screenshots for quick preview
│   ├── page1_overview.png
│   ├── page2_stations_riders.png
│   └── page3_weather_impact.png
└── docs/
    └── data_dictionary.md     # Field-level description of the dataset
```

## How to View This Project

1. **Screenshots** — the quickest way to see the dashboard; check the `screenshots/` folder.
2. **Full interactive report** — clone this repo and open `report/Chicago_Divvy.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download, Windows only).

```bash
git clone https://github.com/<your-username>/Chicago-Divvy-Bikeshare-PowerBI.git
```

## Key Insights

> ✏️ *Replace this section with the actual takeaways from your analysis* for example:
- Ridership peaks during the evening commute (5–6 PM) on weekdays and midday on weekends.
- The top 10 stations account for a disproportionate share of total trips, concentrated around downtown/lakefront areas.
- Members take shorter, more frequent trips than casual riders, who tend to ride longer on weekends.
- Ridership drops sharply below a certain temperature threshold, and clear-weather days see the highest trip volume.

## Author

**Aditya Sunil Patil**
adityapatillp@gmail.com

---

*This project was completed as part of a data analytics capstone to demonstrate skills in data modeling, DAX, and dashboard design using Power BI.*
