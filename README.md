# European Air Traffic Analysis (1993-2022)

## Overview
This project analyzes European air traffic over a 30-year period (1993-2022) using Tableau. The objective is to understand traffic evolution, compare passenger and flight activity, and identify key trends across countries.

## Objectives
- Analyze overall European air traffic trends
- Compare passenger volume and flight activity
- Identify leading countries and market concentration
- Detect seasonality and long-term growth patterns

## Dataset
- Source: European air traffic statistics dataset
- Time period: 1993-2022
- Structure: Multiple CSV files (passengers, flights, arrivals, departures)
- Granularity: Monthly, quarterly, and yearly data
- Key variables:
  - Country
  - Year / Quarter / Month
  - Passengers
  - Flights
  - Arrivals and Departures

## Data Preparation
- Imported multiple CSV files into Tableau
- Combined datasets using union to integrate different time levels
- Cleaned and validated data
- Standardized key variables (Country, Year, Passengers, Flights)
- Built a unified dataset for analysis

## Calculated Measures
- Flight Balance
- Passenger Growth
- Passenger Growth Index
- Passenger Market Share (%)
- Passengers per Flight

## Dashboard Structure
The analysis is organized into six dashboards:

1. Geographic Overview
   - Distribution of passengers and flights across countries
   - Identification of major aviation hubs

2. Market Leaders
   - Top and bottom countries by passenger volume
   - Market share comparison

3. Traffic Trends
   - Evolution of passengers and flights over time
   - Impact of major events (e.g., COVID-19)

4. Seasonality and Growth
   - Monthly and quarterly traffic patterns
   - Long-term growth trends

5. Country Performance
   - Relationship between flights and passengers
   - Efficiency comparison across countries

6. Distribution and Dynamics
   - Traffic concentration analysis
   - Country-level evolution over time

## Key Insights
- Air traffic is concentrated in a small number of countries
- United Kingdom, Germany, and Spain dominate passenger volume
- Strong long-term growth from 1993 to 2019
- Significant drop in 2020 due to COVID-19
- Gradual recovery observed after 2021
- Clear seasonality with peaks during summer months
- Strong correlation between flights and passenger volume :contentReference[oaicite:0]{index=0}

## Conclusion
European air traffic shows sustained growth over the long term, with clear concentration in major countries and strong seasonal patterns. The COVID-19 crisis caused a major disruption, followed by a gradual recovery phase.
## Tools
- Tableau
- CSV datasets
