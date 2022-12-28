# Case Study: How Does Cyclistic Bike-Share Navigate Speedy Success?

## Background Information

####  My Role: Junior data analyst at the marketing analyst team

####  Situation: Cyclistic financial analysts concluded that annual members are more profitable than casual riders

####  Objective: Analyze datasets and share findings and recommendations

## Ask Phase

#### Business Task: design marketing strategies aimed at converting casual riders into annual members

#### Key Question: How do annual members and causal riders use Cyclistic bikes differently?

#### Key Stakeholders:
   * Lily Moreno (Director of Marketing & My Manager)
   *  Cyclistic marketing analytics team
   *  Executive team

## Prepare Phase 

#### Data Source: Motivate International Inc. 

#### Data Integrity: https://ride.divvybikes.com/data-license-agreement

#### Data Type: CSV file and Public data

#### Data Description:
   - Total of 12 datasets
   - Time period: April 2021 to March 2022 (12 months)
  
#### Data Variables:
   - ride_id: a unique ID for each bike rider
   - rideable_type: type of bike used (docked, classic, electric bike)
   - started_at: date and time the bike is checked out
   - end_at: date and time the bike is checked in
   - start_station_name: name of station the start of the ride
   - start_station_id: a unique ID for each start station
   - end_station_name: name of station the end of the ride
   - end_station_id: a unique ID for each end station
   - start_lag: latitude of the starting point
   - start_lng: longitude of the starting point
   - end_lag: latitude of the ending point
   - end_lng: longitude of the ending point
   - member_causal: type of bike user (casual / member)

## Process Phase
- Data Processing (line 7 - 47 in [R Markdown](https://github.com/harris-wan-analyst/cyclistic_bike_share_analysis/blob/main/cyclistic_bike_share_analysis.Rmd))
- Data Cleaning (line 19 - 83 in [R Markdown](https://github.com/harris-wan-analyst/cyclistic_bike_share_analysis/blob/main/cyclistic_bike_share_analysis.Rmd))
