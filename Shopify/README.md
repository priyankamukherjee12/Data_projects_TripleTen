# Shopify.pbix

This was my sixth project in the TripleTen Business Intelligence Analytics Program. It was a solo project meant to demonstrate what I've learned about Power BI.

### Table of Contents

| File Number | Title           | Description                                                                                       |
|-------------|-----------------|---------------------------------------------------------------------------------------------------|
| 1           | [README.md](README.md)     | This page contains all the important details about the project, located right after the Table of Contents. |
| 2           | [Requirements.rft](Requirements.rft) | A basic .txt document listing the project specifications as given by TripleTen.                   |
| 3           | [Shopify.pdf](Shopify.pdf)   | A .pdf document featuring images of the three-page Power BI Dashboards from my project.           |



| Section Title | Description                                                                                                                                                     |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Outlines the data source, encompassing the included files, tables, and fields.                                                                                  |
| Description   | Outlines the goal of the final product, the software used, its format, and the visuals included.                                                               |
| Assumptions   | Outlines assumptions provided by TripleTen as well as those derived from the data and the project requirements.                                                |
| Process       | An overview of the project's development process from beginning to end.                                                                                         |
| Findings      | Understanding gained from analyzing the data.                                                                                                                   |


### Data

The excel file provided by TripleTen was public data scraped from the Shopify App Store.

- `'shopify.xlsx'`: Excel Workbook containing 4 sheets:
  - `'apps'`: Details of the apps on Shopify apps marketplace.
  - `'apps_categories'`: Join tables to connect apps with categories.
  - `'categories'`: Categories of the apps. Each app has multiple categories.
  - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). It also contains the response from the developer if present.

### Description

Three-page Power BI Dashboards containing data analysis, key performance indicator (KPI) cards, and charts. The goal was to examine the variety of apps on the Shopify platform by analyzing data collected from public Shopify sites. The aim was to understand what important elements contribute to a Shopify app's success.

### Assumptions

- The data collected from Shopify sites is precise and reflects the real situation of apps available.
- The `'shopify.xlsx'` file is thorough and uniform, with hardly any missing information or discrepancies.
- The names and types of data in the columns accurately describe what they contain.

### Process

First, I looked at the overall app store scene with some key stats and graphs. Then, I sorted out the feedback data with similar tools. In the end, I checked out the app makers based on the kinds of reviews they got.

### Findings

1. New apps usually get rated soon after they are launched.
2. A lot of apps get good ratings.
3. If an app developer replies to a review, that app tends to get higher ratings.
4. Reviews marked as useful have an average rating of `5.48` stars.
5. The app maker `"Elfsight"` has the highest total ratings, adding up to `135.10` stars.
6. The app maker `"Pictorem"` has the highest average for reviews considered helpful, at 50.
7. The app maker `"FireApps"` has replied to the most reviews, with `6,008` responses.
