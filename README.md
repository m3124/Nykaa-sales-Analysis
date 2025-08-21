# Nykaa-sales-Analysis
This project is a business analytics case study built on a synthetic dataset that simulates Nykaa’s sales transactions.
The dataset is not taken from Nykaa’s actual systems, but it’s designed to mimic the structure, scale, and complexity of real e-commerce data. The purpose is to demonstrate how raw transactional data can be turned into actionable insights and dashboards that business leaders could use to make decisions.

Project Goals:
I approached this project as if I had been asked to analyze Nykaa’s sales for management. The main objectives were:
1. Understand sales performance – revenue, units sold, and customer purchasing patterns.
2. Identify growth drivers – top categories, brands, and products that generate the most value.
3.Uncover trends – seasonality, monthly sales cycles, and other time-based patterns.
4.Build an interactive dashboard – a tool that decision-makers could explore to answer their own questions.

Project Structure:
1.nykaa_raw.xlsx → The unprocessed synthetic dataset, simulating raw e-commerce transactions.
2. nykaa_clean_final.xlsx → Cleaned and structured version of the dataset (after handling missing values, formatting, and consistency issues).
3. nykaapythoneda.ipynb → Python notebook with data cleaning, exploratory analysis, and visualization.
4. nykaawithdasboard.xlsx → Exce;l dsshboard with KPI's.
5. NykaaBI.pbix / bitut.pbix → Power BI dashboard files, showing the final interactive report.

Tools & Techniques:
Python (pandas, matplotlib, seaborn)
 1. Data cleaning (handling nulls, fixing formats, standardizing categories)
 2. Exploratory Data Analysis (EDA) to spot distributions, correlations, and outliers
 3. Visualizations for trend and category analysis
Excel
 1. Quick data validation and transformations
 2. Creating pivot tables for intermediate checks
Power BI
 1. Dashboard design
 2. DAX calculations for KPIs (e.g., Average Order Value)
 3. Interactive slicers and drill-down analysis.

Dataset Overview:
Rows: One lakh of simulated orders
Columns:
Order ID
Date
Product Name
Category
Brand
Quantity
Price
Revenue (calculated)
Although synthetic, the dataset captures realistic patterns: multiple product categories, diverse brands, variable order sizes, and seasonal peaks.

Business KPIs Tracked:
Total Revenue → Overall sales value
Units Sold → Total items purchased
Average Order Value (AOV) → Revenue ÷ Orders
Top Categories & Brands → Contribution to sales
Monthly Sales Trends → Growth/decline patterns over time

Business KPIs Tracked:
Total Revenue → Overall sales value
Units Sold → Total items purchased
Average Order Value (AOV) → Revenue ÷ Orders
Top Categories & Brands → Contribution to sales
Monthly Sales Trends → Growth/decline patterns over time

Dashboard Highlights:
The Power BI dashboard was designed for business decision-makers. Some features include:
KPI Cards → Revenue, Orders, AOV at a glance
Trend Line Charts → Monthly/seasonal performance tracking
Category & Brand Breakdowns → Interactive filters to explore product mix
Top Products Table → Identify bestsellers quickly
Drill-Down Slicers → Filter by time, category, or brand

Strategic Takeaways:
If this were a real Nykaa dataset, the recommendations would be:
Capitalize on festive demand → Plan marketing pushes and inventory for Q4 spikes.
Broaden brand partnerships → Reduce reliance on a handful of high-performing brands.
Cross-sell & bundle → Encourage customers to add more items per order, boosting AOV.
Category focus → Double down on skincare & makeup but explore ways to grow smaller categories.
