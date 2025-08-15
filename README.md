# Banking Customer Data – Exploratory Data Analysis (EDA) & Power BI Dashboard

## Project Overview
This project performs Exploratory Data Analysis (EDA) on banking customer data and develops a Power BI dashboard to present key insights visually for business decision-making.
The analysis identifies risk patterns, revenue drivers, and customer segments to help financial institutions:
- Reduce lending risk
- Improve customer acquisition
- Increase retention rates

## Project objectives:
- Understand customer demographics, banking behavior, and financial metrics
- Detect correlations between income, deposits, loans, and loyalty tiers
- Segment customers into meaningful groups for risk-based lending
- Prepare KPIs and interactive visualizations in Power BI to support strategic decisions

## Dataset
Source: 
- <a href = "https://github.com/ByteCrafty/Banking-Domain-Analysis-and-Dashboard/blob/main/Banking%20(1).csv">Dataset</a>
Shape: ~3,000 rows × 25 columns
Features:
- Demographics: Gender, Nationality, Occupation
- Financials: Estimated Income, Loans, Deposits, Credit Card Balance
- Behavior: Loyalty Classification, Fee Structure, Properties Owned, Risk Weighting

## Tools & Libraries Used
- Python: pandas, numpy
- Visualization: matplotlib, seaborn
- Feature Engineering: pd.cut() for income bands, calculated KPIs
- Business Intelligence: Power BI (for final dashboard visualization)

## EDA Process
1. Data Loading & Inspection
- Checked data types, missing values, duplicates, and basic statistics
2. Data Cleaning & Feature Engineering
- Created Income Bands (Low, Medium, High)
- Calculated Processing Fees based on Fee Structure & Loans
- Derived Engagement Days from customer join dates
- Computed Total Loans and Total Deposits
3. Univariate Analysis
- Countplots for categorical features (Nationality, Loyalty Tier, etc.)
- Histograms + KDE for numerical features (Income, Deposits, Loans)
4. Bivariate & Multivariate Analysis
- Countplots with hue for cross-category comparisons
- Correlation matrix + heatmap for numerical features
- Boxplots for numerical vs. categorical relationships

## Power BI Dashboard
- Interactive KPIs for Total Deposits, Loans, Customers, and Fees
- Filters/Slicers for Income Band, Nationality, Loyalty Tier
- Branch-wise performance analysis
- Risk-weighted lending recommendations
- Visual storytelling to help stakeholders make data-driven lending and marketing decisions
- Dashboard Interactions <a href = "https://github.com/ByteCrafty/Banking-Domain-Analysis-and-Dashboard/blob/main/Banking%20Domain%20Analysis%20Power%20BI.pbix">View Dashboard</a>
- Dashboard Interactions <a href = "https://github.com/ByteCrafty/Banking-Domain-Analysis-and-Dashboard/blob/main/Banking%20Domain%20Analysis%20Power%20BI%20dashboard.pdf">View Dashboard</a>
- Screenshot of Dashboard <a href = "https://github.com/ByteCrafty/Banking-Domain-Analysis-and-Dashboard/commit/ff5dd5071a8a9375c56954fbf2f93f97f2629959">Dashboard Screenshot</a>

## Key Insights
- Europeans form the largest customer group (~44%)
- Medium-income customers are the majority (~51%)
- 64% hold only one credit card
- High Fee Structure customers make up ~49%
- Jade loyalty tier is most common

