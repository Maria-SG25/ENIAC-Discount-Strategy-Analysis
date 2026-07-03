# 📊 ENIAC-Discount-Strategy-Analysis

## 📖 Project Overview

This project analyzes ENIAC's pricing strategy to determine whether frequent discounting contributes to long-term business performance. The analysis focuses on evaluating the relationship between discounts, revenue, profitability, and seasonal sales patterns while providing data-driven recommendations for pricing decisions.

The complete workflow includes data preparation, exploratory data analysis (EDA), business insights, and strategic recommendations.

---

## 🎯 Business Objective

As a premium electronics retailer, ENIAC faces a strategic challenge:

- Marketing seeks to increase sales through discounts.
- Management and investors aim to protect profitability and maintain the company's premium brand image.

This project evaluates whether discounts create sustainable business value or simply reduce profit margins without significantly increasing revenue.

---

## 🧹 Data Preparation

Before performing the analysis, the dataset was cleaned and standardized to ensure reliable results.

The data preparation process included:

- Handling missing and inconsistent values
- Removing invalid and incomplete orders
- Standardizing date and pricing formats
- Consolidating product categories
- Keeping only completed customer transactions

These steps improved data quality and ensured consistency throughout the analysis.

---

# 📈 Business Analysis

## 1. Product Distribution

### Objective

Understand how products are distributed across different price categories.

### Findings

- Most products belong to lower-priced categories.
- A relatively small number of premium products generate the majority of revenue.

### Business Insight

Revenue is primarily driven by high-value products rather than product volume.

---

## 2. Discount Strategy

### Objective

Evaluate how frequently discounts are applied.

### Findings

- Approximately **97%** of products are sold with a discount.
- Discounting has become part of the standard pricing strategy instead of being limited to promotional events.

### Business Insight

Frequent discounts may weaken ENIAC's premium market positioning.

---

## 3. Revenue Analysis

### Objective

Determine whether larger discounts generate higher revenue.

### Findings

- Larger discounts increase order volume.
- Revenue remains highest within the **0–10%** discount range.
- Discounts above this level do not consistently increase total revenue.

### Business Insight

Higher sales volume does not necessarily translate into higher business value.

---

## 4. Margin Analysis

### Objective

Measure the impact of discounts on profitability.

### Findings

- Discounts between **0–10%** maintain margins close to **95%**.
- Margins decrease steadily as discounts increase.
- Discounts above **20%** reduce margins to approximately **44%**.

### Business Insight

Aggressive discounting substantially reduces profitability.

---

## 5. Seasonal Performance

### Objective

Determine whether sales peaks are driven by discounts or seasonal demand.

### Findings

- Revenue peaks coincide with **Black Friday** and the **Christmas shopping season**.
- Seasonal demand has a greater influence on sales than continuous discounting.

### Business Insight

Targeted promotional campaigns appear more effective than maintaining permanent discounts.

---

# 📋 Data Quality Assessment

Several limitations were identified during the analysis. Although these issues were addressed through preprocessing, improvements in data collection would significantly enhance future analyses.

| Data Issue | Recommended Improvement | Business Benefit |
|------------|-------------------------|------------------|
| Inconsistent product categories | Standardize categories during data entry | Faster reporting and less manual cleaning |
| Missing promotion information | Record campaign names, types, and dates | Better evaluation of marketing performance |
| Single order timestamp | Store the complete order lifecycle | Improved operational and seasonal analysis |
| Revenue and margin not stored | Save validated KPIs at transaction level | More reliable financial reporting |
| No customer or sales channel information | Collect customer segments and sales channels | Better customer analysis and forecasting |

---

# 💡 Recommendations

Based on the findings, the following actions are recommended:

- Use discounts between **0–10%** as the standard pricing strategy.
- Limit discounts above **20%** to exceptional cases.
- Reserve larger discounts for major seasonal campaigns.
- Improve data quality through standardized data collection.
- Support the premium brand with customer experience rather than continuous price reductions.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

# 📌 Key Takeaways

- Small discounts (**0–10%**) provide the best balance between revenue and profitability.
- Large discounts significantly reduce margins.
- Seasonal demand drives revenue more effectively than permanent discounting.
- Improving data collection would enable more accurate reporting and stronger business decisions.

---

## 📁 Deliverables

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Business insights supported by visualizations
- Strategic pricing recommendations
- Python notebooks
