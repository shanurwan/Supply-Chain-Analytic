# Beyond Logistics: Operational Intelligence in Real Time

## PROJECT OVERVIEW
This project is a comprehensive supply chain and logistics analytics solution developed using Microsoft Power BI. It provides end-to-end visibility into key operational areas including product availability,stock levels, order quantities, lead times, shipping performance, supplier reliability, production volumes, and cost distribution.The solution is designed to support strategic decision-making for stakeholders in operations, finance, and supply chain management. It features two fully interactive dashboards — Operational Overview and Logistics & Fulfilment — each built to uncover actionable insights, optimize processes, identify cost-saving opportunities, and drive efficiency across the supply chain lifecycle.
 
## PROJECT  OBJECTIVES
- To monitor and visualize key supply chain and logistics performance across multiple dimensions, including product type, supplier, and shipping routes.

- To track essential KPIs such as stock levels, lead times, shipping costs, defect rates, production volumes, and overall fulfillment efficiency.

- To identify bottlenecks such as delayed shipments, high defect rates, stockouts, and inefficient transportation modes.

- To provide data-driven recommendations for improving order planning, supplier selection, and logistics optimization.

- To utilize Power BI’s interactive features and visual capabilities for dynamic filtering, cross-analysis, and intuitive user navigation.
 

## METHODOLOGY & TOOLS USED
### Power BI Techniques:

- Power Query Editor for data cleaning, shaping, and transformation.

- DAX (Data Analysis Expressions) for custom calculations, KPIs, and logic-driven insights.

- Commonly used DAX functions include: CALCULATE, DIVIDE, SUM, COUNTROWS, COUNTDISTINCT, VAR, IF, ISBLANK

 
### KPIs (KEY PERFORMANCE INDICATORS)
Across the two page, a total of 12 KPI cards are used to summarize the most vital inventory and logistic metrics. These include:

- Total Unit Sold: 46000 units

- Total Revenue: $5776000

- Total Order: 4922 orders

- Average Revenue per Unit: 12.53

- Average Manufacturing Lead Time: 14.77
 
- Total Production Volume: 57000

- Manufacturing Cost Per Unit: $0.08

- Stock at Hand: 4777

- Average Shipping Lead Times: 17.08

- Total Shipping Cost: $554.81

- Average of Shipping Times: 5.75

- Cost-Speed Ratio: 0.96

 
## DASHBOARD SUMMARY
1. Operational Overview
This dashboard presents a consolidated view of core inventory and supply metrics. Key KPIs displayed include Total Units Sold (46,000 units), Total Revenue ($5.78M), Total Orders (4,922), and Average Revenue per Unit (12.53). It also visualizes stock availability, product types, and current stock levels (4,777 units) across SKUs. Charts are used to compare production volumes (57,000 units), manufacturing lead times (avg. 14.77 days), and manufacturing cost per unit ($0.08). The dashboard provides a quick understanding of product movement and stock sufficiency.

2. Logistics & Fulfilment
This section focuses on the downstream side of operations. It highlights shipping lead times (avg. 17.08 days), shipping costs ($554.81 total), average shipping times (5.75 days), and cost-speed ratio (0.96). It includes detailed tables showing order quantities, shipping carriers, and transportation modes by SKU. Insights are derived to support supplier and route efficiency, customer delivery performance, and logistics cost control. The dashboard helps identify fulfillment bottlenecks and areas for optimization using available supply chain and shipping data.


## OBSERVATIONS
1. Skincare Demand Outpaces Supply Across Most Suppliers
   
Skincare products consistently show order quantities exceeding stock levels across all suppliers except Supplier 2, indicating understocking and potential order fulfillment issues. This suggests a need to improve demand forecasting or replenish strategies for skincare SKUs.

2. Lead Time Composition Shows Shipping as Primary Delay
   
Stacked bar analysis of lead time components reveals that shipping time exceeds manufacturing time for all suppliers except Supplier 2. This identifies shipping as the main contributor to total lead time and highlights an opportunity to optimize logistics partnerships or routes.

3. Chennai Leads in Warehouse Overutilization
   
Chennai records the highest warehouse utilization rate of 1.39, with Supplier 1 in Chennai reaching 2.58. A utilization ratio above 1 indicates more orders than available stock, potentially causing fulfillment delays or strain on storage capacity. This flags Chennai as a location requiring inventory balancing or storage expansion.

4. Haircare Products Exceed Defect Rate Threshold
   
Haircare items average a defect rate of 3.32%, exceeding the acceptable limit of 3%. This signals recurring quality issues and necessitates further investigation into supplier practices or production standards for this category.

5. Cosmetic Products: High Manufacturing Cost with Low SKU Variety
   
Cosmetic products, despite having the lowest SKU count, incur the highest manufacturing costs. Conversely, skincare has the highest SKU count with lower unit cost. This insight supports product mix and margin analysis for strategic SKU portfolio planning.

6. Cosmetic Items in Chennai Show High Inspection Failure Rates
   
Products in the cosmetic category stored or manufactured in Chennai exhibit high inspection failure rates across all suppliers. This raises red flags about quality control effectiveness at this location and warrants deeper supplier or site-level audits.

7. Inspection Result Distribution Reveals Quality Control Gaps
   
A noticeable portion of inspection results remain pending, which may cause delays in product release and fulfillment. High fail percentages in certain categories and regions point to targeted quality assurance process gaps.

 
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
