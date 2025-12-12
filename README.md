# Zomato Analysis Dashboard – Power BI
This project presents an analytical Power BI dashboard based on Zomato restaurant data. It highlights top-rated cuisines, best-performing restaurants, and service options such as dine-in, takeaway, and table booking availability.

## Project Overview
The dashboard provides insights into:
- Top-rated cuisines
- Top restaurants based on customer ratings
- Restaurants offering dine-in services
- Restaurants offering takeaway facilities
- Restaurants providing table booking options
- Cost and rating trends
- Location-based distribution of restaurants

## Data Preparation
Data cleaning and transformation were performed using Power Query:
- Removed duplicates
- Cleaned rating and cost fields
- Standardized cuisine names
- Converted service availability fields into Yes/No indicators

## Data Modeling
A structured data model was built consisting of:
- Fact table with restaurant-level data
- Dimension tables for cuisine, location, and services
- Relationships created to support interactive filtering

## DAX Calculations
Custom measures were created for:
- Average Rating
- Total Restaurants
- Restaurants with Dine-in
- Restaurants with Takeaway
- Restaurants with Table Booking
- Top Cuisines by Rating

## Key Insights
- Several cuisines consistently receive higher ratings.
- Most restaurants support takeaway compared to dine-in.
- Only a smaller segment offers table booking facilities.
- Certain locations have a higher concentration of high-rated restaurants.
- Cost does not always correlate directly with ratings.

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Excel/CSV Dataset
- GitHub

