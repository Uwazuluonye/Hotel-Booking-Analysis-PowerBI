# Hotel-Booking-Analysis-PowerBI
## Introduction
This project analyzes hotel booking data to uncover key insights into customer booking behavior, cancellation trends, and reservation patterns. Using Power BI, the project demonstrates the end-to-end process of data transformation, modeling, and preparation for visualization. The goal is to provide actionable insights for hotel managers to improve decision-making, optimize occupancy rates, and reduce booking cancellations.
## Problem Statement
The hospitality industry faces several operational challenges, such as:
- High booking cancellation rates.
- Seasonal fluctuations in demand.
- Dependence on specific booking channels.
- Understanding customer demographics and their impact on hotel occupancy.

This project aims to address the following questions:
- What factors contribute to booking cancellations?
- Which booking channels are most effective?
- How do customer lead times and demographics affect reservations?
- What patterns can be observed in hotel stays (weekend vs weekday, short vs long duration)?
## Data Sourcing
Dataset Name: Practice Hotel_Booking_Data.xlsx
Source: Provided as part of the project exercise.
Description: The dataset contains booking information such as reservation status, guest details, booking channels, stay duration, and cancellation records.
## Data Transformation and Cleaning
The dataset was transformed and cleaned in Power Query (Power BI) to ensure accuracy and usability:
- Removed duplicate records.
- Handled missing values by either imputing or removing them.
- Converted date fields into proper date formats.
- Standardized categorical values (e.g., booking channel names).
Created calculated columns such as:
- Stay Duration (number of nights).
- Total Guests (adults + children).
- Filtered irrelevant or outlier records for analysis.
## Data Modeling
The cleaned dataset was structured in Power BI:
- Established a fact table for bookings.
- Defined dimension tables (e.g., booking channels, guest types).
- Created relationships between fact and dimension tables.
Built DAX measures such as:
1. Average days in waiting 
2. Maximum days in waiting
3. Average booking changes 
4. Total booking where special request is greater than 0
5. Ratio of total bookings to total cancellations

6. Cancellation rate

