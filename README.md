

# Hospitality Market Analysis in Power BI

## Project Overview
This project analyzes Airbnb listings and review data across multiple cities to identify pricing patterns, listing volume, guest ratings, and review trends.

The goal was to build a business-focused Power BI dashboard that connects data modelling, DAX calculations, and visual analysis to support decision-making.

## Business Questions
- Which cities have the highest listing volume?
- Which cities have the highest average prices?
- How do guest ratings compare across markets?
- Which major property types are priced highest?
- Do higher-priced property types receive better guest ratings?
- How are reviews changing month over month and year over year?

## Data Model

The model contains three main tables:

- Listings
- Reviews
- Date

Relationships:
- Listings[listing_id] → Reviews[listing_id]
- Date[Date] → Reviews[date]

![Data Model](01-data-model.png)

## Dashboard Pages

### 1. Market Overview

This page summarizes:
- Total Listings
- Average Price
- Average Rating
- Total Reviews
- Unique Reviewers
- Average Price by City
- Listings by City
- Average Rating by City

![Market Overview](02-executive-overview.png)

### 2. Guest Experience & Property Analysis

This page compares the most common property types using:
- Average Rating
- Average Price
- Listing Volume
- Price vs Rating analysis

Key insight:

- Higher average price does not consistently correspond to higher guest ratings.

![Guest Experience & Property Analysis](03-guest-experience.png)

### 3. Review Trends & Time Intelligence

This page uses a dedicated Date table and DAX time-intelligence measures to analyze review growth.

For the selected period October 2019:
- MoM Review Growth: 6.60%
- YoY Review Growth: 39.06%

![Time Intelligence](04-time-intelligence.png)

## Skills Demonstrated

- Power BI
- Power Query
- DAX
- Data modelling
- Table relationships
- Time intelligence
- KPI design
- Top N analysis
- Business analysis
- Data visualization
- Insight generation
