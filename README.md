Superstore Sales Analysis
A complete end-to-end data analysis project using Python and Power BI on the popular Superstore retail dataset. This project covers data cleaning, exploratory data analysis (EDA), Python visualizations, and an interactive Power BI dashboard.

Project Overview
DetailInfoDatasetSuperstore Sales (9,994 rows × 21 columns)Period2014 – 2017ToolsPython, Pandas, NumPy, Matplotlib, Seaborn, Power BIEnvironmentGoogle Colab

Key Business Insights

Technology leads in profit margin — Technology category generates the highest profit margin at 17.4%, despite Furniture having similar total sales ($836K vs $742K).
Furniture is a high-risk category — Furniture has the lowest profit margin at just 2.49% despite being the 2nd highest revenue category. Heavy discounting is the main cause.
Discounts above 20% cause losses — Any discount rate above 20% results in negative average profit per order. At 50% discount, the average loss is $310 per order.
West region outperforms all others — West region has both the highest total profit ($108K) and the best profit margin (14.94%). Central region is the weakest at 7.92%.
Strong Q4 seasonality — November is consistently the peak sales month across all years, driven by holiday season demand. February is always the lowest month.

Python Visualizations
Sales & Profit by Category

<img width="1023" height="579" alt="image" src="https://github.com/user-attachments/assets/f33002bb-00f9-4aba-8c4c-7e8941ce3590" />

Profit Margin % by Region

<img width="1001" height="575" alt="image" src="https://github.com/user-attachments/assets/4e2766d9-5fc3-4cb8-aa45-d35598c6332f" />

Monthly Sales Trend (2014–2017)

<img width="1505" height="592" alt="image" src="https://github.com/user-attachments/assets/5df2e17c-8d8a-4faf-b371-8543bcff2713" />

Discount vs Profit per Order

<img width="1057" height="582" alt="image" src="https://github.com/user-attachments/assets/6ad4c02d-daa0-442a-a6c0-ae84df31c36a" />

Power BI Dashboard

<img width="1590" height="839" alt="image" src="https://github.com/user-attachments/assets/bd34818c-643e-497e-a078-5bd482d7781a" />

Dashboard features:

KPI cards: Total Revenue ($2.30M), Total Profit ($286.40K), Units Sold (37,873)
Year slicer to filter all visuals dynamically
Sales by Category bar chart
Profit by Region bar chart
Profit Margin % by Category column chart
Monthly Sales Trend line chart

Project Structure
superstore-sales-analysis/
│
├── Sales_Analysis.ipynb        # Main analysis notebook
├── superstore_cleaned.csv      # Cleaned dataset
├── Superstore_Sales_Dashboard.pbix  # Power BI dashboard file
├── README.md
│
└── charts/
    ├── chart1_category.png
    ├── chart2_region.png
    ├── chart3_monthly_trend.png
    ├── chart4_discount_profit.png
    └── dashboard.png

How to Run

Clone this repository
Open Sales_Analysis.ipynb in Google Colab or Jupyter Notebook
Upload superstore_cleaned.csv to your environment
Run all cells in order
Open Superstore_Sales_Dashboard.pbix in Power BI Desktop


Dataset

Source: Superstore Dataset on Kaggle
Records: 9,994 orders
Features: Order details, customer info, product category, sales, profit, discount, region


Tools & Technologies

Python 3 — Pandas, NumPy, Matplotlib, Seaborn
Google Colab — Cloud-based notebook environment
Power BI Desktop — Interactive dashboard
GitHub — Version control and portfolio hosting




