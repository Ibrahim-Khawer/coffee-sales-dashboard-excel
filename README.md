Coffee Sales Dashboard – Excel Project
Business Problem
Coffee companies need to monitor sales performance across different dimensions to optimize product strategy, customer targeting, and regional focus. This project addresses the challenge of tracking and analyzing coffee sales data across multiple years, coffee types, customer segments, and countries. By building an interactive Excel dashboard, the business can make data-driven decisions to increase revenue and customer satisfaction.

Technical Details
Data Sources:

Orders data with 100+ transaction records including customer details, product information, and sales metrics

Customer database with demographic and loyalty information

Product catalog with coffee types (Arabica, Robusta, Liberica, Excelsa), roast types, and pricing

Monthly sales summaries by coffee type and year

Country-level sales performance data

Top customer spending analysis

Analysis Workflow:

Data Integration: Used XLOOKUP to dynamically retrieve customer names, emails, countries, and loyalty card status from customer tables

Product Mapping: Implemented INDEX-MATCH functions to pull product details (coffee type, roast type, size, unit price) from product catalog

Data Transformation: Applied nested IF statements to convert abbreviated codes to full names (e.g., "Rob" → "Robusta", "M" → "Medium")

Data Quality: Conducted duplicate checks and standardized formatting for dates, currency, and numerical values

Dashboard Development: Created PivotTables and interactive charts with slicers for year, country, coffee type, and customer segmentation

Key Findings:

Regional Performance: United States dominates sales ($35,638), significantly outperforming Ireland ($6,696) and United Kingdom ($2,798)

Product Analysis: Arabica shows consistent sales across all years, with notable peaks in February 2020 ($745) and September 2021 ($840)

Customer Insights: Top 5 customers (Allis Wilmore, Brenn Dundredge, Terri Farra, Nealson Cuttler, Don Flintiff) represent significant revenue opportunities

Temporal Patterns: Sales show monthly fluctuations with strongest performance in spring and fall months across all years

Tools: Microsoft Excel (XLOOKUP, INDEX-MATCH, PivotTables, Slicers, Conditional Formatting)

Recommendation
To maximize revenue growth, the coffee company should:

Focus on High-Value Customers: Implement personalized loyalty programs and exclusive offers for top customers like Allis Wilmore and Brenn Dundredge to increase retention and lifetime value

Optimize Regional Strategy: Intensify marketing efforts in the United States while developing targeted campaigns for Ireland and UK markets to capture growth opportunities

Product Portfolio Management: Leverage strong performance of Arabica and Liberica varieties in seasonal promotions and consider expanding product lines in these categories

Inventory Optimization: Use monthly sales trends to improve demand forecasting and stock management, particularly preparing for peak seasons in spring and fall

Customer Segmentation: Develop targeted marketing campaigns based on purchase patterns and regional preferences to increase conversion rates
