# ✈️ Airline Dashboard with Tableau

## Welcome

Welcome to the GitHub repository for our captivating Airline Dashboard – a comprehensive solution for visualizing and managing airline operations data.

## Tableau Dashboard

Explore the live Tableau Dashboard [here](https://public.tableau.com/app/profile/sudheer.pulapa/viz/SFOFlightDataDashboardAirLineDataset/SFOFlightDataDashboard?publish=yes).

## Dynamic Queries

### 1. Total Flight Extravaganza
Discover the daily symphony of flights and unveil the total number of flights in a day.

### 2. SFO Airport Showdown
Witness the hustle and bustle! Pinpoint the busiest day at San Francisco International Airport (SFO).

### 3. Daily Flight Delight
Journey through the month, experiencing the ebb and flow of flight counts each day.

### 4. Top Ten Flight Frenzy
Lights, Camera, Action! Showcase the top ten busiest flight routes for an exhilarating ride.

### 5. Epic Long-Haul Adventures
Unveil the magic of the skies! Highlight the top ten longest flight routes, a spectacle of distance.

### 6. Global Wings
Embark on a visual odyssey! Map the flights departing from SFO to diverse destinations worldwide.

## Airline Data Transformation

To elevate the dashboard's allure, we've transformed the data with precision:

- **Route Divination:**
  - Witness the magic of separation! The 'Route' column has been gracefully split into two, revealing the origin and destination.
- **Number of Flights through Calculated Field:**
  - To analyze flights taking off, used date and number of flights.
- **Monthly Flight Analysis:**
  - To analyze flights in a month, used data and number of flights.
- **Busiest Routes Query:**
  - Used a query to identify busy routes: IF [Route - Split 1] = "SFO" THEN [Route - Split 2] ELSE [Route - Split 1] END
- **Busiest Routes Visualization:**
  - Visualized busiest routes using 'busy' and number of flights.
- **Longest Routes Analysis:**
  - Analyzed longest routes using 'busy' (avg) and number of flights.
- **Mapping Flights from San Francisco:**
  - Mapped flights from San Francisco, creating origin and destination metrics and a distance metric.

## Dashboard Creation

Integrated all sheets into a cohesive Dashboard named **SFO Flight Data Dashboard**.

Feel free to immerse yourself in this visual feast. Explore, contribute, and let the data take you on a journey through the skies!

Happy analyzing! ✨
