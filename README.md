##📊 Mutual Funds Market Analysis and Performance Insights (2019–2025)
🧩 Project Overview

This project analyzes the Indian Mutual Funds Market from 2019–2025, focusing on fund mobilization, redemptions, net inflows, and Assets Under Management (AUM) across various scheme types and categories.
Using Power BI, the data was cleaned, modeled, and visualized to uncover key investment trends and fund performance insights over time.

🎯 Project Objectives

Analyze Market Trends
Study the overall trends in the Indian Mutual Funds industry from 2019–2024, focusing on fund mobilization, redemptions, inflows, and outflows across various scheme types.

Evaluate Fund Performance
Assess performance and growth of mutual fund categories — Equity, Debt, Hybrid, and Solution-Oriented Schemes — based on Net AUM and Net Inflows.

Understand Investor Behavior
Identify how investor preferences shifted between Open-Ended, Close-Ended, and Interval schemes over time.

Compare Scheme Categories
Compare and visualize the contribution of different scheme categories and their performance metrics using interactive Power BI Dashboards.

📂 Data Sources

Source & Timeline:

Indian Data Portal (2019–2024)

Association of Mutual Funds in India (AMFI) (2024–2025)

Domain: Finance

❓ Problem Statement

Analyze mutual fund performance across different scheme types and categories to identify top-performing funds.

Study investor behaviour through inflow and outflow trends to understand investment patterns over time.

Evaluate fund mobilization, redemption, and AUM data to assess market growth and stability.

Compare open-ended, close-ended, and interval schemes for strategic investment insights.

Identify which categories attract the most investors and funds.

Examine monthly/yearly AUM trends for forecasting potential and investor confidence.

Analyze the relationship between investor count (folios) and asset growth.

🧾 Attribute Details
Attribute Name	Data Type	Description
ID	Integer	Unique identifier for each record.
DATE	Date	Reporting date (monthly).
Scheme Name	Text	Name of the mutual fund scheme.
Scheme Type	Category	Open Ended / Close Ended / Interval.
Scheme Category	Category	Equity, Debt, Hybrid, Solution Oriented, Others.
No. of Schemes	Whole Number	Total schemes under a category.
No. of Folios	Whole Number	Total investor accounts (folios).
Funds Mobilized (₹ Crore)	Currency	Total inflows during the period.
Repurchase/Redemption (₹ Crore)	Currency	Total outflows during the period.
Net Inflow (+/-) (₹ Crore)	Currency	Net money movement (Inflow/Outflow).
Net AUM (₹ Crore)	Currency	Total market value of managed assets.
Average AUM (₹ Crore)	Currency	Average AUM during reporting period.
No. of Segregated Portfolios	Whole Number	Segregated portfolios within the fund.
AUM in Segregated Portfolio (₹ Crore)	Currency	Assets managed under segregated portfolios.
Inflow/Outflow Status	Text	Indicates positive or negative net investment.
🛠️ Tools and Technologies
🧮 Microsoft Excel

Used Power Query for ETL operations: data collection, cleaning, and transformation.

Removed duplicates, consolidated data, and standardized formats before Power BI import.

Automated formatting tasks using Excel Macros.

📈 Microsoft Power BI

Primary tool for data modeling, visualization, and dashboard creation.

Utilized DAX (Data Analysis Expressions) to create custom measures and KPIs.

Power Query Editor handled data cleaning and integration.

🧹 Data Preprocessing

Data Collection – Collected data from 2019–2024 (Indian Data Portal) and 2024–2025 (AMFI).

Data Consolidation – Combined monthly Excel sheets into a single workbook, removed subtotal and redundant rows.

Automation (Macros) – Automated repetitive formatting (alignment, styling, text formatting).

Data Cleaning (Power Query) – Filled missing values, standardized formats, and corrected data types.

Data Transformation – Added calculated flag columns and harmonized field names.

Data Integration – Appended cleaned datasets into a unified dataset (2019–2025) for visualization.

🧩 Data Modeling & DAX (Power BI)
Data Modeling

Created a Calendar Table linked to the main dataset using the Date field for time-based analysis.

DAX Components
📊 Calculated Columns

Inflow/Outflow Status

Activity Flag

📏 Measures

Total Funds Mobilized

Total Withdrawals (Redemptions)

Total Net Inflow / Outflow

Total Net AUM

Inflow Percentage (%)

Average Investment per Scheme

⚙️ Parameters

Funds Parameter (fund movement trends)

Investors Parameter (participation comparison)

📉 Analysis & Visualizations

Interactive Power BI dashboards were developed to address problem statements using bar charts, line graphs, donut charts, tree maps, and KPI cards.

Fund Performance – Bar charts identified top-performing schemes across categories.

Investor Behaviour – Stacked area charts visualized inflow/outflow patterns.

Market Growth – KPI cards showed total inflows, redemptions, and AUM stability.

Scheme Comparison – Bar charts compared open-ended vs. close-ended vs. interval schemes.

Investor Distribution – Funnel charts and tree maps analyzed category-wise participation.

AUM Trends – Area charts highlighted monthly and yearly growth patterns.

Investor Engagement – Donut charts represented folio contribution across schemes.

📈 Performance Insights

Open-Ended Schemes were the most preferred investment type.

2024 recorded peak values in both AUM and total inflows.

Other ETFs category received the highest inflows.

Income & Debt-Oriented Schemes showed strong inflow trends (stable, low-risk investments).

Liquid Fund Schemes had the maximum investor participation.

Continuous year-over-year growth in investor folios indicated strong market trust.

Money Market Funds recorded high outflows, suggesting strategic shifts or profit booking.

🧠 Conclusion

The integration of Excel and Power BI enabled a comprehensive analysis of the Indian Mutual Funds market (2019–2025).
Cleaned and unified data revealed:

Open-Ended Schemes received the highest funding.

AUM and inflows peaked in 2024, signaling strong investor confidence.

Liquid Funds attracted the most investors.

Money Market Funds showed higher outflows due to market reallocation.

Overall, the project transformed complex financial data into clear, actionable insights on mutual fund performance and investor behavior.

📚 Tags

#PowerBI #DataAnalysis #MutualFunds #FinanceAnalytics #DAX #DataVisualization #ExcelPowerQuery
