# Sales-insights-report
A SALES INSIGHTS REPORT
Executive Summary
This report presents a technical analysis of a product sales dataset developed for a portfolio project. The objective was to evaluate sales performance across products, regions, and sales personnel, while demonstrating practical skills in data cleaning, exploratory data analysis (EDA), feature engineering, and data visualization using Microsoft Excel.
1.	Business Problem
The analysis was conducted to identify trends and patterns in product sales across different regions. Specifically, the study aimed to determine which products, regions, and sales representatives contributed most to overall revenue.
2.	Project Objectives
• Analyse sales performance across regions and products.
• Identify top-performing salespersons and products.
• Examine the impact of discounts and promotions on revenue.
• Demonstrate proficiency in Excel-based analytical techniques.
• Develop insights to support data-driven business decisions.
3.	Dataset Overview
The dataset consisted of 1,501 sales records and 19 variables, covering transactions from 1 November 2023 to 30 June 2025.
Categorical variables included: Region, Customer Type, Product, Salesperson, Store Location, Payment Method, Promotion, Order ID, Customer Name, Region Manager, and three date-related columns.
Numerical variables included: Quantity Sold, Unit Price, Discount, Revenue (renamed from Total Price), Returned Units, and Shipping Cost.
4.	Data Cleaning and Preparation
Several preprocessing activities were undertaken to improve data quality and reliability:

• Standardised text entries using uppercase formatting to eliminate inconsistencies.
• Checked for duplicate records using Excel's 'Remove Duplicates' functionality; no duplicates were identified.
• Investigated missing values using filtering techniques.
• Blank values identified in the Promotion column were retained after confirming that they represented transactions without promotional codes. A total of 370 records fell into this category.
• Renamed 'Total Price' to 'Revenue' to improve business interpretability.
• Converted the cleaned dataset into an Excel Table to facilitate structured analysis and dynamic reporting.
5.	Feature Engineering
Additional analytical variables were created to enhance insight generation.

1. Quantity Range: Numerical quantities were categorised into Low, Moderate, and High purchase volumes using IF statements.

2. Actual Sales: A measure representing realised sales values after applicable adjustments.

3. Discount Amount: Calculated to quantify the financial impact of discounts on transactions.

These engineered features improved segmentation and supported deeper analytical exploration.
6.	Exploratory Data Analysis (EDA)
EDA was performed using Pivot Tables and Excel aggregation techniques.
The analysis focused on:
• Revenue distribution across regions.
• Product performance comparisons.
• Salesperson effectiveness.
• Discount utilisation patterns.
• Purchase behaviour based on quantity categories.

7.	Key Findings
The analysis generated the following strategic insights:

• Top-performing regions contributed disproportionately to overall revenue generation.
• Certain products consistently outperformed others in terms of sales volume and revenue contribution.
• High-performing sales representatives emerged as key drivers of organisational success.
• Promotional activities influenced purchasing behaviour, although a substantial number of sales occurred without promotional incentives.
• The engineered quantity categories provided additional understanding of customer purchasing intensity.

8.	Dashboard Overview
 <img width="960" height="393" alt="Screenshot 2026-06-12 131402" src="https://github.com/user-attachments/assets/1126e8b1-ceca-482a-9d6f-7ecaaf22ea10" />
<img width="704" height="333" alt="Screenshot 2026-06-10 145518" src="https://github.com/user-attachments/assets/069aa46d-d53b-413a-8e1e-cff21674f48b" />

The dashboard was designed as an executive reporting tool to support data-driven decision-making. Through the use of PivotTables, PivotCharts, slicers, and calculated fields, the dashboard transforms transactional sales data into meaningful business insights.
Key performance indicators (KPIs) monitored include:
• Total Revenue
• Actual Sales
• Top Performing Region
• Top Salesperson
• Top Product
• Sales Period Coverage
9.	Executive Summary of Findings
The analysis revealed that the organisation generated a total revenue of $4,379,992.43 during the reporting period. Actual Sales amounted to approximately $4.73 million, indicating a strong overall sales performance.

The North Region emerged as the best-performing region, while Bob was identified as the top-performing salesperson. The Tablet product category recorded the highest sales performance among all products analysed.
Salesperson evaluation highlighted differences in revenue generation capabilities.
• Bob emerged as the top-performing salesperson.
• Alice maintained strong performance levels.
• Frank, Carlos, Eva, and Diana demonstrated moderate but relatively consistent outcomes.

Product-level analysis identified the products driving organisational revenue.
• Tablets generated the highest contribution to overall sales.
• Laptops ranked among the strongest-performing products.
• Monitors, Chairs, Desks, and Phones contributed comparatively lower sales figures.
Dashboard Design and Analytical Techniques
The dashboard incorporated several advanced Excel functionalities, including:
• PivotTables for multidimensional summarisation.
• PivotCharts for dynamic visual representation.
• Slicers for interactive filtering.
• Feature engineering for Actual Sales and Discount Amount calculations.
• Conditional KPI reporting for executive-level monitoring.
These techniques enhanced usability, transparency, and analytical efficiency.
10.	Strategic Recommendations
Replicate the sales practices observed within the North Region across other regions.
• Develop incentive programmes based on top salesperson behaviours.
• Prioritise inventory replenishment for high-demand products such as Tablets.
• Perform deeper analysis on low-performing products to determine improvement opportunities.
• Evaluate the effectiveness of promotional campaigns using profitability metrics.
• Transition the dashboard to Power BI for real-time monitoring and automated refresh capabilities.
11.	Conclusion
The Sales Insights Dashboard successfully transformed raw sales data into actionable business intelligence. By integrating descriptive analytics with interactive reporting capabilities, the dashboard provided management with a holistic view of organisational performance. The findings support informed decision-making in sales strategy, regional management, customer engagement, and product optimisation.


