# E-Commerce Profitability & Marketing ROI Analysis

An end-to-end data analysis project focused on uncovering actionable business insights from e-commerce operational data. This repository contains the data preparation, exploratory data analysis (EDA), and strategic recommendations designed to optimize marketing spend, mitigate margin-eroding fees, and address high product return rates.

## Business Objective
The primary goal of this project is to analyze three core business datasets (Orders, Products, and Marketing Spend) to identify cost-saving measures and revenue-optimizing opportunities. The analysis directly answers five critical business questions:
1. What is the average profit margin by product category, and what drives the variance?
2. How does profitability differ across owned versus third-party sales channels?
3. What is the return rate by category and channel, and what is the estimated revenue lost?
4. Which marketing platforms deliver the best Return on Ad Spend (ROAS)?
5. How can the company strategically reduce the marketing budget by 20% with minimal revenue impact?

## Tech Stack & Tools
* **Language:** Python
* **Libraries:** `pandas` (data manipulation, aggregation), `numpy` (numerical operations), `matplotlib` (data visualization)
* **Environment:** Jupyter Notebook

## Repository Structure
* `E-commerce_Analysis.ipynb`: The main Jupyter Notebook containing all data cleaning, transformation, analysis, and visualizations.
* `marketing_spend.csv`: Monthly advertising spend, impressions, clicks, and attributed revenue across six marketing platforms.
* `orders.csv`: Transaction-level data including channel, gross revenue, discount, shipping cost, product cost, platform fees, and return status.
* `products.csv`: Product-level catalog data including unit costs, selling prices, and category classifications.

## Key Insights & Recommendations
* **Marketing Optimization:** TikTok Ads and Influencer marketing generate the highest ROAS (>23.0). Conversely, Email Marketing severely underperforms (5.40 ROAS). **Recommendation:** Reallocate the budget by completely pausing Email Marketing and reducing Facebook Ads spend by ~15%, easily achieving a 20% total budget reduction while protecting top-line revenue.
* **Channel Profitability:** Third-party platform fees severely compress margins. Marketplace and Social Commerce yield average profits of just 15.39 USD and 17.10 USD per order. **Recommendation:** Incentivize customer migration to owned channels (Mobile App and Website), which carry zero platform fees and yield over double the profit per order.
* **Shipping Cost Burden:** Flat shipping rates on low-margin product categories (like Books and Beauty) consume a disproportionate amount of the retail price. **Recommendation:** Implement minimum order thresholds for free shipping or renegotiate high-weight shipping tiers.
* **Return Rate Interventions:** Electronics (8.61%) and Social Commerce (9.13%) drive the highest return rates, resulting in an estimated 18,500 USD in revenue leakage. **Recommendation:** Deploy stricter sizing/quality checks and re-evaluate Social Commerce as a primary acquisition channel.
