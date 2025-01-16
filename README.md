# Predicting Delivery Times

This repository contains a dataset and analysis tools for predicting food delivery times based on multiple factors such as weather conditions, order details, and geolocation data. The dataset includes detailed information about each delivery, allowing for comprehensive analysis and machine learning model development to estimate delivery times and delays.

## Dataset Overview
The dataset captures various features:

- **DELIVERY_DELAY**: Difference between actual and estimated delivery times (in minutes).
- **ITEM_COUNT**: Number of items in the order.
- **USER_LAT & USER_LONG**: Latitude and longitude of the delivery destination.
- **VENUE_LAT & VENUE_LONG**: Latitude and longitude of the restaurant/venue.
- **ESTIMATED_DELIVERY_MINUTES**: Predicted delivery time provided initially.
- **ACTUAL_DELIVERY_MINUTES**: Time taken for the delivery to be completed.
- **CLOUD_COVERAGE**: Percentage of cloud coverage during the delivery.
- **TEMPERATURE**: Temperature at the time of delivery (in degrees Celsius).
- **WIND_SPEED**: Speed of wind (in meters per second).
- **PRECIPITATION**: Rainfall during the delivery (in millimeters).
- **TIMESTAMP**: Exact time when the delivery request was made.

## Potential Use Cases

### Exploratory Data Analysis (EDA)
- Identify patterns in delivery times based on weather and location.
- Understand the impact of item count and distance on delays.

### Machine Learning
- Train regression models to predict delivery delays.
- Develop classification models to categorize deliveries as on-time or delayed.

### Operational Insights
- Optimize delivery routes and estimate accurate delivery times.
- Provide recommendations to improve delivery efficiency under various conditions.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Dash 
  - GeoPandas 
  - Geopy 
  - pmdarima 
  - CatBoost 
  - scikit-posthocs
  - ydata-profiling 







