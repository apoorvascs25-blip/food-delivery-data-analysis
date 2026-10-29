#  Food Delivery Demand Analysis

An exploratory data analysis project using Python to investigate food delivery demand, delivery delays, traffic and weather conditions, route efficiency, customer behaviour, and food quality.

##  Project Overview

Food delivery services involve several factors that can influence delivery performance and customer satisfaction. This project explores a food delivery dataset to identify patterns in ordering behaviour, delivery times, traffic conditions, weather, and customer experience.

The analysis is performed using Python in Google Colab, with data manipulation, exploratory analysis, and visualizations to understand the dataset.

## Objectives

* Explore the dataset structure, data types, missing values, and duplicate records.
* Analyze food ordering patterns and order values.
* Examine delivery distances and delivery delays.
* Explore the relationship between delivery delays, traffic conditions, and weather.
* Analyze delivery methods and route characteristics.
* Investigate customer demographics and ordering behaviour.
* Explore customer ratings, satisfaction, and food quality.
* Visualize numerical relationships and correlations.
* Prepare an analysis-ready dataset for further analysis.

## Technologies Used

* **Python** — Programming language
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Google Colab** — Notebook execution environment
* **Jupyter Notebook** — Interactive code and analysis

##  Dataset

The notebook accepts a food delivery dataset in Excel (`.xlsx` or `.xls`) or CSV (`.csv`) format.

The dataset contains fields relating to:

* **Orders:** Order IDs, restaurant IDs, food items, order times, and delivery times.
* **Delivery:** Delivery distance, delivery method, delivery delay, traffic, weather, and route characteristics.
* **Customers:** Customer IDs, age, location, order history, preferred cuisine, order frequency, and loyalty-program status.
* **Customer experience:** Ratings, satisfaction, food freshness, packaging quality, food temperature, and food condition.

The notebook requires the dataset to be uploaded when running it if the file is not otherwise available in the execution environment.

Only datasets that you have permission to use and share should be distributed publicly.

## Analysis Performed

The project covers the following areas:

1. Dataset inspection and data-quality checks.
2. Analysis of food demand and ordering patterns.
3. Order-value summaries.
4. Delivery distance and delay analysis.
5. Comparison of delivery conditions across traffic and weather categories.
6. Delivery method and route analysis.
7. Customer demographics and ordering behaviour.
8. Customer ratings and satisfaction.
9. Food freshness, packaging, and food-condition analysis.
10. Correlation analysis, visualizations, and preparation of an analysis-ready dataset.

##  Key Data-Quality Considerations

* Empty spreadsheet columns whose names begin with `Unnamed` are handled during preprocessing.
* If order timestamps contain dates without actual times, hour-of-day and time-period analysis may not be meaningful.
* Negative delivery-delay values require interpretation based on the dataset's definition. They may represent early deliveries or a data-quality issue.
* Correlation indicates association, not necessarily causation.

These considerations are important when interpreting the results and drawing conclusions from the dataset.

##  Project Output

The notebook generates an analysis-ready CSV file named:

`food_delivery_analysis_ready.csv`

This file can be used for further exploratory analysis or as a starting point for additional data science work.

##  Future Improvements

* Improve timestamp and delivery-delay validation.
* Develop additional visualizations to investigate delivery performance.
* Explore relationships between customer satisfaction and delivery conditions.
* Extend the analysis with suitable statistical techniques.
* Investigate whether a predictive model could help estimate delivery delays.

## Learning Outcomes

This project provides practical experience with:

* Loading and inspecting structured datasets.
* Data cleaning and preprocessing.
* Exploratory data analysis (EDA).
* Working with Pandas and NumPy.
* Creating visualizations with Matplotlib and Seaborn.
* Identifying data-quality issues.
* Communicating analytical observations.

---

**Project Category:** Data Science · Exploratory Data Analysis · Python
