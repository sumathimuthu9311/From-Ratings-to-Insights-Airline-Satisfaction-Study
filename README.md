# From-Ratings-to-Insights-Airline-Satisfaction-Study
To transform raw airline passenger satisfaction survey data into a structured data model in Excel, enabling interactive dashboards and deeper analysis. The goal is to separate facts (measurable events) from dimensions (descriptive categories) so that slicers, PivotTables, and charts can be connected seamlessly.


# Accident-Pattern-and-Risk-Intelligence-System-in-India-2018-2020-

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

## 📊 Project Overview

To transform raw airline passenger satisfaction survey data into a structured data model in Excel, enabling interactive dashboards and deeper analysis. The goal is to separate facts (measurable events) from dimensions (descriptive categories) so that slicers, PivotTables, and charts can be connected seamlessly.

## 🗂️ Data Source

Government road accident reports (India)
Public datasets on road safety(www.indiadataportal.com)


## 🛠️ Tools & Technologies
Tools :
Excel

## 🧹 Data Cleaning & Preparation
Detail the steps you took to make the data usable:
1. Handled missing values and duplicates.
2. Formatted data types.
3. Created new calculated columns

## Connections in Data Model
•	In Excel’s Power Pivot / Data Model, link:
o	fact_airline.Class_ID → class_dim.Class_ID
o	fact_airline.Rating_ID → rating_dim.Rating_ID
o	fact_airline.Customer_Type_ID → cus_type_dim.Customer_Type_ID
o	fact_airline.Travel_ID → travel_dim.Travel_ID
•	This creates a star schema: one central fact table surrounded by dimension tables


## 💡 Key Insights

- **Insight 1:** o	Business and personal travelers rated food, cleanliness, and seat comfort highly.
o	In-flight entertainment, Wi-Fi, and flight service had more satisfied ratings.
o	Seniors and young passengers showed higher dissatisfaction compared to adults and kids.
o	Economy class passengers were more dissatisfied due to delays.
o	First-time travelers had higher dissatisfaction with baggage handling.
o	Male passengers showed greater dissatisfaction across services compared to females
- **Insight 2
- o	If delays continue, economy passengers will remain the least satisfied group.
o	Long-distance travelers are more likely to give higher satisfaction ratings, so improving long-haul services could boost overall ratings.
o	Online boarding satisfaction suggests digital service improvements will continue to raise ratings.

## 🚀 Recommendations
o	Reduce baggage handling issues for first-time travelers to improve their experience.
o	Focus on minimizing departure and arrival delays, especially in economy class.
o	Enhance food and cleanliness standards further, since they strongly influence satisfaction.
o	Target service improvements for seniors and younger passengers, who show higher dissatisfaction.
