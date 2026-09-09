# Project 01 — Bike Rental Data Analysis

## Project Overview

This project analyzes two full years of bike-sharing data from **2011 to 2012** using **JMP** to identify customer behavior patterns, demand drivers, and business insights.

The analysis focuses on two customer segments — **Casual** and **Registered** — and examines how their behavior changes across time, weekdays, seasons, weather conditions, and extreme events.

## Business Question

**Do Casual and Registered users behave as one customer segment, or do they represent two distinct behavioral groups?**

## Analytical Framework

The analysis follows a structured exploratory data analysis approach, moving from overall customer behavior to temporal patterns, environmental factors, and extreme events.

The main analytical areas include:

- Customer segmentation
- Annual growth analysis
- Correlation analysis
- Hourly demand patterns
- Working-day vs. non-working-day behavior
- Weekly and holiday analysis
- Seasonal and monthly trends
- Weather-demand relationships
- Extreme weather event analysis
- Long-term growth patterns

## Key Performance Indicators

The analysis evaluates demand using:

- Casual Users
- Registered Users
- Total Demand
- Average Demand
- Customer Segment Share
- Correlation and Regression Metrics

## Key Findings

- Casual and Registered demand showed a relatively weak relationship, with **R² = 0.156**, indicating substantially different demand patterns.
- Registered users grew by approximately **68%**, compared with **50% growth for Casual users** between 2011 and 2012.
- Casual users' share of total demand declined from **18.1% to 17%**, despite strong absolute growth.
- Registered users showed strong commuting-oriented peaks around **08:00 and 17:00**, particularly on working days.
- Temperature was the strongest weather-related variable associated with demand, with correlations of approximately **0.54** for both customer groups.
- During Hurricane Sandy, total daily demand fell from **8,090 to 22 trips**, representing a **99.7% decline**.

## Visual Highlights

### 1. Casual vs. Registered Relationship

![Casual vs. Registered](./images/Casual%20vs.%20Registered.png)

### 2. Mean Casual & Registered by Year and Month

![Mean Casual & Registered by Year and Month](./images/Mean%20Casual%20%26%20Registered%20by%20Year%20and%20Month.png)

### 3. Mean Casual & Registered vs. Hour by Working Day

![Mean Casual & Registered vs. Hour by Working Day](./images/Mean%20Casual%20%26%20Registered%20vs.%20Hour%20by%20Working%20Day.png)

### 4. Mean Casual & Registered vs. Year

![Mean Casual & Registered vs. Year](./images/Mean%20casual%20%26%20registered%20vs%20yr.png)

## Business Insights

The analysis indicates that Casual and Registered users should not be treated as a single homogeneous customer segment.

Registered users demonstrate stronger commuting-oriented behavior, while Casual users show more flexible and leisure-oriented demand patterns.

These differences can support more targeted decisions in:

- Fleet allocation
- Customer segmentation
- Membership conversion
- Marketing strategy
- Operational planning under adverse weather conditions

## Analytical Skills Demonstrated

- Exploratory Data Analysis
- Customer Segmentation
- Trend Analysis
- Correlation Analysis
- Time-Based Analysis
- Seasonal Analysis
- Weather Impact Analysis
- Comparative Analysis
- Business Insight Generation
- Data Visualization

## Tools

**JMP · Exploratory Data Analysis · Statistical Analysis · Data Visualization**

## Project Scope

**Period:** 2011–2012  
**Industry:** Bike Sharing / Urban Mobility  
**Focus:** Customer Behavior, Demand Patterns & Business Insights

## Full Report

[View the Full Project Report (PDF)](./Project-01.pdf)

## Author

**Mohammad Amin Mohammadi Ahoui**

## Repository Structure

```text
Project-01-Bike-Rental/
│
├── README.md
├── Project-01.pdf
│
└── images/
    ├── Casual vs. Registered.png
    ├── Mean Casual & Registered by Year and Month.png
    ├── Mean Casual & Registered vs. Hour by Working Day.png
    └── Mean casual & registered vs yr.png
