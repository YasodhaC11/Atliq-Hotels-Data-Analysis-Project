# Atliq-Hotels-Data-Analysis-Project

A comprehensive data analysis project focused on understanding the performance, revenue patterns, booking behavior, and operational insights of **AtliQ Hotels**, a fictional hotel chain from Codebasics’ Data Analytics Challenge.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Project Workflow](#project-workflow)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)

## Project Overview
This project analyzes multiple dimensions of hotel performance such as revenue, occupancy, booking trends, cancellations, customer ratings, and booking platforms.
The goal is to provide actionable business insights and develop a strong analytical narrative using real-world datasets.

## Datasets
The project contains five datasets:
**fact_bookings.csv** -	Booking-level data (check-in/out, revenue, guests, status)
**fact_aggregated_bookings.csv** -	Daily aggregated bookings with room and property details
**dim_hotels.csv** -	Hotel-level information including city and category
**dim_rooms.csv** -	Room category and capacity information
**dim_date.csv** -Date dimension (day, week, month, year, weekend flag)

## Data Cleaning & Preprocessing
Key cleaning steps performed:
- Removed invalid entries (e.g., negative guest count).
- Handled outliers in revenue values.
- Standardized date formats using datetime.
- Merged fact and dimension tables to build a unified analytical dataframe.
- Filtered inconsistent room category data for accurate revenue analysis.

## Project Workflow
1.Import data and explore structure
2.Clean and preprocess inconsistent values
3.Merge datasets using keys (date, room_id, hotel_id)
4.Perform Exploratory Data Analysis (EDA)
5.Group results by city, property, room type, month, and platform
6.Visualize revenue, occupancy, ratings, and booking patterns
7.Generate business insights

## Installation
1. Clone the repository:
   ```bash
   git clone (https://github.com/YasodhaC11/Atliq-Hotels-Data-Analysis-Project.git)
   
## Project Structure
```Atliq-Hotels-Data-Analysis-Project/
├── datasets/                                    # Input datasets
│   ├── dim_rooms.csv
│   ├── new_data_august.csv
│   ├── dim_hotels.csv
│   ├── dim_date.csv
│   ├── fact_aggregated_bookings.csv
│   ├── fact_bookings.csv
├── Hospitality_Analysis.ipynb                  # Jupyter Notebook for analysis
├── requirements.txt                            # Project dependencies
└── README.md                                   # Project documentation

## Conclusion
This project showcases real-world hotel performance analysis using structured datasets.
The insights generated can help optimize revenue, enhance customer experience, and improve operational decision-making.
