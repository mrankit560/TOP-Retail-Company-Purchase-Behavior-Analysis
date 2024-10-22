# Walmart: Confidence Interval and CLT

## Project Overview
This project analyzes customer purchase behavior at Walmart during Black Friday, specifically focusing on the purchase amount in relation to gender and other demographic factors. The management team at Walmart Inc. seeks to understand if spending habits differ between male and female customers, and how various demographics influence purchasing decisions.

## Business Problem
The goal of this analysis is to provide insights into customer purchase behavior, specifically addressing the question: **Do women spend more on Black Friday than men?** The dataset contains transactional data from 100 million customers, with equal representation of male and female customers.

## Dataset Overview
The dataset used for this analysis contains transactional data of customers who purchased products from Walmart stores during Black Friday. The key features of the dataset are as follows:

- **Dataset Link**: [Walmart_data.csv](https://github.com/mrankit560/Walmart-Confidence-Interval-and-CLT/blob/main/walmart_data.csv)
- **User_ID**: User ID
- **Product_ID**: Product ID
- **Gender**: Sex of the user
- **Age**: Age in bins
- **Occupation**: Occupation (masked)
- **City_Category**: Category of the city (A, B, C)
- **StayInCurrentCityYears**: Number of years in the current city
- **Marital_Status**: Marital status
- **ProductCategory**: Product category (masked)
- **Purchase**: Purchase amount

## Key Metrics
- **Spending Patterns**: Assessed spending patterns by gender, age, marital status, and product category.
- **Gender Analysis**: 75% of customers were male, with males spending more than females.
- **Age Group Insights**: 
  - The 26-35 age group had the highest purchases at 39.92%.
  - The 36-45 age group accounted for 20% of purchases.
- **Product Preferences**: 
  - Product category 5 was the most popular, followed by categories 1 and 8.
- **Statistical Insights**: Married customers spent 8.8% less than unmarried customers.
- **Confidence Intervals**: 
  - Males spent between \$895,617 and \$955,070.
  - Females spent between \$673,254 and \$750,794.
- **Actionable Insights**: Suggested targeted marketing for the 26-35 age group, focusing on popular products and adjustments based on gender and marital status.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/walmart-confidence-interval-clt.git
