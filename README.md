# AMAZON-PRODUCT-REVIEW-CAPSTONE

Amazone Product Review Analysis Capstone Project.

## Project Overview

This project is part of the DSA Data Analysis Capstone, where I serve as a Junior Data Analyst at RetailTech Insights. The goal is to explore and analyze Amazon product and customer review data to generate actionable insights for product improvement, marketing strategies, and customer engagement.

Dataset: 1,465 rows × 16 columns of Amazon product and review data.

Tools Used: Microsoft Excel (Pivot Tables, Formulas, Dashboard), GitHub for portfolio hosting.

## Repository Structure 

## (Amazon-case-study.xlsx)[[Amazon case study Raw data.xlsx](https://github.com/user-attachments/files/21105616/Amazon.case.study.Raw.data.xlsx)
]         # (Main analysis and dashboard file)[[AMAZON-PRODUCT-REVIEW-ANALYSIS.xlsx](https://github.com/user-attachments/files/21105452/AMAZON-PRODUCT-REVIEW-ANALYSIS.xlsx)
]

### Case Study Instruction. 

## Objective:
Analyze Amazon product review data to answer specific business questions using Excel, and present findings in a dashboard.

### Analysis Tasks
 1. Average discount percentage by product category

 2. Number of products listed under each category

 3. Total number of reviews per category
 4. Products with the highest average ratings

5. Average actual price vs discounted price by category

 6. Products with the highest number of reviews

 7. Number of products with a discount of 50% or more

 8. Distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)

 9. Total potential revenue (actual_price × rating_count) by category

 10. Number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)

 11. Relationship between rating and level of discount

 12. Number of products with fewer than 1,000 reviews

 13. Categories with products having the highest discounts

 14. Top 5 products in terms of rating and number of reviews combined

 15. Final Task: Build an Excel dashboard using your cleaned dataset and pivot outputs.

### Analysis Approach.
##### 1. Data Cleaning
 - Checked for missing values and inconsistencies.

 - Ensured all numeric columns (prices, discount, ratings, review counts) were properly formatted.

 - Added calculated columns where needed (e.g., discount percentage, potential revenue).

##### 2. Exploratory Data Analysis (EDA)
 - Used Excel Pivot Tables to summarize data by category, price range, and rating.

 - Created helper columns for combined metrics (e.g., rating × rating count for top products).

 - Used filters and sorting to identify products meeting specific criteria.

##### 3. Visualization & Dashboard
 - Built a dashboard in Excel featuring:

 - Bar charts for product counts, average discounts, and average ratings by category.

 - Pie/donut charts for review distribution.

 - Scatter plots for rating vs. discount percentage.

 - Slicers for interactive filtering by category and price range.

## Key Insights
Highest Average Discount: [![pppppp](https://github.com/user-attachments/assets/642f90e7-b2f8-4310-9bfa-5b9097567276)
] with an average discount of 58%.

Most Listed Products: [![pp](https://github.com/user-attachments/assets/9af35dde-9c10-4b3e-8980-6209c1538aa7)
] has the highest number of products.

Most Reviewed Product: [![ppp](https://github.com/user-attachments/assets/643d5b64-8772-4958-a720-421f8143d0ae)
] with [14208406
![image](https://github.com/user-attachments/assets/b1c50997-7817-4e11-bc95-788863c6c999)
] reviews.

Highest Rated Product: [![pppp](https://github.com/user-attachments/assets/12d67d2b-d488-4af0-8dc0-6a925af5c9f8)
] with an average rating of [5].

Products with ≥50% Discount: [![p](https://github.com/user-attachments/assets/8729d212-ae92-4ca7-bd89-a761e1b1aeab)] products, mostly in [HomeImprovement
![image](https://github.com/user-attachments/assets/2b9661f2-33f5-4fca-9c2d-854960e7541c)
].

Potential Revenue: [Electronics
![image](https://github.com/user-attachments/assets/cae36aaa-164a-42b1-88e7-9610cd63662a)
]could generate up to ₹[ ₹ 91,323,918,321 
![image](https://github.com/user-attachments/assets/b51c8f95-fc2d-4ad5-93de-148b9513a624)
] in revenue.

 ## Dashboard Preview
(![Dashboard](https://github.com/user-attachments/assets/e1a74191-5808-404a-bbdb-169449103fb5)
)

 ## Methodology Details
###### Key Calculated Columns
 - Discount Percentage:
=(actual_price - discounted_price)/actual_price

 - Potential Revenue:
=actual_price * rating_count

 - Combined Score (for top products):
=rating * rating_count

 - Price Range Bucket:
Used Excel's IF function

### Pivot Table Examples
Category vs. Average Discount:
Rows: Category | Values: Average of Discount Percentage

Category vs. Product Count:
Rows: Category | Values: Count of Product ID

Category vs. Total Reviews:
Rows: Category | Values: Sum of Rating Count

Rating Distribution:
Rows: Rating | Values: Count of Product ID

## Recommendations
Focus marketing on categories with high discounts and high ratings.

Investigate categories with low ratings but high review counts for potential improvements.

Leverage top-performing products in promotions.

Monitor the impact of large discounts on ratings to avoid negative perceptions.


