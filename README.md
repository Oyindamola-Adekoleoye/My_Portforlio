🚦 Road Accident Analysis Dashboard
<img width="1518" height="721" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/5ea89423-1ff4-4abc-a7da-d8ca0c06b75d" />

📖 The Data Story

Road safety is a critical issue worldwide. With thousands of incidents occurring annually, raw data can easily become overwhelming. The goal of this project was not just to count accidents, but to understand why, where, and when they happen, enabling stakeholders to make data-driven decisions for safer roads.

Using a dataset spanning two years (2021 & 2022), I built an interactive Excel dashboard to identify trends in casualties based on road types, lighting conditions, and vehicle involvement.

🔍 Key Insights Uncovered

Severity Distribution: While the vast majority of casualties are "Slight" (~82%), the dashboard highlights a critical 2.28% of cases that are "Fatal," allowing investigators to drill down specifically into those high-priority incidents.

Road Type Impact: "Single" carriageways account for the highest volume of casualties (approx. 109k in the full dataset), significantly outweighing dual carriageways or roundabouts.

The "Car" Factor: Passenger cars account for ~80% of all casualties, suggesting that safety campaigns should prioritize driver education over other vehicle types.

Environmental Context: The dashboard reveals that while most accidents happen in daylight, a significant portion occurs in the dark, and road surface conditions (Wet vs. Dry) play a measurable role.

🛠️ Technical Workflow

This project demonstrates an end-to-end data analysis workflow entirely within Microsoft Excel:

Data Cleaning & ETL: * Handled missing values and standardized categorical data (e.g., unifying "Urban" vs. "Rural" labels).

Parsed date fields to allow for granular monthly and yearly comparison.

Data Modeling:

Created relationships between accident details, vehicle types, and casualty severity.

Utilized Pivot Tables to aggregate millions of rows of data efficiently.

Dashboard Design & UX:

Interactive Slicers: Added filters for "Urban/Rural," "Year," and "Light Conditions" to make the report dynamic.

Visual Hierarchy: Used KPIs (Key Performance Indicators) at the top for immediate context (Total Casualties, Fatal %).

Trend Analysis: implemented a line chart to compare monthly trends between 2021 and 2022 side-by-side.

📊 Dashboard Features

Feature

Function

KPI Banners

Instant view of Fatal, Serious, and Slight casualty counts.

Trend Lines

Compares 2021 vs. 2022 performance to spot seasonality (e.g., spikes in specific months).

Donut Charts

Visualizes the percentage breakdown of severity and vehicle type.

Dynamic Filtering

Allows the user to toggle between Rural and Urban settings or Day/Night conditions instantly.

Custom Icons

Visual representation of vehicle types (Bus, Car, Bike) for faster cognitive processing.

🚀 How to Use

Download: Clone the repository and open the .xlsx file.

Interact: Use the slicers on the right-hand panel ("Filters") to segment the data.

Try selecting "Rural" to see how fatality rates change compared to "Urban" areas.

Select "Wet" road conditions to see if accident severity increases.

Analyze: Hover over the charts to see specific data points for each month.

👨‍💻 About Me

I am a Data Analyst passionate about uncovering stories hidden within datasets. This project showcases my ability to create professional, client-ready business intelligence tools using Excel.
