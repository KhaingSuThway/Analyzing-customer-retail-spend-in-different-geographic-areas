# UK Customer Spend Analysis Project

## Overview
This data analysis project examines customer spending patterns across different geographic regions in the United Kingdom for ProWidget Systems, a B2B retailer. The analysis focuses on comparing spending volumes between London-based customers and those in other UK regions to identify market opportunities and optimize business strategy.

## Business Objectives
- Analyze and compare customer spending patterns between London and other UK regions
- Identify underserved cities with growth potential
- Determine the geographical distribution of the customer base
- Provide data-driven insights for strategic business decisions

## Data Sources
The analysis utilizes two primary data sources:
- Customer Address Dataset (.csv) - Contains customer location data and total spending information
- UK Cities Reference Dataset (.csv) - Comprehensive list of UK cities for geographical mapping

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib/Seaborn for data visualization
- Jupyter Notebooks for analysis documentation

## Project Structure
```
├── data/
│ ├── customer_address.csv
│ ├── uk_cities.csv
│ └── cleaned_customers_data.csv
├── notebooks/
│ └── analysis.ipynb
├── README.md
└── requirements.txt
```

## Installation and Setup
1. Clone this repository
```bash
git clone https://github.com/yourusername/Analyzing-customer-retail-spend-in-different-geographic-areas.git
```
2. Install required dependencies
```bash
pip install -r requirements.txt
```

## Analysis Approach
1. Data Cleaning and Preprocessing 
   - Address standardization 
     * Case normalization
     * Line structure analysis
     * Address pattern identification
   - Geographic location validation
     * City extraction strategy development
     * UK cities reference data integration
     * Reclassification of London addresses using postal codes
     * Manual update of Hull addresses
   - Spending data normalization 
     * Basic statistics analysis completed
     

2. Exploratory Data Analysis 
   - Regional spending distribution
   - Customer concentration analysis
   - City-wise market penetration



## Current Status
- Completed initial data loading and basic cleaning
- Implemented address standardization
- Developed city extraction strategy
- Performed basic spending analysis
- Reclassified London addresses using postal codes
- Updated Hull addresses manually
- Completed geographic location validation
- Pending spending data normalization









