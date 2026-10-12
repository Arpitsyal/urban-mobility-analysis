# urban-mobility-analysis
Urban mobility and public transport performance analysis using Tableau
# Urban Mobility and Public Transport Performance Analysis

A Tableau dashboard project analyzing public transport demand, route performance, and vehicle capacity utilization.

## Project Overview

This project explores public transport performance using bus passenger and vehicle load data. The analysis focuses on passenger boarding and alighting activity, route-level demand, peak travel periods, and vehicle capacity utilization.

## Objectives

- Analyze passenger boardings and alightings.
- Identify routes and stops with high passenger activity.
- Examine passenger demand across different time periods.
- Evaluate vehicle load and capacity utilization.
- Identify potential areas for further operational analysis.

## Tools and Technologies

- Tableau — Data visualization and dashboard development
- Python (Google Colab) — Data inspection and preparation
- CSV — Data storage and input

## Key Findings

- **Passenger demand:** Route 18 recorded the highest boarding activity in the analyzed data, according to the dashboard.
- **Peak utilization:** Vehicle utilization increased during the afternoon, reaching approximately 29% around 4:00–5:00 PM, based on the selected utilization metric.
- **Route capacity utilization:** Route 109 recorded the highest average V/C ratio among the selected routes, at approximately 32.7%.
- **Scope of analysis:** The dataset primarily represents weekday bus activity, limiting direct comparisons between weekday and weekend travel patterns.
- **Passenger journey interpretation:** Boarding counts represent boarding events, not necessarily unique passengers. A passenger may board multiple times during a journey.

## Dataset

**Source:** [Transport for London — Bus Crowding Data](https://crowding.data.tfl.gov.uk/)

The dataset includes variables relating to routes, stops, time periods, boardings, alightings, vehicle load, and capacity.

## Interactive Dashboard

[View the Urban Mobility and Public Transport Performance Dashboard on Tableau Public](https://public.tableau.com/views/Urban_Mobility_Public_Transport_Performance/UrbanMobilityandPublicTransportPerformance?:language=en-US&publish=yes)

## Limitations

- The analyzed data primarily covers weekdays, so weekend passenger behavior cannot be directly compared.
- Variables such as service delays, passenger satisfaction, and emissions were not available for this analysis.
- Boarding and alighting counts should not be interpreted as counts of unique passengers.
- The findings describe the analyzed dataset and should not be generalized beyond its coverage without further validation.

## Project Purpose

This project demonstrates practical skills in data preparation, exploratory analysis, dashboard design, and communicating data-driven findings for public transport performance analysis.
