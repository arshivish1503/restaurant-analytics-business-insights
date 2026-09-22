# Restaurant Analytics & Business Insights

## Project Overview

This project analyzes **9,551 restaurant records** to identify patterns in cuisine preferences, pricing, customer ratings, engagement, geographic concentration, digital-service adoption, and restaurant-chain performance.

The analysis combines **exploratory data analysis, segmentation, correlation analysis, geographic analysis, and statistical testing** to translate restaurant data into actionable business insights.

## Business Questions

- Which cuisines and markets dominate restaurant supply?
- How are restaurants distributed across rating and price segments?
- How does price range relate to ratings and customer engagement?
- How widely are online delivery and table booking adopted?
- Does offering multiple digital services relate to higher customer engagement?
- Does restaurant-chain scale have a meaningful relationship with ratings?
- Which observed differences are statistically significant?

## Key Insights

- **North Indian, Chinese and Fast Food** are the most prevalent cuisines.
- **New Delhi, Gurgaon and Noida account for 80.39%** of restaurant records.
- **Price Range 1 and 2 represent 79.13%** of restaurants.
- Average rating increases from **3.24 in Price Range 1 to 3.89 in Price Range 4**.
- Online delivery is available at **25.69%** of restaurants, while table booking is available at **12.14%**.
- Restaurants offering both online delivery and table booking record the highest average engagement at **474.30 votes**.
- Restaurant-chain outlet count has only a **weak association with average rating (Spearman = 0.10)**.
- Among rated restaurants, votes and ratings show a **moderate positive association (r = 0.409)**.

## Analysis Areas

### 1. Restaurant & Cuisine Analysis
- Cuisine prevalence
- Cuisine combinations
- Cuisine-wise ratings
- Cuisine concentration

### 2. Geographic Analysis
- City-level restaurant concentration
- Geographic distribution
- Latitude and longitude-based mapping

### 3. Pricing & Customer Engagement
- Price-range distribution
- Price vs. rating
- Price vs. customer votes
- Price-segment service adoption

### 4. Digital Services
- Online delivery adoption
- Table booking adoption
- Combined service configurations
- Customer engagement by service configuration

### 5. Restaurant Chain Analysis
- Outlet count
- Chain-level ratings
- Customer votes
- Relationship between chain scale and performance

### 6. Statistical Analysis
- Pearson correlation
- Spearman correlation
- Kruskal-Wallis test
- Mann-Whitney U test
- Post-hoc pairwise analysis

## Tools & Technologies

**Python | Pandas | NumPy | Matplotlib | Seaborn | GeoPandas | SciPy | Google Colab**

## Repository Structure

```text
restaurant-analytics-business-insights/
│
├── data/
│   └── Dataset.csv
│
├── notebooks/
│   └── restaurant_analytics.ipynb
│
└── README.md
