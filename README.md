# Data-Growth-Analysis-
In-depth analysis of an e-commerce orders dataset using SQL & Python: cohort retention, CLV modeling, revenue growth decomposition, and churn prevention. 

This repository contains solutions to the Data Growth Analyst SQL & Python homework, which covers:

- **Cohort Retention Analysis**  
- **Customer Lifetime Value & Acquisition Efficiency**  
- **Growth Decomposition & Revenue Health**  
- **Customer Risk Scoring & Churn Prevention**

# Schema: 

invoice_id (string): Order identifier
line_item_id (string): Line item identifier
user_id (string): Customer identifier
item_id (string): Product identifier
item_name (string): Product name
item_category (string): Product category
price (float): Item price in USD
created_at (datetime): Order creation timestamp
paid_at (datetime): Payment completion timestamp

# Notebook Walkthrough:

Setup & Data Loading
Configure Google Colab or local Jupyter environment
Load dataset and verify schema
Question 1: Cohort Retention Analysis
Build monthly cohorts
Calculate standard and quality retention tables
Perform resurrection analysis
Question 2: CLV & Acquisition Efficiency
Segment customers based on first 90 days behavior
Compute CLV and recommend max CAC for each segment
Validate predictions against 12+ month history
Question 3: Growth Decomposition & NRR
Decompose MoM revenue growth into new vs. existing customer contributions
Calculate Net Revenue Retention by cohort
Identify sustainability of growth drivers
Question 4: Churn Risk Scoring
Develop RFM-style customer health scores
Estimate return probabilities for inactive customers
Prioritize high-value at-risk customers

