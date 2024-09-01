
# COVID-19 Dashboard with SQL Exploration

## Project Overview

This project presents a comprehensive COVID-19 Dashboard created using Tableau. The dashboard provides an interactive visualization of global COVID-19 data, showcasing key metrics such as total cases, deaths, and vaccine doses administered across various countries and regions. The dashboard also includes trend graphs highlighting cases, deaths, and vaccinations over time, broken down by continent.

[COVID-19-Dashboard.png](https://postimg.cc/hfSzs6NW)

## Features

- **Global Map Visualization:** Displays the distribution of COVID-19 cases and deaths across the world, with color-coded regions indicating the severity.
- **Key Metrics:** 
  - **Total Cases:** Aggregated count of confirmed COVID-19 cases globally.
  - **Total Deaths:** Total number of deaths attributed to COVID-19 worldwide.
  - **Total Vaccine Doses Administered:** Sum of all vaccine doses administered globally.
- **Country/Region Breakdown:** Lists COVID-19 statistics by country/region, including total cases and deaths.
- **Trend Graphs:**
  - **Cases by Continent:** A time series graph showing the progression of COVID-19 cases across continents.
  - **Deaths by Continent:** A similar graph illustrating the trend of COVID-19-related deaths by continent.
  - **Vaccinations by Continent:** Tracks the number of vaccine doses administered over time, segmented by continent.

## Data Source

The data used in this dashboard was retrieved from reliable public health databases, ensuring accurate and up-to-date information. SQL was utilized to explore, clean, and preprocess the data before it was imported into Tableau for visualization.

## SQL Exploration

Before the data was visualized in Tableau, it underwent extensive exploration and processing using SQL. This included:

- **Data Cleaning:** Handling missing values, duplicates, and inconsistencies in the dataset.
- **Aggregations:** Calculating total cases, deaths, and vaccine doses at both the country and continent levels.
- **Joins:** Merging multiple datasets to combine information on cases, deaths, and vaccinations.
- **Filtering:** Extracting relevant data for specific time periods or geographic regions.

The SQL queries used for these operations are available in the `SQL_Queries.sql` file in this repository.

## How to Use the Dashboard

1. **Interactive Filters:** Use the continent filter to focus on specific regions.
2. **Hover and Click:** Hover over the map or charts to view detailed statistics for each region or time period.
3. **Update Data:** The dashboard can be refreshed with new data by updating the underlying SQL queries and re-importing the data into Tableau.

## Conclusion

This dashboard serves as a powerful tool for tracking the impact of COVID-19 across the globe. By integrating SQL for data exploration and Tableau for visualization, this project provides an in-depth analysis that is both informative and easy to navigate.

## Contact

For any questions or feedback, feel free to reach out to the project author.

---

Feel free to modify or expand upon this README as needed for your specific project!
