# Airbnb Listings & Reviews — SQL Analysis

## Project Overview
SQL-based business analysis of 279,712 Airbnb listings and 5.3 million 
reviews across 10 global cities (Paris, New York, Sydney, Rome, 
Rio de Janeiro, Istanbul, Mexico City, Bangkok, Cape Town, Hong Kong).

## Tools Used
- SQLite (database engine)
- Python / Google Colab (environment)
- Pandas (data loading and display)

## Key Business Questions Answered
1. Which cities have the most listings and highest average prices?
2. What room types dominate the platform?
3. Which hosts manage the most properties (power hosts)?
4. Which city has the highest average guest satisfaction?
5. Which neighbourhoods in New York are most expensive?
6. Which listings have the most reviews?
7. Which highly-reviewed listings have below-average ratings?
8. What does month-over-month review growth look like over time?
9. What is the cumulative review growth across the platform?

## Key Findings
- Paris has the most listings (64,690) but Mexico City has the 
  highest guest satisfaction (avg rating: 94.8)
- The top host manages 627 listings — operating like a hotel chain
- Tribeca is New York's most expensive neighbourhood ($373 avg/night)
- Platform reviews grew from single digits in 2009 to millions by 2018
- Prices are in local currency per city — not directly comparable 
  without conversion (flagged as a data limitation)

## Skills Demonstrated
- Multi-table JOINs (listings + reviews)
- GROUP BY / HAVING for aggregations and filtering
- Subqueries for dynamic comparisons
- Window functions: ROW_NUMBER, DENSE_RANK, LAG, SUM OVER
- CTEs for readable multi-step logic
- Data cleaning decisions and null handling

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/airbnb-listings-reviews)
2. Open `Airbnb_SQL_Analysis.ipynb` in Google Colab
3. Upload both CSV files when prompted
4. Run all cells in order
