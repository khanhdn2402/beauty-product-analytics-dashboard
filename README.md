# Project Name: Beauty Prodcut Analytics Dashboard (Tableau Visualization Project)
## 1. Overview
**Beauty Product Analytics Dashboard** is a data-driven project aimed at exploring key factors that influence consumer behavior in the beauty and cosmetics market. Using a dataset of skincare and makeup products, this project analyzes product popularity, brand performance, rating distribution, and customer loyalty indicators.

By leveraging Tableau to visualize trends, relationships, and category-level insights,this project provides valuable information for beauty brands, marketers, product managers, and data analysts interested in understanding how consumers interact with cosmetic products.
## 2. Project Objectives
### 🛍️ Identify Popular Product Categories
Analyze which beauty categories receive the highest consumer engagement based on review volume.
### 🏷️ Evaluate Brand Performance
Compare top-performing brands to understand which companies generate the most customer attention and satisfaction.
### ⭐ Analyze Rating vs. Popularity Patterns
Investigate whether products with higher ratings truly receive more reviews and higher engagement.
### 💄 Compare Luxury vs. Non-Luxury Brands
Determine whether luxury cosmetics genuinely outerform drugstore products in customer ratings.
### 🧴 Measure Skincare vs. Makeup Loyalty
Convert usage frequency into a usage score (Daily = 5 ... Monthly = 2) to quantify customer loyalty across product types.
## 3. Workflow and Methodology
### Data Preparation
The raw dataset was cleaned and standardlized using Tableau and Python, including:
* Removing duplicates
* Normalizing category and brand names
* Mapping usage frequency to a numeric score
* Assigning brand tiers (Luxury vs. Non-Luxury)
* Creating rating bins for trend analysis

This ensured consistency and usablity for downstream visualization.
### Feature Engineering
Additional fields were created to enrich the analysis:
* **Brand Tier** (Luxury/Non-Luxury/Other)
*  **Category Type** (Skincare/Makeup/Other)
*  **Usage Score** (numeric loyalty indicator)
*  **Rating Bins** (for visual grouping)
### Exploratory Data Analysis (EDA) in Tableau
Through Tableau, each key question was analyzed using:
* Bar charts
* Box plots
* Scatter plots
* Trendlines
* Summary dashboards

These visuals provided insight into petterns, variance, abd clustering behaviors across the beauty market.
### Key insights Extraction
The final step involved synthesizing the findings from all five visualizations to form actionable insights about customer behavior, product performance, and brand strategy.
## Key Takeaways
### ⭐ Most Popular Product Categories
Serum, Face Oil, Mascara, and Highlighter receive the highest total review counts, indiacting strong consumer demand and daily-use relevance.
### ⭐ Top-Performing Brands
Brands such as NARS, Milk Makeup, KVD Beauty, Glossier, and Kiehl's show consistenly high engagement.

These brands dominate review volume, suggesting effective marketing and strong brand loyalty.
### ⭐ Ratings Do Not Gurantee Popularity
Products with ratings between **3.6 and 4.2** tend to have the highest review counts.

Perfect 5.0 products are **not** the most popular - suggesting visibility, reputation, and social influence matter more than rating alone.
### ⭐ Luxury vs. Non-Luxury Ratings
* Luxury products show **higher viriability** - some very high ratings but also more low-rated outliers
* Non-luxury products have **more consistent** ratings overall
* Average ratings between the two tiers are suprisingly close

This suggests luxury brnding does not always translate to superior customer satisfaction.
### ⭐ Skincare vs. Makeup Loyalty
Customer loyalty (Usage Score) is nearly identical:
* Skincare: **3.50**
* Makeup: **3.49**

Customers appear equally committed to both categories, using each category consistenly on weekly and daily cycles.
