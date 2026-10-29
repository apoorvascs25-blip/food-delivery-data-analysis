Food Delivery Demand Analysis

Overview

This project explores a food-delivery dataset to understand order demand, order value, delivery delays, traffic and weather conditions, route characteristics, customer behaviour, and food quality. The analysis is performed in a Jupyter Notebook using Google Colab.

Objectives

Explore the dataset structure, data types, missing values, and duplicate records.

Analyze demand by food item and location.

Summarize order values and delivery distances/delays.

Compare delivery delays across traffic conditions, weather conditions, delivery methods, and route information.

Explore customer age groups, order frequency, loyalty-program status, ratings, and satisfaction.

Examine food freshness, packaging quality, and food condition.

Visualize numerical relationships and correlations.

Export an analysis-ready CSV file.

Tools and Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab / Jupyter Notebook

Excel or CSV input dataset

Dataset

The notebook expects a food-delivery dataset in .xlsx, .xls, or .csv format. The dataset used when the notebook was originally developed contained 20,000 records and fields such as:

Order details: order_id, restaurant_id, food_item, order_time, delivery_time

Delivery details: delivery_distance, delivery_method, delivery_delay, traffic_condition, weather_condition, route_taken, route_type, route_efficiency

Customer details: customer_id, age, gender, location, order_history, preferred_cuisine, order_frequency, loyalty_program

Experience and quality: customer_rating, customer_satisfaction, food_temperature, food_freshness, packaging_quality, food_condition

Please use only data that you have permission to share. If the dataset is not included in the repository, each person running the notebook will need to upload their own copy.

How to Run in Google Colab

Download food_delivery_demand_analysis_fixed.ipynb from this repository or open it in Google Colab.

Run the notebook cells from top to bottom.

When the upload prompt appears, select the dataset file (.xlsx, .xls, or .csv).

Review the generated tables and visualizations.

The final cells create food_delivery_analysis_ready.csv. In Google Colab, the last cell prompts a download of that file.

How to Open the Notebook from GitHub

Open the notebook file in your GitHub repository.

Copy its URL.

Go to Google Colab.

Choose File → Open notebook → GitHub, paste the repository URL, and select the notebook.

Run the notebook from the first cell.

Main Analysis Areas

Dataset inspection and basic quality checks

Order demand by food item and location

Order-value summaries

Delivery distance, delay, traffic, and weather analysis

Delivery method and route analysis

Customer demographics and ordering behaviour

Customer ratings and satisfaction

Food freshness, packaging, and food-condition analysis

Correlation analysis and outlier checks

Summary dashboard and export of the analysis-ready dataset

Important Data Notes

The notebook removes empty columns whose names begin with Unnamed, which can appear when a spreadsheet is exported.

The saved notebook outputs previously showed order_time values at 00:00:00. If the source data contains dates only rather than actual times, hour-of-day and time-period analysis is not meaningful; the corrected notebook marks the time period as unavailable in that situation.

The dataset includes negative delivery_delay values in the previously saved outputs. Confirm how delivery_delay is defined (for example, whether negative values mean early delivery) before drawing conclusions from delay categories or averages.

Correlation does not prove causation. Findings should be interpreted in the context of how the dataset was generated.

Output

The notebook saves an analysis-ready file named food_delivery_analysis_ready.csv.


Future Improvements

Add a concise summary of the most important findings after reviewing the final charts.

Improve validation of timestamps and delivery-delay values.

Add more targeted visualizations or a simple predictive model if appropriate for the project goals.
