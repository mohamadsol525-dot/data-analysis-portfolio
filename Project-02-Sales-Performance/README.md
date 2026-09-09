# Project 02 — Sales Performance & Business Insights

## Overview

This project analyzes the sales performance of a food manufacturing company over a three-year period from **1399 to 1401**.

The analysis follows a top-down structure, moving from overall sales performance to product groups, individual products, sales channels, sales representatives, and customers. The goal is to identify the main drivers of growth, decline, and business concentration.

## Business Objective

The main business question is:

> **Where is sales performance improving, where is it declining, and which parts of the business are responsible for these changes?**

To answer this question, the analysis evaluates sales using multiple complementary indicators rather than relying on revenue alone.

## Analytical Framework

The analysis follows the structure:

**Overall Sales → Product Groups → Products → Sales Channels → Sales Representatives → Customers**

This approach makes it possible to move from identifying major sales anomalies to investigating their underlying sources.

## Key Performance Indicators

Sales performance is evaluated using four main indicators:

- **Sales Quantity**
- **Sales Weight**
- **Sales Revenue (IRR)**
- **Sales Revenue (USD)**

Using multiple indicators helps distinguish genuine changes in sales volume from changes that may primarily reflect price increases or inflation.

## Key Findings

### 1. Winter 1401 was the major sales deviation

Winter 1401 was identified as the main departure from the company's historical sales pattern, with declines in sales quantity, sales weight, and dollar revenue.

### 2. Autumn was the strongest and most consistent season

Autumn was the only season that showed continuous growth across all three years and across all four sales indicators.

### 3. Revenue growth alone does not always indicate real sales growth

In several periods, growth in IRR revenue occurred without corresponding growth in physical sales volume or dollar revenue. This highlights the importance of evaluating financial and physical indicators together.

### 4. Non-sesame products were a major source of the 1401 decline

Although sesame products remained the larger product group, non-sesame products contributed disproportionately to the decline in sales weight and sales quantity in 1401.

### 5. Sales concentration increased across multiple dimensions

The analysis identified concentration risk across several layers of the business, including:

- Products
- Sales channels
- Sales representatives
- Customers

### 6. B2B remained the dominant sales channel

B2B was the primary sales channel throughout the analyzed period, while its share of total dollar sales increased over time.

## Product Analysis

The analysis compares the performance of **sesame** and **non-sesame** product groups and then moves deeper into individual product categories.

Products are evaluated using dollar sales across annual, seasonal, and monthly periods to identify:

- Top-performing products
- Growth drivers
- Declining products
- Changes in product rankings
- Product concentration and dependency

The analysis also highlights cases where the growth of one product changes the ranking of another product, as well as situations where dependence on a single product increases business risk.

## Sales Channel Analysis

Sales performance is examined across four main channels:

- **B2B**
- **Retail Store**
- **Online**
- **Other Channels**

The analysis evaluates both the scale and stability of each channel and investigates whether changes in overall sales originate from specific channels or reflect broader business conditions.

## Sales Representative & Customer Analysis

The analysis goes beyond simply identifying the largest sales representatives and customers.

It evaluates:

- Sales concentration
- Stability over time
- Changes in ranking
- Customer purchasing behavior
- Relationships between customers, sales representatives, and sales channels

An important finding is that a large customer is not necessarily a stable customer. Customer value therefore needs to be evaluated not only by purchase size, but also by persistence and repeat purchasing behavior.

## Business Insights

The overall analysis suggests that the company's main risk is not simply a decline in total sales, but rather **concentration across multiple layers of the business**.

High dependence on specific products, channels, sales representatives, and customers means that a change in any one of these areas can have a significant impact on overall performance.

The findings highlight the importance of:

- Product diversification
- Customer retention
- Channel development
- Reducing dependence on individual products
- Strengthening stable sales relationships

## Visual Highlights

### Cumulative Monthly Sales

![Cumulative Monthly Sales](./images/Cumulative%20Monthly%20Sales.png)

This visualization helps identify when annual sales performance begins to diverge across the three-year period and highlights major points of acceleration or decline.

### Top-Performing Sesame and Non-Sesame Products

![Top-Performing Products](./images/Top-Performing%20Sesame%20and%20Non-Sesame%20Products%20by%20Sales%20Revenue%20(USD)%201399.png)

This analysis highlights the strongest products within the sesame and non-sesame categories and provides a view of product-level sales concentration.

### Non-Sesame Product Sales by Season and Year

![Non-Sesame Product Sales](./images/Comparison%20of%20Non-Sesame%20Product%20Sales%20Methods%20by%20Season%20and%20Year%20Based%20on%20Dollar%20Sales.png)

This visualization examines how non-sesame product sales vary across seasons and years and helps identify periods of stronger or weaker performance.

### Summer 1400 Sales Performance

![Summer 1400](./images/1400%20-%20Summer.png)

This visualization provides a focused view of seasonal sales performance during summer 1400.

## Analytical Skills Demonstrated

- Exploratory Data Analysis
- Sales Performance Analysis
- Trend Analysis
- Year-over-Year Comparison
- Seasonal Analysis
- Product Portfolio Analysis
- Sales Channel Analysis
- Customer Analysis
- Sales Representative Analysis
- Sales Concentration Analysis
- Business Insight Generation
- Data Visualization

## Tools

**JMP · Exploratory Data Analysis · Statistical Analysis · Data Visualization**

## Project Scope

**Period:** 1399–1401  
**Industry:** Food Manufacturing  
**Focus:** Sales Performance & Business Analysis

## Full Report

[View the Full Project Report (PDF)](./Project-02-Report.pdf)

## Author

**Mohammad Amin Mohammadi Ahoui**

## Repository Structure

```text
Project-02-Sales-Performance/
│
├── README.md
├── Project-02-Report.pdf
│
└── images/
    ├── 1400 - Summer.png
    ├── Comparison of Non-Sesame Product Sales Methods by Season and Year Based on Dollar Sales.png
    ├── Cumulative Monthly Sales.png
    └── Top-Performing Sesame and Non-Sesame Products by Sales Revenue (USD) 1399.png
