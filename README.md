📊 Sales Performance Dashboard – Power BI Project
🧾 Overview

This project presents an interactive Power BI dashboard designed to analyze and visualize sales performance across multiple dimensions such as time, region, gender, product category, and customer behavior.
It provides valuable insights by combining KPIs, visual analytics, and dynamic filters—helping stakeholders understand trends, targets, and performance drivers at a glance.

Additionally, the project includes a full ETL workflow using SSIS, where multiple Excel files were transformed and loaded into a SQL Server database. Power BI then connected to the SQL database using Import Mode to ensure fast and optimized reporting.

🎯 Objectives

Track and compare Gross, Net, and Volume sales metrics.

Evaluate performance against MTD (Month-to-Date) and YTD (Year-to-Date) targets.

Identify top-performing regions, categories, and products.

Analyze customer activity levels and engagement.

Support data-driven decisions related to marketing, inventory, and customer retention.

⚙️ ETL Workflow (SSIS)

To prepare the dataset for Power BI:

Built an SSIS package to automate the ETL process.

Extracted data from multiple Excel files representing different product, sales, and customer datasets.

Transformed data where needed (datatype cleanup, mapping, removing inconsistencies).

Loaded all transformed tables into SQL Server using OLE DB Destinations.

Ensured a clean and structured database ready for Power BI modeling.

🔗 Power BI Data Source

All SQL tables were connected to Power BI using Import Mode for:

Faster performance

Complex data modeling

DAX measure calculations

Efficient filtering and interaction

⚙️ Dashboard Features
Dynamic Filters (Slicers)

Users can filter data by:

Date

Gender

Product Category

Country / Region

Sales Metrics (Gross / Net / Volume)

Interactive Report Pages

Sales Dashboard: KPIs, trends, and overall business view

Product Analysis: Detailed product-level performance

Customer Activity: Active vs inactive customers by region and product

📈 Key Insights
1️⃣ Strong Overall Sales Performance

Gross Sales exceeded targets, showing solid revenue growth.

Net Sales were slightly below target (–6.69%), suggesting possible issues related to discounts, costs, or profit margins.

2️⃣ Category Dominance

Bikes represent the majority of total sales.

Clothing and Accessories show smaller but stable contributions.

3️⃣ Balanced Gender Distribution

Sales are nearly equally split between male and female customers.

4️⃣ Regional Analysis

Australia, Southwest, and Northwest are leading markets.

Other regions show lower performance and represent opportunities for improvement.

5️⃣ Product-Level Insights

The Mountain-200 series leads top product sales.

Lower-performing items may require promotions or inventory adjustments.

6️⃣ Customer Engagement

Around 50% of customers are active, indicating growth potential and a need to re-engage inactive users.

7️⃣ Seasonal Trends

Clear summer sales peak, especially for outdoor-related products.

💼 Business Impact

This dashboard helps stakeholders:

Monitor KPIs and sales targets effectively

Identify underperforming regions or products

Improve customer targeting and retention

Support pricing and inventory decisions

Understand seasonal and market patterns

🛠️ Tools & Technologies

Power BI – Data visualization & modeling

SQL Server – Central data warehouse

SSIS – Extracting and loading Excel files into SQL

DAX & Power Query – Data modeling and measure creation

Excel / CSV – Original data sources

📂 Dataset

The dataset includes:

Product categories & names

Regional and country-level sales

Customer segmentation (active vs inactive)

Gender distribution

Gross, Net, and Volume sales

MTD & YTD targets

Note: While the slicer screenshot displays 2018, the dataset spans a wider date range.

💡 Conclusion

This project demonstrates a complete end-to-end BI pipeline—from ETL with SSIS, to SQL Server modeling, to Power BI dashboarding.
It transforms raw multi-source data into meaningful insights that support strategic business decisions related to sales growth, customer engagement, and performance optimization.

<img width="1329" height="651" alt="Screenshot (211)" src="https://github.com/user-attachments/assets/8f392194-103c-4eaf-afee-514c05cdc65e" />
<img width="1328" height="664" alt="Screenshot (212)" src="https://github.com/user-attachments/assets/20e52625-afee-46f9-a861-bb943341e9da" />
<img width="1332" height="656" alt="Screenshot (213)" src="https://github.com/user-attachments/assets/be8e9425-fbf5-448a-91b2-cdd6b61f5245" />
<img width="1331" height="654" alt="Screenshot (214)" src="https://github.com/user-attachments/assets/f3042313-2342-40f3-948e-e69131f80adb" />
<img width="1331" height="661" alt="Screenshot (215)" src="https://github.com/user-attachments/assets/0c1d8696-4529-4a10-bc6c-0112e0a9beb3" />
<img width="1916" height="1009" alt="Screenshot (216)" src="https://github.com/user-attachments/assets/04e014ea-ca10-40b0-b48a-36089c94fe25" />
<img width="1920" height="954" alt="Screenshot (253)" src="https://github.com/user-attachments/assets/d6ab22c4-8ad0-4dcf-8445-b2dd60b693cb" />







