# Airbnb Price Analysis Dashboard 2016

## Overview

This repository contains the Tableau project for the Airbnb Price Analysis Dashboard 2016. The dashboard provides a comprehensive overview of various pricing metrics for Airbnb listings. The project involves multiple data sources and visualizations to help understand trends and patterns in Airbnb pricing data.

## Getting Data

You can download the dataset from [this link](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset?select=Tableau+Full+Project.xlsx). After downloading, connect the Excel file to Tableau Public. The file is too large to upload here directly.

## Connections Panel

- **Data Source:** "Tableau Full Project" from Microsoft Excel.
- **Sheets Available:**
  - Calendar
  - Listings
  - Reviews
- The data interpreter option is available, indicating that Tableau might help clean the data if needed.

## Sheets Section

- Under the "Sheets" section, there are multiple sheets listed:
  - Calendar
  - Listings
  - Reviews
  - New Union
- These sheets represent different datasets that can be used for analysis.

## Data Join

- In the central pane, there is a visual representation of the join between the "Listings" and "Calendar" tables, indicating that these tables are related through a common field.

## Fields in Listings Table

- The "Listings" table contains 96 fields with 1,048,575 rows.
- Some of the fields are:
  - **Id:** A unique identifier for each listing.
  - **Listing Url:** The URL of the Airbnb listing.
  - **Scrape Id:** An identifier for the data scraping instance.
  - **Last Scraped:** The date when the data was last scraped.
  - **Name:** The name of the listing and many more.


## Key Points

- The project involves a large dataset, with over a million rows in the "Listings" table alone.
- The fields listed include essential information about each Airbnb listing, such as its ID, URL, name etc.
- This setup is foundational for creating various visualizations and dashboards in Tableau. By linking the "Listings" and "Calendar" tables, one can perform more detailed analyses, such as understanding trends over time, comparing prices, and examining booking patterns.


## Price Dashboard of Airbnb 2016

The Price Dashboard of Airbnb 2016 provides a comprehensive overview of various pricing metrics for Airbnb listings. The dashboard includes six main visualizations, each focusing on different aspects of Airbnb pricing data.

### Summary of Each Graph

1. **Avg Price Per Bedroom:**
   - This bar graph displays the average price of listings based on the number of bedrooms.
   - **Key Observations:**
     - 1-bedroom: $96.2
     - 2-bedroom: $175.4
     - 3-bedroom: $249.7
     - 4-bedroom: $315.4
     - 5-bedroom: $450.0
     - 6-bedroom: $584.8
   - The average price increases with the number of bedrooms, indicating a higher price for larger properties.

2. **Distinct Count of Bedroom Listings:**
   - This table shows the count of listings based on the number of bedrooms.
   - **Key Observations:**
     - 1-bedroom: 1,811 listings
     - 2-bedroom: 483 listings
     - 3-bedroom: 206 listings
     - 4-bedroom: 55 listings
     - 5-bedroom: 20 listings
     - 6-bedroom: 5 listings
   - There is a higher number of smaller properties (1 and 2-bedroom) compared to larger ones.

3. **Price Per Zipcode (Map):**
   - This map visualization displays the average price per zipcode.
   - **Key Observations:**
     - Zipcode 98109 has the highest average price, followed by 98103, 98101, and 98102.
     - The prices vary significantly across different zipcodes.

4. **Price by Zipcode (Bar Graph):**
   - This bar graph shows the average price of listings for each zipcode.
   - **Key Observations:**
     - Zipcode 98109 has the highest average price, closely followed by 98103, 98101, and 98102.
     - Zipcode 98136 has the lowest average price.

5. **Revenue for Year:**
   - This line graph shows the total revenue generated over the course of the year 2016.
   - **Key Observations:**
     - The revenue shows an upward trend over the year, with some fluctuations.
     - The projection indicates a continued increase in revenue.

These visualizations provide insights into how the number of bedrooms, location, and time of year impact the pricing and revenue of Airbnb listings in 2016.

---

By providing detailed insights into Airbnb listings, this dashboard helps in understanding key pricing metrics and trends. It can be a valuable tool for stakeholders looking to analyze and optimize their Airbnb offerings.
