# Brazilian E-Commerce Business Intelligence Analysis 📊✨

## 🎯 Project Overview
This project provides a comprehensive, data-driven analysis of a real-world Brazilian E-Commerce dataset using Python. The objective is to transition from basic data manipulation to delivering highly actionable Business Insights that help stakeholders optimize marketing spend, manage inventory, improve logistics, and increase conversion rates.

The analysis is structured around 4 core business questions designed to solve friction points in the customer journey and supply chain.

---

## 🛠 Tech Stack & Skills Demonstrated
*   Data Preprocessing & Engineering: Handled multi-table relational data, executing clean left joins, parsing datetime variables, and treating missing values through strategic imputation.
*   Data Visualization: Crafted executive-level visuals using Matplotlib and Seaborn with a clean, cohesive lightblue aesthetic and professional typography.
*   Business Intelligence: Translated visual data patterns into strategic corporate recommendations.

---

## 📈 Executive Summary of Insights & Business Impact

### 1️⃣ Geographical Sales Distribution (Target Market)
*   Objective: Identify the core regions driving the company's order volume.
*   Key Insight: SP (São Paulo) single-handedly dominates the marketplace, generating the highest number of orders by a massive margin compared to all other states.
*   Business Recommendation: The marketing team should allocate at least 50% of the digital advertising budget specifically to São Paulo (SP) to maximize the Return on Ad Spend (ROAS).

### 2️⃣ Product Category Performance (Inventory Management)
*   Objective: Determine the top-performing product categories by sales volume to optimize supply.
*   Key Insight: Home and lifestyle categories heavily lead the platform, with Bed, Bath, Table (bed_bath_table) capturing the top spot, closely followed by Health & Beauty (health_beauty).
*   Business Recommendation: The procurement team must establish continuous replenishment contracts with suppliers for these top 5 categories to prevent costly stockouts.

### 3️⃣ Customer Purchase Timing Patterns (Marketing & IT Ops)
*   Objective: Analyze seasonal shopping behaviors across a 24-hour cycle.
*   Key Insight: Sales volume is heavily concentrated during midday and afternoon hours, peaking specifically between 10:00 AM and 4:00 PM, while dropping to near-zero between 2:00 AM and 6:00 AM.
*   Business Recommendation: Push notifications and email marketing campaigns should be scheduled right before peak activity (around 9:30 AM). Conversely, critical server maintenance should be pushed to the lowest activity window (3:00 AM to 5:00 AM) to protect user experience.

### 4️⃣ Shipping Cost Burden (Logistics Optimization)
*   Objective: Uncover product categories where freight fees threaten customer checkout conversions.
*   Key Insight: Low-cost or bulkier items like Home Comfort (home_comfort_2) and Flowers (flowers) suffer from a massive logistics burden, where shipping fees devour 45% to over 55% of the item's baseline value due to volumetric weight.
*   Business Recommendation: Adopt a "Price Bundling" strategy by embedding a portion of the shipping fee into the product base price and advertising "Free Shipping" on the website to eliminate checkout friction.

---

## 📂 Project Structure
*   analysis.ipynb: The primary Jupyter Notebook containing the full pipeline (Data Loading, Cleaning, Analysis, and Visualizations).
*   README.md: Executive summary and project documentation.

---

## 🚀 How to Run the Project
1. Clone this repository.
2. Download the dataset from Kaggle (Brazilian E-Commerce Public Dataset by Olist).
3. Place the .csv files in the working directory.
4. Run all cells in analysis.ipynb.

---
