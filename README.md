📊**Business Insights 360 – Power BI Project**


🚀 **Project Overview:**

AtliQ Hardware is expanding rapidly and has decided to implement data analytics using Power BI to gain a competitive edge in the market. This project aims to help stakeholders make data-driven decisions across key business areas such as Finance, Sales, Marketing, and Supply Chain.



💻 **Tools Used:**

SQL

Excel

Power BI Desktop

DAX Language

DAX Studio (for performance optimization)





🏢 **About the Company (Context):**

AtliQ Hardware is a fast-growing company that sells computers and accessories globally through:

Retailers

Direct Channels

Distributors

After a significant loss from opening a store in the US based on intuition and outdated reports, the company decided to invest in data analytics to make better business decisions going forward.



**Key Tables:**

📘 **Dimension Tables**

dim_customer – Markets, customers, platforms, and channels

dim_market – 27 markets, 7 sub-zones, 4 regions (APAC, EU, LATAM, etc.)

dim_product – Divisions like P&A, N&S, categories, variants

📕 **Fact Tables**

fact_forecast_monthly – Forecasted quantity per customer (denormalized)

fact_sales_monthly – Actual sales quantity

📗 **Additional Tables**

freight_cost – Shipping cost per market/year

gross_price – Product-wise gross prices

manufacturing_cost – Production cost per year/product

pre_invoice_deductions, post_invoice_deductions




🔌 **Importing Data into Power BI**

Data was imported from MySQL into Power BI using credentials provided for the project. Data transformations and relationships were established in the Power Query Editor.




🧩 **Data Modeling**

A Snowflake schema was followed to ensure scalable and optimized performance. Proper relationships were defined between dimension and fact tables.

✅ Tip: Good data modeling = Fast reports + Accurate insights



**Key Features**
**Integrated Data Sources:**

Merged and analyzed data from SQL databases, Excel, and CSV files into a unified dashboard.


**Net Sales & COGS Analysis:**

Provided detailed analysis on Net Sales, Cost of Goods Sold (COGS), and profit margins across various regions, products, and channels.

**Gross Margin Insights:**

Created visualizations that allowed management to easily identify the factors contributing to improvements in the gross margin.

**Creative Dashboard Design:**

Custom visuals and interactive elements were designed to make the dashboard intuitive, easy to use, and tailored to AtliQ's specific needs.

**Forecast Accuracy:**

Enhanced forecast reports using historical sales and financial data to improve future decision-making.



🌟 **Project Results**
**Gross Margin Increase**: Early analysis of the Power BI dashboard suggested the possibility of increasing the company's gross margin by up to 30% by focusing on cost-effective product lines and high-performing regions.

**Conclusion**

This project showcases the power of modern data analytics tools such as Power BI in transforming traditional reporting processes. By leveraging real-time data, the leadership at AtliQ is now empowered to make more informed decisions, driving both increased gross margin and reduced operational expenses.


Explore my live dashboard here: https://app.powerbi.com/view?r=eyJrIjoiMDEzOTI1MDctZjk1Yi00M2QzLWI2ZmMtOTZkZDA2ZWI1YjdmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

**Expense Reduction**: Through better COGS tracking and analysis, the company forecasted a potential 20% reduction in expenses by streamlining its operations and focusing on profitability.

**Improved Forecast Accuracy**: The dashboard also allowed for more accurate forecasting by visualizing historical trends, which helped leadership make more informed predictions.

