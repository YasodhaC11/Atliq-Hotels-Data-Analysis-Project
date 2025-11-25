# Atliq-Hotels-Data-Analysis-Project

AtliQ Hotels Data Analysis Project

A comprehensive data analysis project focused on understanding the performance, revenue patterns, booking behavior, and operational insights of AtliQ Hotels, a fictional hotel chain from Codebasics’ Data Analytics Challenge.

🌟 1. Project Overview

This project analyzes multiple dimensions of hotel performance such as revenue, occupancy, booking trends, cancellations, customer ratings, and booking platforms.
The goal is to provide actionable business insights and develop a strong analytical narrative using real-world datasets.

📁 2. Datasets Used

The project contains five datasets:

File Name	Description
fact_bookings.csv	Booking-level data (check-in/out, revenue, guests, status)
fact_aggregated_bookings.csv	Daily aggregated bookings with room and property details
dim_hotels.csv	Hotel-level information including city and category
dim_rooms.csv	Room category and capacity information
dim_date.csv	Date dimension (day, week, month, year, weekend flag)
🧼 3. Data Cleaning & Preprocessing

Key cleaning steps performed:

Removed invalid entries (e.g., negative guest count).

Handled outliers in revenue values.

Standardized date formats using datetime.

Merged fact and dimension tables to build a unified analytical dataframe.

Filtered inconsistent room category data for accurate revenue analysis.

🧠 4. Project Workflow

Import data and explore structure

Clean and preprocess inconsistent values

Merge datasets using keys (date, room_id, hotel_id)

Perform Exploratory Data Analysis (EDA)

Group results by city, property, room type, month, and platform

Visualize revenue, occupancy, ratings, and booking patterns

Generate business insights
