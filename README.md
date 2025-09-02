# India Weather Monitor Dashboard 🌦️

**Description / Purpose:**

This project automates the complete workflow of collecting, processing, and visualizing weather data for major Indian cities. Using Python, it connects to the WeatherAPI.com service to fetch real-time weather conditions, 7-day forecasts, and air quality information. The data is then cleaned, structured, and enriched with custom transparent weather icons before being exported into CSV files. These files serve as the data source for a modern, interactive Power BI dashboard, which provides users with clear and dynamic insights into live and forecasted weather trends.

**Tech Stack:**
The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main data visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (Current_weather, Forecast_Weather, Forecast_weather_sunrise_Sunset and data_dictionary) to enable     cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.

**Data Source**
. Provider: WeatherAPI.com
. API Endpoint: Forecast API (forecast.json)

This service provides hyper-local, real-time weather data as well as a 7-day forecast. The API was used to collect a wide range of metrics, including temperature, humidity, wind speed, pressure, UV index, and sunrise/sunset times.

**Dashboard Features:**
. This interactive Power BI dashboard is designed to make weather insights both engaging and easy to explore. A multi-city slicer lets users switch between 10 major Indian cities, instantly updating the visuals to reflect local conditions. The live data display ensures that the main panel and detail cards always show the latest weather, with a clear “Last Updated” timestamp for transparency.

. The layout balances simplicity with detail. A hero panel highlights current conditions with temperature, weather icons, and descriptive text (e.g., “Partly Cloudy”), supported by cards for humidity, wind speed, sunrise, and sunset. The 7-day forecast is presented in a clean, grid-style view with daily icons, max/min temperatures, and intuitive bar graphics to represent temperature ranges.

. A modern design approach ties everything together. The dashboard uses transparent, high-quality SVG icons that blend perfectly with its dark theme, while glassmorphism-inspired panels with semi-transparent layers and rounded corners give it a sleek, professional look that’s both functional and visually appealing.
• Business Impact & Insights Marketing Optimization: Travel agencies can use this dashboard to identify key selling points for different demographics (e.g., child-friendly resorts or expert terrain). Strategic Expansion: Resort developers can spot underdeveloped regions with high potential. Vacation Planning: Tourists can plan trips based on slope availability, elevation, and terrain difficulty. Regional Analysis: Governments and tourism bodies can analyze competitiveness by region.
