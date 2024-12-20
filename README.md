# Home Sales Analysis Project

## Overview
This project analyzes home sales data using SparkSQL to determine key metrics about home sales. The analysis includes creating temporary views, partitioning data, and comparing query performance with cached and uncached data.

## Features
- Utilizes SparkSQL for data analysis
- Implements data caching and uncaching
- Performs partitioned data analysis
- Calculates various home price metrics
- Compares query runtime performance

## Dependencies
- PySpark
- Python
- Jupyter Notebook

## Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/Home_Sales.git
cd Home_Sales
```

2. Ensure you have PySpark installed in your environment.

## Data Analysis Tasks
The project performs the following analyses:

1. Average price calculations for:
   - Four-bedroom houses by year
   - Three-bedroom, three-bathroom homes by build year
   - Homes with specific criteria (3 bed, 3 bath, 2 floors, ≥2000 sqft) by build year
   - Homes by view rating (with average price ≥$350,000)

2. Performance optimization techniques:
   - Data caching
   - Query runtime comparison (cached vs. uncached)
   - Data partitioning by date built
   - Parquet format implementation

## File Structure
- `Home_Sales.ipynb`: Main Jupyter notebook containing analysis
- `home_sales_revised.csv`: Input data file
- `README.md`: Project documentation

## Usage
1. Open `Home_Sales.ipynb` in Jupyter Notebook
2. Execute cells in sequence to:
   - Import required PySpark functions
   - Load and process data
   - Create temporary tables
   - Run analysis queries
   - Compare performance metrics

## Query Performance Analysis
The project includes runtime comparisons for queries using:
- Uncached data
- Cached data
- Partitioned parquet data

## Data
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
