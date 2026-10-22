# Uber / Taxi Trip Data Analysis Using Apache Spark

A web-based analytics project that processes taxi trip records and displays useful insights through an interactive dashboard.

## Project Overview

This project helps users explore taxi trip data, including trip counts, fares, distances, pickup locations, and revenue trends. It combines a frontend dashboard, a backend API, and a data-processing layer.

## Problem Statement

Taxi trip datasets may contain many records, making manual analysis time-consuming. This project processes and summarizes the records so that useful patterns can be viewed through charts and summary statistics.

## Objectives

- Load and clean taxi trip data from CSV files.
- Handle duplicate and invalid records.
- Calculate trip counts, revenue, average fare, and distance.
- Analyze trip activity by hour and pickup location.
- Visualize daily revenue and other statistics.
- Filter trip records and export selected data as CSV.

## Technologies Used

- **Frontend:** React, TypeScript
- **Backend:** Python, Flask, Flask-CORS
- **Data Processing:** Apache Spark, PySpark
- **Visualization:** Chart.js
- **Input Data:** CSV files
- **Deployment:** Replit

## System Architecture

CSV Dataset → PySpark Data Processing → Flask REST API → React Dashboard

The backend provides API endpoints for trip summaries, trip records, hourly analytics, pickup-location analysis, daily revenue, and CSV export.

## Main Features

- Dashboard with summary metrics
- Trip and revenue analysis
- Hourly trip activity
- Pickup-location comparisons
- Date and location filters
- Dataset selection
- CSV export

## Live Demo

https://uber-taxi-trip-data-analysis--24modanip.replit.app/

## Data and Implementation Notes

The application uses CSV datasets, including a supplied dataset and a synthetic teaching dataset. Synthetic data is for demonstration and should not be interpreted as actual Uber operational data.

The documented Spark setup runs in local mode. A distributed Hadoop cluster and Cassandra integration are not claimed as implemented features.

## Future Enhancements

- Cassandra integration for persistent storage
- Distributed Spark processing
- Map-based trip visualizations
- Demand forecasting
- Automated dataset updates

## Academic Project

Developed as a university mini project to demonstrate data analytics, backend API development, frontend visualization, and Apache Spark processing.
