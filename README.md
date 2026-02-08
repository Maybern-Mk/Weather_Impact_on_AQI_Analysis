🌦️ Weather & Air Quality Analysis – Indian Cities
📌 Project Overview

This project analyzes the relationship between weather conditions and air pollution levels across major Indian cities using real historical weather data and Air Quality Index (AQI) metrics.

The focus is on understanding how temperature, humidity, precipitation, cloud cover, and wind speed interact with pollutant levels in urban environments.

🎯 Objectives

Fetch historical weather data for Indian cities using an external API

Analyze city-wise temperature and weather conditions at a fixed time

Merge weather data with AQI / pollutant metrics

Perform exploratory data analysis (EDA)

Visualize pollution trends and correlations with weather variables

🧰 Tech Stack

Python

Pandas, NumPy

Requests (API integration)

Matplotlib, Seaborn

CSV-based data storage

🌍 Cities Covered

Bengaluru, Karnataka

Mumbai, Maharashtra

Chennai, Tamil Nadu

Kolkata, West Bengal

Delhi, Delhi

Hyderabad, Telangana

Jaipur, Rajasthan

📥 Data Sources
1️⃣ Weather Data

Source: World Weather Online API

Data extracted:

Temperature (°C)

Humidity

Precipitation (mm)

Wind speed (km/h)

Cloud cover

Weather description

Fixed snapshot time: 20:00 (8 PM) on 19 Oct 2025

2️⃣ Air Quality Data

Loaded from local CSV

Includes:

Pollutant ID

Average pollutant level

Maximum pollutant level

City & State mapping

🔄 Project Workflow
1️⃣ Weather Data Extraction

API request sent for each city

Hourly weather data filtered to 20:00

Stored structured weather data into a Pandas DataFrame

Exported to CSV for reuse

2️⃣ Data Cleaning

Handled missing values

Converted numeric columns (pollutant levels, temperature)

Standardized date formats

Sorted data based on temperature and pollutant concentration

3️⃣ Data Integration

Combined weather data and AQI data

Created a unified dataset for correlation analysis

Ensured city-level alignment

4️⃣ Exploratory Data Analysis (EDA)

Performed:

Descriptive statistics

City-wise pollutant comparison

Distribution analysis

Cross-tabulations between:

Temperature & pollutant type

State & pollutant ID

📊 Visualizations Used

Bar charts (pollution levels by city)

Line plots (humidity vs pollutant levels)

KDE plots (pollution distribution across cities)

Box plots & strip plots

Pie chart (Top 5 most polluted cities)

Histograms & count plots

Scatter-style relationship plots

🔍 Key Insights

Certain cities show consistently higher pollutant averages

Pollution levels vary significantly with humidity and temperature

Some pollutants dominate specific regions

Weather conditions influence pollutant concentration but do not directly imply causation

🚀 Future Enhancements

Add real-time AQI API integration

Perform regression modeling for pollution prediction

Extend analysis to seasonal & multi-day trends

Build interactive dashboards (Power BI / Tableau)

👤 Author

Mrudul Paku
Data Analytics | Python | API Integration | Data Visualization
