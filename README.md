# 911-Call-Assessment---Exploratory-Data-Analysis-EDA-
This project explores a dataset of 911 calls to uncover insights about call types, locations, and times. By leveraging exploratory data analysis (EDA) techniques, we aim to gain a better understanding of patterns in emergency calls and any trends that could help improve emergency response and resource allocation.

## Dataset

  The dataset contains information on 911 calls, with attributes such as:
  * Lat: Latitude
  * Lng: Longitude
  * Description: Detailed description of the emergency
  * Timestamp: Time and date of the call
  * Category: The general type of emergency (e.g., Fire, EMS, Traffic)
  * Township: The township where the call originated
  * Address: Location details

## Goals
  * Identify the most common types of emergencies.
  * Analyze the distribution of calls over time (hour, day, month).
  * Explore geospatial patterns in emergency call locations.
  * Assess if certain emergencies are more common in specific locations or times.
  * Provide insights that could help emergency services optimize their operations.

## EDA Process

### Data Cleaning:

* Handled missing values and irrelevant columns.
* Parsed dates and times for time-based analysis.

### Descriptive Statistics:

* Summarized key statistics for numeric and categorical variables.

### Visualizations:

* Time series plots for calls over different periods.
* Heatmaps to visualize call density over different periods.
* Pie charts or bar plots for emergency categories.

## Tools & Libraries

* Pandas: For data manipulation and cleaning.
* Matplotlib & Seaborn: For visualizations.
* Plotly: For interactive geospatial visualizations.
* Numpy: For numerical operations.

## Insights & Results

* EMS-related calls make up the majority of 911 calls.
* A significant spike in calls is observed during certain hours of the day.
* Traffic-related incidents are more frequent during rush hours.

## Future Work

* Integrating machine learning models for call type prediction.
* Implementing time series forecasting to predict call volumes.
* Further in-depth analysis of the impact of weather on emergency calls.

## Contributions
Feel free to submit issues or pull requests if you have suggestions or improvements for the project!

