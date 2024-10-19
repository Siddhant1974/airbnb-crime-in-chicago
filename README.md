
# Contributors
Siddhant Nayar
Dizhao Zhang (Project Manager)
Ching Hsuan Lin
Ruo-Rong Wang
Sai Nruthya Vaka
Siddharth Kant
## Project Overview
This project explores the correlation between crime rates in Chicago and Airbnb listings, examining how crime impacts neighborhood safety, housing prices, and overall Airbnb performance. The goal is to provide data-driven insights for Airbnb hosts, policymakers, and other stakeholders to promote neighborhood safety while managing the growth of Airbnb listings.

### Table of Contents
Introduction
Business Problem
Data Sources
Methodology
Findings
Visualization
Recommendations
How to Run the Code
#### Introduction
Crime is a persistent issue in Chicago and has significant implications for businesses, especially those in the hospitality sector. Airbnb listings located in neighborhoods with high crime rates may experience reduced bookings as potential guests may feel unsafe. This project aims to understand the correlation between crime rates and Airbnb listings, focusing on crime trends, listing density, and the types of crimes that most impact Airbnb performance.

## Business Problem
The study focuses on:

Investigating the relationship between Airbnb listings and crime rates across various Chicago neighborhoods.
Understanding how the increase in Airbnb listings affects local crime rates, neighborhood safety, housing prices, and police presence.
Providing actionable recommendations for policymakers and Airbnb hosts to improve neighborhood safety while managing the growth of short-term rentals.
### Data Sources
Airbnb Listings Data: Sourced from the Inside Airbnb website, containing detailed information on Airbnb listings, including property type, host characteristics, pricing, reviews, and location data.
Chicago Crime Data: Sourced from the City of Chicago Data Portal, which provides detailed records of reported crimes, including crime type, location, date, and whether arrests were made.
## Methodology
The analysis involved the following steps:

Data Collection and Cleaning: Airbnb listing data and Chicago crime data were cleaned to fill missing values. Missing longitude and latitude values in crime data were filled using median coordinates, while Airbnb data missing prices were predicted using linear regression.
Data Merging: The two datasets were merged based on geographic proximity using the Haversine formula, which calculates distances between Airbnb listings and crime incidents within a half-mile radius.
Analysis and Visualization: Trends in crime rates were analyzed and visualized to understand the distribution of different crime types, the correlation between crime and Airbnb performance, and neighborhood-specific insights.
## Findings
Crime Trends: Crime rates in Chicago fluctuated significantly over the years, with a dip in 2020 due to the COVID-19 pandemic and a resurgence in 2021 as cities reopened.
Crime Types: Theft was identified as the most common crime type affecting Airbnb listings, followed by battery and deceptive practices.
Neighborhood Insights: The Near North Side had the highest crime count, far exceeding other neighborhoods such as Lake View, Loop, and West Town.
Impact on Airbnb: Airbnb listings in high-crime areas tend to experience lower bookings and guest satisfaction, as safety concerns directly impact customer decisions.
## Visualization
Key visualizations include:

Trends in crime rates over the years.
Distribution of the most common crime types in Chicago.
Comparison of crime counts across top neighborhoods.
Analysis of Airbnb review scores versus prices.
Host response times across neighborhoods and crime types.
## Recommendations
Enhanced Safety Measures: Airbnb hosts in high-crime neighborhoods should implement additional safety measures (e.g., security systems) to boost guest confidence.
Policy Interventions: Policymakers should consider zoning regulations for Airbnb in areas with high crime rates and work on improving police response times.
Improved Guest Communication: Airbnb hosts should maintain high responsiveness to guest inquiries, as timely communication fosters a sense of security.
## How to Run the Code
Clone this repository to your local machine using:
bash
Copy code
git clone https://github.com/your-repo/airbnb-crime-analysis.git
Install the required Python dependencies using:
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks to explore the analysis, data cleaning, and visualization processes.
