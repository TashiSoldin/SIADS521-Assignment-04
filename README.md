# Strava Exercise Dashboard

This repository contains a comprehensive data visualization dashboard built with Python to analyze and display fitness data from the Strava platform. The dashboard provides insights into exercise activities, including running and cycling sessions, through interactive visualizations.

## Overview

This project transforms raw Strava activity data into an intuitive, interactive dashboard. It offers both high-level summary statistics and detailed activity-specific visualizations to help users better understand their exercise habits and performance trends.

## Repository Contents

- `Strava_Dashboard.ipynb`: Jupyter notebook containing all the code for data processing and dashboard creation
- `strava.csv`: Dataset containing raw Strava activity data
- `dashboard_screenshots/`: Folder containing screenshots of the resulting dashboard views

## Dashboard Features

The dashboard consists of two main tabs:

### Summary Dashboard
- Activity overview cards showing total activities, distance, duration, and estimated calories burned
- Activity table with filtering capability by exercise type
- Monthly activity distribution chart
- Distance distribution boxplot comparing running and cycling activities
- Speed trends over time visualization

### Activity Details
- Interactive activity selector with filtering by type
- Route map visualization using GPS data
- Detailed activity metrics (distance, duration, speed, heart rate)
- Multi-metric time series plots with customizable variable selection

## Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/hvPlot**: Static and interactive visualizations
- **Folium**: Geospatial visualizations for activity routes
- **Panel**: Dashboard framework for layout and interactivity

## Getting Started

1. Clone this repository
2. Ensure you have all dependencies installed:
   ```
   pip install pandas numpy matplotlib hvplot folium panel
   ```
3. Open the Jupyter notebook:
   ```
   jupyter notebook Strava_Dashboard.ipynb
   ```
4. Run all cells to generate the dashboard

## Dashboard Screenshots

The `dashboard_screenshots/` directory contains images showcasing different views of the dashboard:
- Summary statistics and activity overview
- Activity table with filtering
- Visualization panels including monthly activity chart and distance comparisons
- Activity map view displaying GPS routes
- Time series plots of various metrics during individual activities

## Data Description

The `strava.csv` dataset contains exercise data including:
- Timestamps of activities
- GPS coordinates
- Heart rate data
- Speed and cadence metrics
- Distance and duration information
- Activity type classification (running/cycling)

## Notes

This dashboard was created as part of a data visualization project focusing on effective presentation of time-series fitness data. The visualizations adhere to established principles of effective data presentation, including attention to color, layout, and interactivity to ensure the insights are accessible and meaningful.
