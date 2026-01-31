Customer Shopping Behavior Analysis 🛒📊
Project Overview
This end-to-end data analytics project focuses on transforming raw customer data into actionable business intelligence. By utilizing Python for data preparation and PostgreSQL for deep-dive analysis, the project identifies high-value customer segments, evaluates the ROI of discount programs, and explores the impact of subscription models on total revenue.

🚀 Key Business Questions Addressed
The analysis was driven by five core objectives to help stakeholders make data-driven decisions:
Purchasing Patterns: Understanding how demographics like age and gender influence shopping habits.
Revenue Drivers: Identifying which customer segments (Subscribers vs. Non-subscribers) provide the highest financial value.
Promotional Effectiveness: Evaluating whether discounts truly increase long-term revenue or simply drive volume.
Operational Impact: Analyzing how shipping preferences (Standard vs. Express) correlate with higher order values.
Customer Loyalty: Segmenting customers into New, Returning, and Loyal tiers to improve retention strategies.

🛠️ Tech Stack & Methodology
1. Data Preparation (Python/Pandas)
Exploration: Conducted initial summary statistics and missing value checks.
Imputation: Handled missing review ratings using median imputation within specific product categories to maintain data integrity.
Standardization: Cleaned column names and formatted strings for seamless SQL integration.
Feature Engineering: Created age groups and numeric frequency tiers to enhance segmentation.

2. Database Management (PostgreSQL)
Loaded cleaned data into a structured customer_behavior database.
Leveraged CTEs (Common Table Expressions) and Window Functions to identify top-performing products and customer lifetime value (CLV).

4. Interactive Visualization
Developed a dashboard to present real-time insights for executive decision-making using PowerBI

📈 Key Insights & Strategic Impact
High-Value Segments: Specific age groups were found to contribute a disproportionate share of total revenue, suggesting a need for targeted marketing spend.
The Subscription Edge: Subscribers generally exhibit higher spending patterns, validating the financial value of loyalty programs.
Shipping & Spend: A positive correlation exists between Express shipping and higher average purchase amounts.
Discount Strategy: While discounts drive volume, they do not always equate to higher profit margins, indicating a need for optimized discount targeting.
