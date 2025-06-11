# Beyond Logistics: Operational Intelligence in Real Time

<iframe title="Supply Chain Analysis" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZWM5NTk4MTEtY2IwMC00MTRjLWE2NTQtNWNhYmI2ZWYwM2MyIiwidCI6ImE2M2JiMWE5LTQ4YzItNDQ4Yi04NjkzLTMzMTdiMDBjYTdmYiIsImMiOjEwfQ%3D%3D" frameborder="0" allowFullScreen="true"></iframe>

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

8. Persistent Late Deliveries by Route and Region
   
Route A in Mumbai, Route C in Kolkata, and Route B in Bangalore exhibit consistently high late delivery rates, highlighting potential regional logistics inefficiencies or delays at specific route endpoints. These bottlenecks warrant process reviews or alternative routing strategies.

9. Carrier B Has the Highest Shipping Cost with Minimal Quality Gain
    
Despite Carrier B incurring the highest shipping costs, its defect rate is comparable to other carriers, offering no significant quality advantage. This questions its cost-effectiveness and makes a strong case for carrier contract review or renegotiation.

10. Transport Mode Preferences Reflect Cost-Speed Trade-Offs
    
Carrier preferences show that Carrier B primarily uses Air, which aligns with its high shipping cost. In contrast, Carrier A favors Road, and Carrier C uses Sea, resulting in lower costs but potentially longer lead times. These patterns reveal each carrier’s operating strategy and help optimize selection based on urgency and budget.

11. Shipping Efficiency Scores Indicate Overall Moderate Performance
    
The computed Shipping Efficiency Score (which balances lead time, cost, and defect rate) averages in the 0.4+ range across all carriers. This suggests room for improvement in balancing cost, quality, and timeliness, especially when normalized against best-case benchmarks.

 
## RECOMMENDATIONS
### 🔧 Inventory & Production
1. Prioritize Restocking for Skincare Products Across Suppliers Except Supplier 2
   
Since order quantities exceed stock levels for all suppliers except one, urgent replenishment plans and safety stock buffers should be put in place to prevent stockouts.

2. Address Haircare Category Quality Control Issues
   
With an average defect rate of 3.32%, haircare exceeds the quality threshold. Recommend conducting a root cause analysis and increasing inspection stringency for this product line.

3. Optimize Manufacturing for Cosmetic Products
   
Despite having the lowest SKU count, cosmetics have the highest manufacturing costs. Recommend cost analysis and potential redesign or supplier renegotiation to bring costs down.

4. Leverage Supplier 2’s Efficiency
   
Supplier 2 stands out with better balance in stock levels, order quantities, and shipping vs. manufacturing time. Consider reallocating more production volume to this supplier or using it as a benchmark for others.

5. Investigate High Failure Rate of Cosmetic Inspections in Chennai
   
All suppliers in Chennai show high inspection failure rates for cosmetics. Recommend facility audits or process reviews in that region to maintain quality standards.

6. Rebalance Warehouse Utilization in Chennai
   
Chennai shows warehouse utilization ratios of 1.39 and 2.58 for some suppliers, indicating stock overflow. Suggest inventory redistribution to other warehouses or revisiting stocking policies.

🚚 Logistics & Shipping
1. Re-evaluate Carrier B for Cost Optimization
   
Carrier B shows significantly higher shipping costs without delivering proportionally better defect rates or lead times. Recommend benchmarking cost-per-delivery or exploring alternate providers.

2. Assign Transport Modes Based on Product Sensitivity & Urgency
   
Use Air (Carrier B) only for time-sensitive or high-value products, and allocate Road/Sea for others to optimize the cost-speed trade-off.

3. Review and Reroute Deliveries for High-Late-Rate Routes
   
Persistent late deliveries on:

Route A in Mumbai

Route C in Kolkata

Route B in Bangalore
Suggest evaluating alternate logistics providers or last-mile strategies in those areas.

4. Improve Overall Shipping Efficiency Score (>0.4)
   
A moderate Shipping Efficiency Score across all carriers suggests inefficiencies in cost, time, or quality. Recommend investing in route optimization tools, better forecasting, and stricter SLAs.
 

## CONCLUSION
This Power BI-based Inventory & Logistics Analytics Dashboard offers a comprehensive, interactive view of inventory status, supplier performance, production metrics, and logistic efficiency. Leveraging 12 key KPIs and multiple cross-dimensional visuals, the dashboard enables data-driven decision-making in areas such as restocking, supplier evaluation, cost management, and shipping strategy. With actionable insights on stock imbalances, defect hotspots, warehouse utilization, and delivery performance by route and carrier, this solution lays a strong foundation for strategic supply chain improvements. Targeted actions in quality control, warehouse planning, and transport optimization can significantly enhance operational efficiency and reduce avoidable costs.
