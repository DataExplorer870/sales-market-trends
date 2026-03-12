# Sales Analysis Dashboard for a Computer Hardware Company
This project analyzes sales data of a computer hardware company using an interactive dashboard built in Microsoft Power BI.

# Business Problem
The sales team at hardware company was struggling to analyze sales performance due to scattered data across multiple sources and manual reporting processes.
Generating reports required significant manual effort, making it difficult for managers to quickly identify top-performing markets, declining regions, and key customers.

Because of the lack of a centralized analytics system, decision-makers had limited visibility into sales trends and performance insights.

# Solution

The solution has the power-bi dashboard for this real-time analysis

The solution includes:
The data is stored in a MySQL database, which records all sales transactions such as products sold, customers, markets, and revenue. In large organizations, data from OLTP systems is often moved to a data warehouse before analysis. However, for simplicity, this project directly connects Power BI to the MySQL database.

A data model was created by establishing relationships between different tables such as customers, products, markets, and sales transactions. Key performance indicators (KPIs) such as Total Revenue and Sales Quantity were calculated using DAX.

Interactive visualizations were designed to allow users to analyze sales performance across markets, customers, and time periods. The dashboard provides a centralized platform for the sales team to monitor performance and make informed business decisions.

# Impact
The dashboard provides a centralized view of sales performance, enabling the sales team and management to quickly identify important trends and insights.

With the help of this dashboard:
- The sales team can quickly identify top-performing markets and customers
- Underperforming regions and products can be detected early
- Decision-making becomes faster and more data-driven
- Manual effort spent on collecting and merging Excel reports is significantly reduced

# Success Criteria
The project will be considered successful if it achieves the following outcomes:

- The dashboard provides sales insights using the latest available data
- The sales team can make better data-driven decisions, contributing to approximately 10% cost savings
- Manual data gathering efforts are reduced, saving around 20% of analysts’ time, allowing them to focus on higher-value activities
