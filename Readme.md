# Zomato Data Analysis

## Overview

This project analyzes Zomato restaurant data to gain insights into restaurant ratings, cuisines, locations, and price distributions. The goal is to help users, businesses, and food enthusiasts make data-driven decisions based on restaurant trends and patterns.

## Dataset

The dataset used in this analysis is `zomato.csv`, which contains extensive information about various restaurants. Key attributes in the dataset include:

- **Restaurant names**: Identifies different restaurants.
- **Locations**: Geographical details of the restaurant locations.
- **Ratings**: User ratings for different restaurants.
- **Cuisines offered**: Types of cuisines served at each restaurant.
- **Cost for two**: The approximate cost for two people dining at the restaurant.
- **Online delivery options**: Indicates whether the restaurant offers online delivery.
- **Table booking availability**: States whether table reservations are available.
- **Reviews and votes**: Customer feedback and votes on different restaurants.

## Libraries Used

The analysis is performed using Python and several essential libraries:

- `pandas`: For data manipulation, cleaning, and analysis.
- `numpy`: For numerical computations and handling missing values.
- `matplotlib`: For creating static visualizations and graphs.
- `seaborn`: For enhanced data visualization and analysis.

## Data Analysis Steps

1. **Data Loading:** Read the dataset using Pandas to understand its structure.
2. **Data Exploration:** Inspect dataset attributes, check for missing values, and identify duplicates.
3. **Data Cleaning:** Handle missing values by imputation or removal, remove duplicates, and normalize categorical data.
4. **Exploratory Data Analysis (EDA):**
   - Analyzing the distribution of ratings to understand user preferences.
   - Identifying the most popular cuisines across different locations.
   - Evaluating the average cost for two in different cities and localities.
   - Examining restaurant density across various locations.
   - Analyzing the correlation between restaurant ratings and pricing.
5. **Visualizations:** Generate meaningful charts and graphs using Matplotlib and Seaborn, including:
   - Bar charts for top-rated restaurants and popular cuisines.
   - Heatmaps to show location-based restaurant density.
   - Box plots to analyze pricing distributions.
   - Histograms to understand rating distributions.

## Key Insights

- High-rated restaurants tend to specialize in certain cuisines that attract more positive reviews.
- Restaurant pricing varies significantly across different geographical locations.
- Some cities or neighborhoods have a high density of restaurants offering similar cuisines, leading to intense competition.
- Online delivery options and table booking availability impact customer preferences and restaurant ratings.

## How to Use

1. Install required dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn
   ```
2. Download the dataset (`zomato.csv`) and place it in the working directory.
3. Open the Jupyter Notebook and execute the cells sequentially to explore the analysis.

## Conclusion

This analysis provides valuable insights into restaurant trends, pricing variations, and customer preferences. Businesses in the food industry can leverage these insights to optimize their strategies, enhance customer experience, and improve overall decision-making in restaurant management and marketing.

## Author

**Lakshay Bhardwaj**

