# Beyond Logistics: Operational Intelligence in Real Time

## PROJECT OVERVIEW
This project is a comprehensive inventory analysis solution built using Microsoft Power BI. It is designed to help Smartstock stakeholders gain deep visibility into their inventory levels, product statuses, stock performance across countries, warehouse locations, and category breakdowns. The solution includes three fully interactive dashboards: Summary, Status, and Country, all built to enhance strategic decision-making and drive inventory efficiency.

 
## PROJECT  OBJECTIVES
- To monitor and visualize the overall inventory performance across multiple dimensions, including product status, country, and category.

- To track essential KPIs like stock levels, unit price, inventory value, turnover rate, and lead times.

- To identify bottlenecks such as stock under reorder points, products out of stock, and warehouse imbalances.

- To recommend actionable strategies for improving inventory planning and restocking decisions.

- To leverage Power BI's interactivity and rich visual capabilities for dynamic filtering and navigation.

 

## METHODOLOGY & TOOLS USED
### Power BI Techniques:

- Power Query Editor for data cleaning, shaping, and transformation.

- DAX (Data Analysis Expressions) for custom calculations, KPIs, and logic-driven insights.

- Commonly used DAX functions include: CALCULATE, DIVIDE, IF, SUM, AVERAGE, SWITCH, and RELATED.

### Custom Visuals:

- Card with States by OKVIZ – Used for dynamic KPI visuals with trend indicators.

- Donut Pro – Interactive donut chart used to analyze product stock statuses.

- Timeline Slicer Pro – Enables intuitive monthly filtering for trend-based insights.

- Combo Bar Chart Pro – Combines category and stock breakdowns for deeper insights.

- Map Pro Visual – Used to show stock distribution geographically across 10 countries.

### UX/UI Features:

- Navigation icons (Summary, Status, Country, Filters, Help) for seamless page transitions.

- Custom color themes, soft shadows, and structured card layouts to enhance readability.

 
### KPIs (KEY PERFORMANCE INDICATORS)
Across the three dashboards, a total of 15 KPI cards are used to summarize the most vital inventory metrics. These include:

- Total Stock: 2,234,467 units

- Inventory Value: $1.124M

- Average Unit Price: 500.28

- Average Lead Time Days: 14.98

- Average Turnover Rate: 24.39

- % In Stock: 85.96%

- % Out of Stock: 14%

- % Under Reorder Point: 6.16%

- Stock Under Reorder Point: 36

- Minimum Order Restock: 1,071

- Products: 4,459

- Highest Stock Country: Belgium (236K)

- Highest Turnover Country: Poland (25.16)

- Highest Inventory Value: Belgium ($119.16M)

- Total Countries Monitored: 10

 
## DASHBOARD SUMMARY
1. Summary Dashboard
This is the primary dashboard showing a high-level overview of inventory metrics, including trends in total stock, average unit price, turnover rate, and lead time over time. The “Stock by Month” visual highlights seasonal or monthly peaks, with March 2024 being the highest stock volume (121K). The donut chart illustrates product status proportions—In Stock (84.25%) vs Out of Stock (15.75%).

2. Status Dashboard
Focused specifically on the category, this dashboard displays individual product performance, reorder levels, stock sufficiency, and lead times. It features a detailed table highlighting 20+ products, showing their stock levels, reorder points, and supplier IDs. Only 6.16% of electronics are below the reorder threshold, with 85.96% still in stock.

3. Country Dashboard
This dashboard maps inventory distribution by country. Belgium emerges as the leader in both inventory stock and value, followed by Germany and Italy. The warehouse section pinpoints high-stock shelves, such as AISLE-02-SHELF-03. It also segments stock levels by high, mid, and low categories, and reveals the category with the most stock—Home & Garden (339,731 units).

 
 

## OBSERVATIONS
1. Peak Stock Observed in March 2024
March 2024 recorded the highest monthly stock (121K units), indicating a significant inventory buildup, possibly tied to pre-sales replenishment or supply chain shifts.

2. High Inventory Value with Slightly Moderate Turnover Rate
Despite an inventory value of $1.124M, the average turnover rate of 24.39 suggests potential slow-moving items or overstocking in certain categories.

3. Belgium Dominates in Stock and Inventory Value
Belgium has the highest total stock (236K units) and inventory value ($119.16M), making it a key distribution hub. However, performance should be monitored to avoid excess stock.

4. Electronics Category Has Balanced Stock Health
Out of 584 electronics products, 85.96% are in stock with minimal reorder issues. However, some products (e.g., Product_1017) are dangerously low (15 units), needing attention.

5. Office Supplies and Home & Garden Show Strong Mid-Level Inventory
More than 40% of products in these categories fall under the 'Mid' inventory level, supporting stable stock availability.

6. Clothing and Toys Categories Have Lower High-Stock Percentages
These categories show high proportions in 'Low' inventory brackets, suggesting risk areas for understock.

7. Out-of-Stock Rate Is Relatively Low at 14%
This shows efficient restocking and forecasting, but focus is needed on those few SKUs with consistent OOS status.

8. AISLE-02-SHELF-03 Shows Peak Warehouse Load
This shelf appears overloaded with over 6,900 items, which may pose logistical or space management issues.

9. Germany Has the Most Products Below the Reorder Point
Germany leads with 30 products needing restocking, requiring tighter reorder planning.

10. Electronics Lead Time Varies Greatly by Product
Some items have very long lead times (up to 25 days), which can disrupt stock continuity if not forecasted accurately.

 
## RECOMMENDATIONS
1. Review March Procurement Strategy
Analyze the reasons behind the March peak to determine if it was strategic or resulted in overstock.

2. Optimize Stock Turnover with Targeted Promotions
Increase promotional efforts on slow-moving items to raise the turnover rate from 24.39.

3. Monitor Belgium Inventory for Overstock Risks
While high stock levels are good, excessive holding can tie up capital—consider redistribution.

4. Adjust Reorder Thresholds for Low-Stock Electronics
Products like Product_1017 and Product_1176 require adjusted reorder triggers to avoid OOS.

5. Reevaluate Stock Planning for Clothing and Toys
These categories need better forecasting models to reduce low-stock risks.

6. Automate Restocking Based on Category Performance
Implement predictive reorder models, especially for mid-performing categories like Office Supplies.

7. Improve Monitoring of High-Load Warehouses
Implement warehouse zoning or dynamic racking strategies for congested areas like AISLE-02-SHELF-03.

8. Enhance Lead Time Management for Electronics
Work with suppliers to shorten lead times or plan restocks earlier for long-lead items.

9. Conduct Regional Stock Audits in Germany
Identify gaps in Germany's stock forecasting, causing higher reorder needs.

10. Expand Successful Practices in Home & Garden to Other Categories
Their strong mid-level performance suggests a model worth replicating elsewhere.

 

## CONCLUSION
The SMARTSTOCK Inventory Control Analysis provides a highly interactive and insightful look into stock health, turnover, and category-level performance across multiple regions. With a solid foundation of KPIs and a well-structured visual experience, this dashboard empowers strategic inventory management decisions. With minor improvements in reorder strategies and warehouse optimization, this solution can dramatically improve operational efficiency and cost control.
