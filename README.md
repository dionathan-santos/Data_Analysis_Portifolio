#edmonton_real_estate_new_units_houses

# Edmonton Building Permits Data Analysis: New House Units Project

[Click here to visualize the entire Notebook File](https://github.com/dionathan-santos/data_analysis_portifolio/blob/main/Edmonton_Permits.ipynb)

## Technical Approach

The analysis was performed using the following tools and libraries:

- **Python**: Primary language for data analysis.
- **Pandas**: Data cleaning, transformation, and aggregation.
- **Matplotlib**: Visualization of trends, distributions, and geographic data.
- **Seaborn**: Advanced plotting for correlation heatmaps.
- **Jupyter Notebooks**: Used to organize the code, visualize data interactively, and develop the analysis step by step.

### Key Analytical Steps:
1. **Data Wrangling**: Data cleaning to handle missing values, conversion of date columns, and filtering for relevant data.
2. **Exploratory Data Analysis**: Summary statistics, groupings, and plotting to identify patterns and trends.
3. **Geospatial Analysis**: Use of latitude and longitude to visualize geographic trends.
4. **Correlation and Trend Analysis**: Statistical analysis to find relationships between variables, such as floor area vs. units added, and permit date vs. units added.

## Project Files
- **Edmonton_Permits.ipynb**: The Jupyter Notebook containing the full data analysis and visualizations.
- **Data**: A CSV file with Edmonton's building permit data.
- **README.md**: This README file documenting the project.

## Overview
This project presents a comprehensive data analysis of **building permits** in Edmonton, focusing specifically on **new house units** added between the years covered in the dataset (2009 to 2024). The goal of this project was to explore trends, patterns, and insights about residential construction, including geographic distribution, seasonality, construction costs, and the impact of zoning and job categories. This repository demonstrates my expertise in **data wrangling**, **exploratory data analysis**, and **visualization** using **Python**.

## Dataset
The dataset contains detailed information on building permits in Edmonton, extracted from https://data.edmonton.ca/

### Key Columns Used:
- `UNITS_ADDED`: Number of new house units added.
- `CONSTRUCTION_VALUE`: Total construction value of the project.
- `BUILDING_TYPE`: The type of building being constructed (e.g., Duplex, Apartment).
- `ZONING`: Zoning regulations associated with each permit.
- `JOB_CATEGORY`: Categorization of the type of construction (e.g., New Construction, Alterations).

## Analysis Summary

### Trend of New House Units Over the Years
I analyzed the trend in the number of new house units added to Edmonton over time. The data shows significant growth between 2009 and 2013, followed by fluctuating numbers, with a surge around 2020 due to possible increased housing demand during the pandemic.

![**Number of new house units added per year**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/2_Monthly%20Trend%20Of%20Units%20added%20(2020-2024)%20with%20highlights.jpg)

### Top Neighborhoods for New House Unit Development
Neighborhoods such as **Chappelle**, **Laurel**, **Windermere**, and **Walker** saw the newest units. This analysis helps identify hot spots for residential development within Edmonton.

![**Top 5 neighborhoods by total new house units added**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/4_Top%205%20Neighbourhoods%20for%20New%20Units%20last%203%20years.jpg)

### Average Construction Value by Neighborhood
The analysis of construction value reveals that neighborhoods like **Goodridge Corners** and **Desrochers Area** have the highest average construction values for new house units. This provides insights into the scale and cost of developments in different areas.

### Seasonality of New House Unit Construction
There is a clear seasonal trend, with March and May experiencing peaks in new house unit construction. This insight can be valuable for predicting future housing supply and scheduling construction activities.

![**Units added by month**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/2_Monthly%20Trend%20Of%20Units%20added%20(2020-2024)%20with%20highlights.jpg)

### Most Common Building Types
Among building types, **Apartments** and **Duplexes** are the most common for new house units, highlighting a trend toward multi-family dwellings in Edmonton.

### Geographic Distribution of New House Units
Using latitude and longitude data, we created a geographic distribution map of new house units. The results show significant clustering of new development in certain regions of the city.

![**Geographic scatter plot showing the distribution of new house units**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/7_Distribution%20of%20New%20Housing%20Units%20Edmonton.jpg)

### Proportion of Units in Larger Projects
A significant portion (around **19.45%**) of new house units are part of larger projects like apartment buildings. This indicates a substantial share of multi-unit residential development in Edmonton.

### Fluctuations During Economic Events
There were observable fluctuations in the number of units added during major economic events such as the 2008-2010 recession and the 2020 pandemic, which saw a spike in new house construction.

![**Fluctuations in new house units during economic events**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/3_Monthly%20Trends%20of%20Units%20Added%20with%20Rolling%20Average.jpg)

### Correlation Between Permit Approval and Project Size
There is a weak correlation (0.048) between the permit approval year and the number of units added, suggesting that permit timing does not heavily influence project size.

![**Correlation heatmap between permit year and units added**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/5_Coor%20Matrix.jpg)

### Some other visualizations

![**Cluster by Constructions Metrics in Edmonton**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/8_Cluster%20for%20Contructions%20Paterns.jpg)

![**Distribution of Construction Value**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/blob/secondary/Images/6_Distribution%20of%20Construction%20Value.jpg)

[**All visualizations in this Folder**](https://github.com/dionathan-santos/edmonton_real_estate_new_units_houses/tree/secondary/Images)



