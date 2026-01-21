# COVID-19 County Report Program

This project analyzes COVID-19 case data at the U.S. county level using publicly available datasets from Johns Hopkins University.  
It generates statistical summaries, time-series visualizations, and an interactive choropleth map based on user-selected counties.

## Project Overview
The program allows users to:
- Select a U.S. county (and state if needed)
- View COVID-19 case trends over time
- Calculate average and total new cases by year (2020–2022)
- Visualize cumulative cases using charts and geospatial maps

## Data Sources
- Johns Hopkins University COVID-19 Time Series Data
- U.S. County Geometry Shapefiles (GeoJSON)

## Tools & Libraries
- Python
- pandas
- geopandas
- matplotlib
- folium
- contextily
- mapclassify

## Key Features
- Data cleaning and reshaping using pandas
- Time-series analysis of COVID-19 cases
- County-level summary statistics
- Line chart visualization of case trends
- Interactive choropleth map by county

## How to Run
1. Open the Jupyter Notebook (`.ipynb`)
2. Run all cells
3. Enter a county name when prompted
4. View statistical output, charts, and maps

## Output
- Console-based COVID-19 summary report
- Line chart showing cumulative cases
- Interactive county-level choropleth map

