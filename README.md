🌦️ Weather Analytics Dashboard (Power BI)

A fully interactive Weather & Air Quality Analytics Dashboard built using Power BI and real-time weather API data.
The dashboard displays current weather conditions, forecasts, sunrise/sunset times, air quality levels, and environmental indicators for multiple cities.

4
🚀 Project Overview

This project visualizes real-time weather and air quality data using a weather API.
It includes:

Current temperature and weather condition

7-day forecast with a line chart

Sunrise and sunset times

Humidity, pressure, visibility, wind speed, UV index

Air Quality Index (AQI) with pollutant breakdown

City switching panel (Ajmer, Lucknow, Mumbai, Noida, Pune, Satara etc.)

Chance of rain for each day

API-based automatic data refresh

This dashboard can be integrated into Power BI Desktop or Power BI Service with scheduled refresh.

📌 Features
1. Current Weather Card

Shows real-time:

Temperature (°C)

Weather condition (Mist, Overcast, Sunny, etc.)

City selection

Last updated timestamp

2. 7-Day Forecast

A line chart displaying:

Daily forecasted temperatures

Weather icons

Day labels

Smooth visual trendline

3. Sunrise & Sunset

Displays:

Sunrise time

Sunset time

4. Air Quality Index (AQI)

Circular AQI gauge showing:

AQI category (Unhealthy, Very Unhealthy, etc.)

AQI value

Pollutants: PM10, PM2.5, SO₂, CO, NO₂, O₃

5. Environmental Indicators

Cards showing:

Humidity

Wind Speed

Visibility

Pressure

UV index

Precipitation

6. Chance of Rain

A bar chart showing the probability (%) for each upcoming day.

🧩 How the API is Used

This dashboard pulls data from a weather API by sending HTTP requests for:

Current weather

7-day forecast

Air quality

Sunrise/Sunset

Location-based details

The API response (JSON) is transformed inside Power Query (M language) and loaded into Power BI tables.

Example API workflow:

Create parameters for API key and city name

Call the weather API for each city

Convert JSON → table

Expand nested fields

Create lookup tables for forecast, AQI, and current weather

Bind data to visuals

🏗️ Technology Stack
Component	Description
Power BI Desktop	Dashboard design & data modeling
Weather API	Real-time data for weather & AQI
Power Query (M Code)	API calls and data transformation
DAX	Measures for forecast and chance of rain
JSON	API data format
GitHub	Project hosting
🔧 How to Use This Project
1. Download the repo
git clone https://github.com/your-username/weather-dashboard.git

2. Open the .pbix file

Use Power BI Desktop.

3. Add your API key

Go to:

Home → Transform Data → Manage Parameters

Replace the placeholder key with your own API key from your weather service.

4. Refresh data

Click:

Home → Refresh

Power BI will fetch the latest weather & AQI data.

📊 Visuals Included

Modern gradient temperature card

Dark mode theme

Circular AQI gauge

Daily forecast icons

Horizontal rain probability bars

Clean metric cards

🎯 Purpose of the Project

This dashboard is ideal for:

✔ Weather analysis
✔ Environmental monitoring
✔ Urban planning
✔ Air quality tracking
✔ Data visualization portfolio
✔ Power BI learning / demonstration

📁 Project Structure
weather-dashboard/
│
├── Weather_Dashboard.pbix
├── README.md
├── /screenshots
│     ├── dashboard1.png
│     ├── dashboard2.png
│     └── dashboard3.png
└── api-notes.txt

📝 Future Improvements

Add hourly forecast

Add maps with real-time weather layers

Add alerts panel using API notifications

Add historic AQI trend analysis

🙌 Acknowledgements

Weather and air quality data provided by an external weather API

Dashboard design created using Power BI custom visual elements
