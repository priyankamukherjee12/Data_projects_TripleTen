# SuperStore Returns Analysis

This was my fifth project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Tableau Story Telling.

Tableau Public Share Link: [here](https://public.tableau.com/app/profile/priyanka.mukherjee2482/viz/SuperStoreReturnAnalysis/TotalSalesVsTotalReturn).

## Table of Contents

| File Number | Title                     | Description                                                                                                     |
|-------------|---------------------------|-----------------------------------------------------------------------------------------------------------------|
| 1           | [DataSet_superstore.xlsx](DataSet_superstore.xlsx)  | The original data file provided by TripleTen that was used in this project's analysis.                          |
| 2           | [README.md](README.md)                 | This current page with all relevant information about the project, just past the Table of contents.            |
| 3           | [Requirements.txt](Requirements.txt)          | A simple .txt file with the provided project requirements as provided by TripleTen.                             |

## Section Titles and Descriptions

| Section Title | Description                                                                                                                                               |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Describes the source of data, included files, tables, and fields.                                                                                         |
| Description   | Describes the final product's purpose, software, format, and included visuals.                                                                            |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task.                                                      |
| Process       | A general outline of how this project formed from start to finish.                                                                                        |
| Findings      | Insights learned from the data analysis.                                                                                                                  |
| Notes         | Notes sent with project to the reviewer for more context about presentation choices.                                                                      |

### Data

The data was one Excel spreadsheet file provided by TripleTen:

- **Superstore.xls**: each row corresponds to one product sold; sheets were LEFT JOIN'd
  - `orders`: details all fields for each ordered item
  - `returns`: details all fields for each returned item

### Description

- **8 page Tableau Visualization and Presentation**
  - Includes data analysis, charts, dashboard, and stories.
  - Purpose was to prepare an analysis for the CEO of Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

### Assumptions

- Profits from sales are totaling in the negative.
- There is one or more causes for negative profits directly related to orders and returns.
- Operations department will need to make changes.

### Process

- I combined data sheets, analyzed return causes through visualizations, and summarized findings in a Tableau story, creating a comprehensive overview of return patterns and insights.

### Findings

1. Declining profits at Superstore are primarily due to returned purchases.
2. A positive correlation exists between the volume of sales and returns.
3. The technology category experiences the highest rate of returns.
4. A select group of customers exhibit a 100% return rate.
5. Return rates vary by state and sub-category.
6. The return rate of orders fluctuates based on the month of purchase.
7. Return rates are independent of sales volume; some low-selling products see a 100% return rate.
