# Amazon E-commerce Sales Analysis & Interactive Dashboard

End-to-end data analysis project on 50,000 synthetic Amazon-style transactions (2022–2023). Demonstrates full junior data analyst workflow: data cleaning & feature engineering in Python/Pandas, exploratory analysis, business insights, and interactive visualization in Google Looker Studio.

Live Dashboard: [Amazon Sales Dashboard](https://lookerstudio.google.com/reporting/9b037b54-60c8-4a7a-9abb-270b6431d30c)  
Colab Notebook: [View in Google Colab](https://colab.research.google.com/drive/1KkjK_VIi_1tmSUnhOfNKcvBtSSWPSHSY?usp=sharing)

## Project Overview
Analyzed a realistic e-commerce dataset to answer business questions:
- What drives revenue (categories, regions, discounts)?
- How do discounts impact quantity sold?
- Which payment methods dominate?
- Key performance metrics (total revenue, AOV, average rating)

Built to showcase skills matching junior/mid-level data analyst roles:  
SQL-style aggregation (Pandas), Python data manipulation, visualization tools (Looker Studio), insight communication.

## Tech Stack
- **Data Processing & Analysis**: Python, Pandas, Matplotlib/Seaborn (Google Colab)
- **Visualization**: Google Looker Studio (interactive dashboard with filters & KPIs)
- **Dataset**: 50,000 rows synthetic Amazon sales data (CSV)

## Key Features & Insights
- **Total Revenue**: ₹32,866,573.74
- **Average Order Value (AOV)**: ₹657.33
- **Top Revenue Category**: Beauty (~₹5.55M)
- **Discount Impact**: Higher tiers (>20%) show potential volume uplift
- **Regional Breakdown**: Strong variation across North America, Asia, Europe, Middle East
- **Payment Methods**: Distribution visualized (UPI/Credit Card dominant in many cases)

Interactive dashboard allows slicing by date, category, and region.

## How to Reproduce
1. Clone repo: `git clone https://github.com/yourusername/amazon-sales-analysis-dashboard.git`
2. Open `amazon_sales_cleaned.csv` in Google Colab or Excel
3. Explore notebook (if uploaded) or replicate cleaning/EDA steps
4. Connect CSV to Looker Studio → Remap fields as needed

## Skills Demonstrated
- Data cleaning & feature engineering (discount_tier, month extraction)
- Aggregation & grouping (revenue by category/region)
- Time-series prep & visualization
- Interactive BI dashboard creation
- Business insight generation & communication

## Next Steps / Improvements
- Add time-series forecasting (Prophet or simple ARIMA in Colab)
- Build churn/retention proxy using ratings & repeat purchase signals
- Deploy as Streamlit/Shiny app (future phase)

Feedback welcome! Open to connect on LinkedIn or discuss data roles.

Made with ❤️ in Bengaluru, February 2026  
Raoul Anthony Lobo
