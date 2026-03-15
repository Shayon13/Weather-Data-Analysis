# Weather-Data-Analysis
# Project Overview
This project performs Exploratory Data Analysis (EDA) on a time-series weather dataset using Python and the Pandas library. The dataset contains hourly weather conditions recorded over a period of time. The project demonstrates how to clean, manipulate, and analyze data to extract meaningful insights using various Pandas functions and logical conditions.
# Technologies Used
 1.Python 
 2.Pandas (Data manipulation and analysis)
 3. NumPy (Numerical operations)
 4.Jupyter Notebook / VS code 
# Dataset Information
 The dataset ( Weather Data.csv) contains 8,784 rows and 8 columns with the following weather attributes:
  1. Date/Time: The date and time of the record.
  2. Temp_C: Temperature in Celsius.
  3. Dew Point Temp_C: Dew point temperature in Celsius.
  4. Rel Hum_%: Relative humidity percentage.
  5. Wind Speed_km/h: Wind speed in kilometers per hour.
  6. Visibility_km: Visibility distance in kilometers.
  7. Press_kPa: Atmospheric pressure in kilopascals.
  8. Weather: General weather condition (e.g. Rain, Clear, Fog, Snow). Note: Renamed to Weather condition during the analysis.
# Key Analysis & Operations Performed
    1. Data Exploration: Explored the dataset using .head(), .shape, .info(), and .dtypes.
    2. Unique Values: Identified all unique wind speed values in the dataset.
    3. Data Filtering:
          1. Found the exact number of times the weather was "Clear".
          2. Found the exact number of times the wind speed was exactly "4 km/h".
          3. Isolated all instances where "Snow" was recorded (using partial string matching).
          4. Filtered records where wind speed was > 24 km/h AND visibility was exactly 25 km.

    4. Data Cleaning: Checked the dataset for NULL/missing values (none were found) and permanently renamed columns for better readability.
    5. Statistical Calculations
    6. Data Aggregation 
    7. Complex Conditional Filtering:
        1. Extracted instances where the weather was "Clear" AND relative humidity was > 50%, OR visibility was above 40 km.
