# superstore-sales-profitability-analysis
**Interactive Tableau dashboard analyzing sales, profitability, products, categories, and regional performance.**
## Overview

This project analyzes the Superstore dataset to evaluate overall sales performance, profitability, product performance, category performance, regional performance, and the relationship between discounts and profit.

An interactive Tableau dashboard was developed to transform the raw data into actionable business insights and recommendations.

## Tools & Skills

- Tableau
- Data Visualization
- Exploratory Data Analysis (EDA)
- Sales & Profitability Analysis
- KPI Analysis
- Trend Analysis
- Product & Category Analysis
- Regional Analysis
- Statistical Analysis
- Business Intelligence
- Data-Driven Business Recommendations

## Key Findings

### Overall Performance

- Total Sales: **$2,326,534**
- Total Profit: **$292,297**
- Overall Profit Margin: **12.6%**

### Sales Performance

- Sales declined during the first two months before increasing and fluctuating between approximately $100K and $200K from May through August.
- Sales became more volatile toward the end of the year.
- **November** recorded the highest sales, while **February** recorded the lowest.

### Category Performance

- **Technology** generated the highest sales and total profit.
- **Furniture** ranked second in both sales and total profit.
- **Office Supplies** generated the lowest sales and total profit.

### Profitability by Category

- **Technology:** 17.4% profit margin
- **Office Supplies:** 17.2% profit margin
- **Furniture:** 3.0% profit margin
- Furniture is therefore the main category requiring further profitability investigation despite generating the second-highest sales and profit.

### Product Performance

- The largest individual loss was **$8,880** from the *Cubify CubeX 3D Printer Double Head Print*.
- Several other products also generated significant losses, including printers, conference tables, and specialized technology equipment.

### Regional Performance

**Sales ranking:**
1. West
2. East
3. Central
4. South

**Profit ranking:**
1. West
2. East
3. South
4. Central

- The **West** region led both sales and profit.
- **Central** generated more sales than South but less profit, indicating a potential profitability opportunity.

### Discount vs. Profit

- The analysis showed a slight negative relationship between average discount and profit.
- However, the relationship was extremely weak and statistically insignificant:
  - **R² = 0.0052**
  - **p = 0.7836**
- Therefore, discount level alone does not appear to meaningfully explain differences in profit in this analysis.

## Business Recommendations

1. **Improve Furniture profitability**  
   Investigate pricing, costs, and product-level profitability within the Furniture category, which has a significantly lower profit margin than Technology and Office Supplies.

2. **Review high-loss products**  
   Investigate products generating substantial losses, particularly the *Cubify CubeX 3D Printer Double Head Print*, which recorded the largest individual loss of $8,880.

3. **Investigate Central region profitability**  
   Analyze the product mix, pricing, discounting, and costs in the Central region to understand why it generates less profit than South despite higher sales.

4. **Continue supporting Technology performance**  
   Technology leads in sales, total profit, and profit margin. Identifying the products and sub-categories driving this performance could help inform future business decisions.

5. **Evaluate discounts alongside other factors**  
   Since the discount-profit relationship was extremely weak and statistically insignificant, discount levels should be evaluated alongside product, regional, pricing, and profitability factors rather than in isolation.

## Dashboard

The interactive Tableau dashboard provides a consolidated view of:

- Key performance indicators
- Sales trends over time
- Category performance
- Regional performance
- Profitability by category
- Interactive filtering by region and category

![Superstore Sales & Profitability Dashboard](images/dashboard.png.png)
