# customer-shopping-behavior-analysis
Customer Shopping Behavior Analysis | Data Analytics Project | Python Pandas | SQL | Power BI Dashboard | Retail Analytics | Customer Segmentation | Business Intelligence

# 📊 Customer Shopping Behavior Analysis
## 📌 Project Overview
A comprehensive data analytics project analyzing 3,900 customer transactions to uncover spending patterns, customer segments, and product preferences. This end-to-end analysis provides actionable insights for strategic business decisions in retail optimization.

## 📁 Dataset
Source: Customer transaction data

Size: 3,900 rows × 18 columns

## Key Features:

Demographics (Age, Gender, Location, Subscription Status)

Purchase Details (Item, Category, Amount, Season, Size, Color)

Shopping Behavior (Discounts, Promo Codes, Previous Purchases, Review Ratings, Shipping Type)

Data Quality: 37 missing values in Review Rating (imputed)

## 🛠️ Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data loading, cleaning, and exploratory analysis
PostgreSQL	Advanced SQL queries and data analysis
Power BI	Interactive dashboard and visualization

## 📊 Project Steps
1. Data Loading & Initial Exploration (Python)
.  Imported dataset using Pandas & Identified data types and missing values

2. Data Cleaning & Preparation
.  Handled 37 missing values in Review Rating using median imputation

. Standardized column names and data formats

.  Verified data consistency across categories

3. Feature Engineering
.  Created age_group categories for segmentation
   
.  Calculated purchase_frequency_days from transaction history

.  Engineered metrics for customer lifetime value analysis

4. Exploratory Data Analysis (EDA)
.  Analyzed revenue distribution by demographics

.  Identified top-performing products and categories

.  Examined discount impact on purchasing behavior

.  Segmented customers based on purchase history

5. SQL Analysis (PostgreSQL)
sql
-- Example: Revenue by gender
SELECT gender, SUM(purchase_amount) as revenue
FROM customer
GROUP BY gender;

6. Dashboard Development (Power BI)
.  Built interactive dashboard with key metrics

.  Created visualizations for subscription analysis

.  Designed product performance heatmaps

.  Implemented customer segmentation views

7. Report Generation
Compiled findings into PowerPoint presentation

# Formulated data-driven recommendations

## 📈 Key Results & Insights
Revenue Analysis
Gender: Male customers generate significantly higher revenue

Age Group: Young Adults (18-30) contribute the highest total revenue

Shipping: Express shipping users have 3.5% higher average purchase amounts

# Product Performance
## Top 5 Rated Products:

Gloves: 3.86 ⭐

Sandals: 3.84 ⭐

Boots: 3.82 ⭐

Hat: 3.80 ⭐

Skirt: 3.78 ⭐

Most Discount-Dependent:

Hat (50% of purchases use discount)

Sneakers (49.66%)

Coat (49.07%)

Customer Segmentation
Segment	Count	Revenue Contribution
Loyal (10+ purchases)	3,116	68%
Returning (2-10 purchases)	701	25%
New (1 purchase)	83	7%
Subscription Analysis
Subscribers: 27% of customers

Non-subscribers: Generate higher total revenue despite smaller base

Opportunity: 73% of customers represent subscription growth potential

# 🎯 Business Recommendations
Boost Subscriptions: Offer exclusive benefits to increase subscriber base from 27% to 40%

Loyalty Programs: Implement tiered rewards for returning and loyal customers

Discount Optimization: Adjust pricing for high-discount dependency products

Targeted Marketing: Focus on Young Adults and express shipping users

Product Strategy: Feature top-rated products in marketing campaigns



