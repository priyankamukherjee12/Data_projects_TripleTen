# The Zuber Database

This was my second project in the TripleTen Business Intelligence Analytics Program. It was a solo project to show off my SQL skills.

Please find my queries [here](Queries.md).

## Table of Contents

| File Number | Title            | Description                                                                 |
|-------------|------------------|-----------------------------------------------------------------------------|
| 1           | [README.md](README.md)      | This page contains all essential details about the project, located immediately after the Table of Contents. |
| 2           | [Requirements.txt](Requirements.txt) | A straightforward text file listing the project requirements as specified by TripleTen. |
| 3           | [Table.png](Table.png) | A picture file (.png) that shows how the tables in this project are connected. |
| 4           | [Queries.md](Queries.md)  | The SQL commands I used and their outcomes for this project.                |

## Sections

| Section Title | Description                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Explains where the data came from, including the files, tables, and fields involved.                                                                          |
| Description   | Outlines the goal of the final product, the software used, its format, and the visuals included.                                                             |
| Assumptions   | Details the assumptions provided by TripleTen and those derived from the data and the project's objectives.                                                   |
| Process       | A broad overview of the project's development from beginning to end.                                                                                         |
| Findings      | Key findings derived from analyzing the data, providing insights into taxi ride durations, weather conditions, and their impact on the dynamics of taxi rides. |


### Data

A database with info on taxi rides in Chicago provided by TripleTen:

- **neighborhoods table**: data on city neighborhoods
  - `name`: name of the neighborhood
  - `neighborhood_id`: neighborhood code
- **cabs table**: data on taxis
  - `cab_id`: vehicle code
  - `vehicle_id`: the vehicle's technical ID
  - `company_name`: the company that owns the vehicle
- **trips table**: data on rides
  - `trip_id`: ride code
  - `cab_id`: code of the vehicle operating the ride
  - `start_ts`: date and time of the beginning of the ride (time rounded to the hour)
  - `end_ts`: date and time of the end of the ride (time rounded to the hour)
  - `duration_seconds`: ride duration in seconds
  - `distance_miles`: ride distance in miles
  - `pickup_location_id`: pickup neighborhood code
  - `dropoff_location_id`: dropoff neighborhood code
- **weather_records table**: data on weather
  - `record_id`: weather record code
  - `ts`: record date and time (time rounded to the hour)
  - `temperature`: temperature when the record was taken
  - `description`: brief description of weather conditions, e.g., "light rain" or "scattered clouds"

### Description

Conducted a six-step SQL query process for exploratory analysis, specifically investigating if rain affects the duration of taxi rides from the Loop to O'Hare International Airport on Saturdays. Aimed to uncover patterns in competitor data to understand passenger preferences better. Explored the impact of external factors, like weather, on the dynamics of taxi rides.

### Assumptions

- There isn't a direct connection between the trips table and weather_records table in the database.
- `neighborhood_id` is the Primary Key for the neighborhoods table.
- `cab_id` is the Primary Key for the cabs table.
- `trip_id` is the Primary Key for the trips table.
- `record_id` is the Primary Key for the weather_records table.

### Process

- Conducted analysis of taxi rides by company, focusing on particular dates and organizing the data by the number of trips.
- Examined rides from companies with names that include certain keywords, organizing the results by company name.
- Identified the neighborhood IDs for both O'Hare and the Loop.
- Organized weather conditions by each hour of the day.
- Extracted data on Saturday rides from the Loop to O'Hare, noting both weather conditions and ride duration.
- Arranged the findings in a structured manner.

### Findings

1. The taxi company "Flash Cab" had the highest number of taxi rides for Nov. 15th-16th, 2017 at 19,558 trips.
2. When searching SQL for a taxi company that contains the keyword "Yellow" or "Blue": The taxi company "Blue Diamond" had the highest number of taxi rides for Nov. 1st-7th, 2017 at 6,764 trips.
3. When comparing the two most popular taxi companies "Flash Cab" and "Taxi Affiliation Services" with all other available companies for Nov. 1st - 7th, 2017; The total number of taxi rides from "Other" is significantly higher than each top company separate or combined.
4. The SQL "neighborhood_id" identifiers of the O'Hare and Loop neighborhoods are ID # 63 and 50 respectively.
5. Each hour had been given a designated weather condition, starting with a "Good" designation.
6. A SQL table was printed to show all rides that started in the Loop on a Saturday and ended at O'Hare. Tables included start time, weather conditions, and duration.
