Power BI Project Requirement Document
📚 Business Context
TVS Motors is a two-wheeler manufacturer with a wide dealer network across Tamil Nadu. 
The business operates with a centralized order processing system, where each dealer places orders on behalf of customers for various bike models. 
The manufacturing process is stage-based (Quotation, Confirmation, Engine Setup, Body Setup, Final Assembly,
QC, Delivery Start, Delivered), and each order can take 30-45 days to complete. The business wants to track delays, 
dealer performance, customer behavior, and model-wise trends using Power BI.

🔍 Objective
To monitor dealer performance, order fulfillment stages, delay patterns, and customer insights using a centralized Power BI dashboard with advanced DAX features and dynamic KPIs.

🔢 Report-wise KPIs and Metrics
Dealer Performance Report

•	- Total Orders Per Dealer – Number of orders placed by each dealer.
•	- Avg Delivery Time – Average days between order and delivery.
•	- On-Time Delivery % – Percentage of orders delivered on or before expected date.
•	- Delayed Orders Count – Number of orders delivered late.
•	- Dealer SLA Compliance Score – Weighted score based on delivery timelines.

Order Fulfillment Tracker

•	- Orders in Each Stage – Count of orders currently in each delivery stage.
•	- Completed Orders – Orders that reached 'Delivered' stage.
•	- In-Progress Orders – Orders yet to be delivered.
•	- Delivery  Duration (Average) – Time taken by each dealer for their delivery
•	- Recent Stage Update Timestamp – Last updated timestamp to track freshness.
•	- Fulfillment SLA Breach Count – Orders exceeding stage deadlines.

Model-Wise Sales Performance

•	- Total Orders by Model – Number of orders for each bike model.
•	- Revenue Estimation – Sum of On_Road_Price × Quantity (assumed 1 per order).
•	- Most Preferred Categories – Category-wise order split.
•	- Fuel Type Comparison – Petrol vs Electric model share.
•	- Avg Delivery Time by Model – Model-wise fulfillment efficiency.

Customer Insights Report

•	- Repeat Customers Count – Customers with more than one order.
•	- Orders by Gender – Male vs Female buyers.
•	- Customer Age Band Distribution – Age-group-wise order count.
•	- City-wise Customers – Orders segmented by customer city.

Monthly Trend & SLA Report

•	- Monthly Order Volume – Count of orders each month.
•	- Monthly On-Time % – SLA performance trend.
•	- Avg Monthly Delivery Days – Timeline benchmark analysis.
•	- Monthly Delayed Orders – Count of late deliveries by month.
