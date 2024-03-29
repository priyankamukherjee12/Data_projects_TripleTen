# Nyc Airbnb Data Project

This was my first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I had learned for Advanced Spreadsheets.

Google Spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/1LlMRmfGFbBgfIjdY2_OlqAmjdfZq16yzXsruNkCdyk8/edit?usp=sharing).

## Table of Contents

| File Number | Title             | Description                                                                                                     |
|-------------|-------------------|-----------------------------------------------------------------------------------------------------------------|
| 1           | [README.md](README.md)        | This current page with all relevant information about the project, just past the Table of contents.            |
| 2           | [Requirements.txt](Requirements.txt)  | A simple .txt file with the provided project requirements as provided by TripleTen.                             |
| 3           | [airbnb_rental_data_analysis.xlsx](airbnb_rental_data_analysis.xlsx)  | The original data file provided by TripleTen that was used in this project's analysis.                             |

## Section Titles and Descriptions

| Section Title | Description                                                                                                                                               |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Describes the source of data, included files, tables, and fields.                                                                                         |
| Description   | Describes the final product's purpose, software, format, and included visuals.                                                                            |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task.                                                      |
| Process       | A general outline of how this project formed from start to finish.                                                                                        |
| Findings      | Insights learned from the data analysis.                                                                                                                  |

### Data

The data was one Google spreadsheet file provided by TripleTen:

- **airbnb_rental_data_analysis.xlsx**: each row corresponds to one listing on Airbnb in September 2022
- **data_dictionary**: summary of field titles seen in file and its data type
- **listings**: uniquely listings available with all available data
- **calendar**: listings with upcoming availabilities and date type data

### Description

- **12 page spreadsheet**
  - Includes raw data, processed data, data analysis, pivot tables, and a bar chart.
  - Purpose was to determine what types of properties should be targeted for the vacation rental market, in the Manhattan borough of New York City based on available Airbnb data.

### Assumptions

- Airbnb rentals are equivalent to the general vacation rental statistics.
- Rental activity is assumed through the number of reviews in the last 12 months.
- Properties with no reviews in the last 12 months were considered inactive.
- High review ratings are greater than or equal to 4.5.
- Very actively rented properties are rented greater than or equal to 40 times over the last 12 months.
- Extremely low-priced listings are below $100 and super luxury listings are above $1000 and both were filtered from the analysis.

### Process

- I first explored, filtered, and cleaned the data.
- Then I created aggregations and pivot tables to determine the type of properties that should be targeted.
- I performed calculations, pivot tables, and charts to determine occupancy and estimated revenue.
- Lastly, I finalized formatting for the client's readability.

### Findings

1. The top 10 attractive neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.
2. The most popular vacation rental size is 1 bedroom overall.
3. Mondays and Tuesday have the highest occupancy rate out of the week.
4. I identified the Lower East Side and 1 bedroom as a good investment. Estimated revenue for similar properties to recommendations is $39,862.80.
