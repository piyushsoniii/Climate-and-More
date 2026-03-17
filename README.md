# Climate-and-More

## 📖 Overview
*A dynamic, interactive data visualization dashboard designed to analyze climate patterns across seven diverse Indian cities. Key features include real-time weather forecasting, precipitation probability tracking, and comprehensive air quality monitoring.

## 🔌 API & Data Source
This project uses the **Weatherapi ** to populate the dashboard.

## 🛠️ Tech Stack & Architecture
*Business Intelligence Tool:                Power BI Desktop
* Data Extraction & Transformation (ETL):   Power Query (M Language) for data cleaning, shaping, and formatting the raw API data.
* Data Modeling & Calculations:             DAX (Data Analysis Expressions) for creating custom measures and calculated columns.
* Data Integration:                         REST API integration via Power BI's Web connector.
* Data Format:                              JSON parsing via Power Query.

## ✨ Features & Highlights
* Real-Time Weather Tracking:    Displays current temperature, conditions, and location.
* Air Quality Monitoring:        Tracks CO2, PM10, PM2.5, O3, and SO2.
* Multi-City Support:            Quick-select menu for comparing data across multiple cities.
* Detailed Metrics:              Shows Wind Speed, Pressure, UV Index, Humidity, Precipitation, and Visibility.
* Interactive Charts:            Includes a bar chart for Rain Chance and a line graph for Temperature Trends.
* Extended Forecast:             7-day outlook with weather icons and sun cycle (Sunrise/Sunset) tracking.

## 🎯 Project Overview

### Business Problem
Organizations operating across multiple regions often struggle with fragmented environmental data. Tracking shifting weather patterns and hazardous air quality metrics (such as PM2.5 or CO2) across disparate platforms leads to reactive, rather than proactive, decision-making and ensures compliance with health and safety regulations related to air pollution.

### Goal of the Dashboard
The objective is to consolidate real-time atmospheric and air quality API data into a single, automated interactive view. It aims to empower decision-makers—from operational managers to environmental researchers—with immediate access to multi-city climate trends, enabling rapid, data-backed planning and forecasting without the need for manual data gathering.

### Walkthrough of Key Visuals
* City Navigation Slicers: Located at the top, allowing users to seamlessly filter and compare data across major locations like Pune, Jaipur, and Kolkata.
* Environmental Health KPIs: The left panel tracks critical air quality indicators, including PM 10, PM 2.5, CO2, and SO2, providing an immediate snapshot of local pollution levels.
* Core Atmospheric Metrics: The top-center section displays immediate, granular data points such as Wind Speed, UV Index, Humidity, and Visibility.
* Precipitation & Temperature Trends: The central bar chart visualizes the daily rain probability, while the bottom line graph maps the 7-day temperature forecast, illustrating upcoming weather shifts at a glance.
* Sun Cycle Tracker: The right-side panel displays precise Sunrise and Sunset times to assist with daylight-dependent planning.

### Business Impact & Insights
* Risk Mitigation & Safety: Monitoring high air pollution markers (like elevated PM 2.5) allows organizations to ensure health compliance for outdoor workers or adjust facility HVAC systems accordingly.
* Operational Efficiency: Logistics, agriculture, and supply chain teams can leverage the 7-day temperature and rain probability trends to reroute deliveries, protect inventory, or reschedule outdoor operations.
* Automated Reporting: By utilizing Power Query to connect directly to an external API, the dashboard eliminates manual data entry. This saves significant time and ensures leadership always bases decisions on the freshest possible data.

  
## 📸 Sneak Peek <img width="2321" height="1314" alt="Climate and More" src="https://github.com/user-attachments/assets/5f50c0d2-f3cb-4459-a733-92b123935e29" />

[Dashboard](https://github.com/piyushsoniii/Climate-and-More/blob/main/Climate%20and%20More.png)
