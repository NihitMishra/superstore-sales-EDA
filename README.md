# Superstore Sales Data Analysis — Exploratory Data Analysis (EDA)

## Project Overview
This project explores a retail Superstore dataset using Python and Pandas to understand sales performance, profitability, product categories, regional trends, customer segments, and discount patterns.

## Objectives
- Examine dataset structure and data quality.
- Analyze sales and profit across product categories and regions.
- Identify top-selling products and profitable or loss-making sub-categories.
- Explore monthly sales trends.
- Investigate discount patterns and their association with profitability.
- Derive actionable business insights and recommendations.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Dataset Overview
- **Records:** 9,994
- **Columns:** 21
- **Missing values:** None found
- **Exact duplicate rows:** None found

The dataset includes order dates, shipping details, customer segments, product categories, sales, discounts, and profit.

## Key Findings

### 1. Category Performance
Technology generated the highest total sales ($836,154.03) and profit ($145,454.95). Furniture generated substantial sales ($741,999.80) but had a low profit margin of 2.49%.

### 2. Regional Performance
The West region led in sales ($725,457.82) and profit ($108,418.45). The Central region generated more sales than the South but earned less profit.

### 3. Product Performance
The Canon imageCLASS 2200 Advanced Copier was the top product by sales, generating $61,599.82.

### 4. Sub-category Profitability
Copiers generated the highest sub-category profit ($55,617.82), while Tables recorded the largest loss (−$17,725.48).

### 5. Discount Patterns
The average profit per row was negative for discount groups of 30%, 40%, 50%, and 80%. This indicates an association between higher discount levels and lower profitability in these groups, but does not prove that discounts alone caused the losses.

### 6. Customer Segments
The Consumer segment generated the highest sales ($1,161,401.35) and profit ($134,119.21).

### 7. Monthly Sales
November showed strong sales across multiple years, with November 2017 reaching $118,447.83.

## Business Recommendations
- Review Furniture pricing, discounting, and product costs.
- Investigate the losses in Tables and other loss-making sub-categories.
- Evaluate high-discount transactions by product category.
- Investigate regional differences in profitability.
- Use historical monthly trends to inform inventory and promotional planning.

## Conclusion
This exploratory analysis identifies key differences in sales and profitability across products, regions, categories, discounts, and customer segments. The findings can help guide further investigation into pricing, product performance, and business strategy.

## Project Files
- `Superstore-dataset.ipynb` — Jupyter Notebook containing the exploratory data analysis.

## Author
**Nihit Mishra**
