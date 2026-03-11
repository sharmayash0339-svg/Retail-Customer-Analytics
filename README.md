#  Deep Dive: Customer Behavior & Revenue Drivers
*A Comprehensive Analysis using Inferential Statistics & Predictive Modeling*

# Project Overview
This project performs a deep-dive statistical analysis of customer purchasing patterns. Instead of basic descriptive statistics, I used **Inferential Statistics** (ANOVA, Correlation testing) and **Linear Regression** to identify what truly drives revenue for the business.

# Statistical Questions Answered:
1.  **Correlation:** Does how recently a customer visited (Recency) significantly impact how much they spend (Monetary)?
2.  **ANOVA:** Is there a statistically significant difference in spending across different customer segments (Top, Middle, Low Tier)?
3.  **Linear Regression:** Can we predict a customer's total spend based on their frequency of visits?

# Tech Stack & Skills
- **Python (Pandas, NumPy):** Data manipulation and manual RFM binning.
- **Matplotlib & Seaborn:** Visualizing correlation heatmaps and distribution plots.
- **Scipy & Statsmodels:** ANOVA testing and OLS Linear Regression.
- **SQL (MS SQL Server):** Advanced data aggregation and window functions.
- **Power BI:** Interactive dashboarding for business stakeholders.

# Statistical Deep Dive Results
- **Correlation:** Found a strong positive correlation (**0.60**) between Frequency and Monetary value, suggesting that getting a customer to return is the most effective way to grow revenue.
- **Hypothesis Testing (ANOVA):** With a p-value of **0.00**, we rejected the null hypothesis, proving that our customer tiers (Top, Mid, Low) are statistically distinct in their spending habits.
- **Linear Regression:** Every additional purchase (Frequency) adds an average of **$6,218** to a customer's total value (Coefficient: 6218.6).

- # Power BI Dashboard: Executive Insights
The final phase of this project translates statistical findings into a dynamic, interactive dashboard designed for business stakeholders.

# Dashboard Highlights:
- **Customer Segmentation TreeMap:** Visualizes the distribution of customers across 'Low', 'Mid', and 'Top' Tiers based on their Monetary value.
- **Revenue Driver Analysis (Regression Visualization):** A scatter plot showing the relationship between Purchase Frequency and Total Spend, featuring a trend line that represents the Linear Regression model.
- **Geographic Performance:** An interactive slicer by `Customer City` allows managers to drill down into specific regional performance.
- **Statistical KPI Cards:** Displays real-time averages for Recency and Frequency, alongside the ANOVA p-value to validate segment distinctness.

# Business Value:
By integrating the **Linear Regression** results, the dashboard doesn't just show historical data—it provides a predictive look at how increasing customer frequency by just 1 unit can significantly boost the bottom line.
