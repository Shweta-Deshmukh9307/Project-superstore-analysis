# Superstore Sales, Profit & Discount Analysis

## Project Overview
This project is a 30-day end-to-end data analytics study on Superstore sales data (`Analysis_Ready_Superstore.csv`). The goal was to clean and analyze the data, build an interactive Power BI dashboard, and turn the findings into practical business steps.

## Overall Summary
- **Total Sales:** $2,297,200.86
- **Total Profit:** $286,397.02
- **Profit Margin:** 12.47%
- **Total Orders:** 5,009

## Tools Used
- **Python:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **SQL:** Queries for aggregation and validation
- **Power BI:** Interactive dashboard and KPI tracking
- **Git & GitHub:** Version control and project documentation

## Key Findings
1. **Order count drives sales gaps:** Regions with more orders (such as the West) bring much higher sales than lower-order regions (such as the South).
2. **High discounts hurt profit:** Discounts above 20% (`21-30%` and `>30%`) push profit margins into negative territory.
3. **Regional profit varies:** The Central region has a lower profit margin (`7.92%`) compared to stronger regions.
4. **Sub-category profit is uneven:** Some sub-categories make strong profit, while items like Tables, Bookcases, and Supplies lose money.
5. **Q4 is the peak season:** Sales grow steadily across quarters and peak in Q4.
6. **Large orders can shift averages:** High-value individual orders can raise averages, so order counts and margins should be checked alongside averages.

## Top Recommendations
1. **Control discounts above 20%:** Add limits or approval checks on steep discounts to protect profit margin.
2. **Fix loss-making sub-categories:** Review pricing, shipping costs, and discounting on items losing money (such as Tables and Bookcases).
3. **Grow order volume in lower-order regions:** Focus on order count and repeat purchases in regions like the South.
4. **Plan ahead for Q4:** Prepare inventory and discount rules before peak-season demand arrives.


## How to View the Project
1. Open the Python notebooks/scripts or SQL files to review the data checks and summary metrics.
2. Open the Power BI file in Power BI Desktop to explore filters by **Region**, **Category**, and **Year**.
3. Check the final report and presentation for full details, charts, success metrics, and limitations.
