# DPR Camping Reservations Analysis (2020)

## Overview
This project analyzes the **2020 DPR Camping Reservations** dataset to uncover insights into booking patterns, such as the number of bookings per month, facility usage, and other trends related to camping reservations. The analysis uses Python and its popular libraries, including Pandas, Matplotlib, and Seaborn.

## Dataset
The dataset used for this project contains camping reservation data for various parks managed by the Department of Parks and Recreation (DPR) for the year 2020. Key features in the dataset include:
- **ParkName**: Name of the park
- **FacilityName**: The facility within the park where the reservation is made
- **ArrivalDate**: Date of arrival for the reservation
- **UseType**: Type of reservation (e.g., nightly)
- **VehicleLength**: Length of the vehicle (relevant for RV and camping sites)
- **IsTentSite**: Whether the reservation is for a tent site
- **IsRvSite**: Whether the reservation is for an RV site

## Goals of the Project
The aim of this analysis is to:
1. Provide insights into **booking trends** by month.
2. Explore **facility usage** and determine the most popular types of bookings.
3. Analyze the impact of **vehicle type** and **site preference** (tent vs. RV).

## Key Insights
1. **Top 3 Months with Highest Bookings**:
   - **July**: 69,102 bookings
   - **August**: 66,111 bookings
   - **October**: 48,759 bookings
2. **Bookings by Use Type**:
   - Currently, the dataset only includes **Nightly** bookings. There are no other use types (e.g., weekly or monthly) found in the dataset.
   
## Libraries and Tools Used
- **Python** (version 3.7+)
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization (graphs and charts)
- **Seaborn**: Statistical data visualization

## Requirements
To run this analysis locally, ensure that the following libraries are installed:
```bash
pip install pandas matplotlib seaborn
