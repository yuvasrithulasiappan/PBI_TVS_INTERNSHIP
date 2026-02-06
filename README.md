Power BI Project Requirement Document
📚 Business Context
TVS Motors is a two-wheeler manufacturer with a wide dealer network across Tamil Nadu. 
The business operates with a centralized order processing system, where each dealer places orders on behalf of customers for various bike models.<img width="1040" height="659" alt="Data Model" src="https://github.com/user-attachments/assets/7de14139-0b8a-41a9-8bce-5295105ecd06" />
![order fulfillment tracker](https://github.com/user-attachments/assets/a603667e-1a62-4786-91d4-e4f67b9ffec9)
![Monthly Trend SLA report](https://github.com/user-attachments/assets/8ded744a-66d1-4cad-80f4-35cc6a55a8d0)
![model wise sales performance](https://github.com/user-attachments/assets/1fbca7ff-918d-4de4-9821-8534387d229b)
![Dealer Performance Report](https://github.com/user-attachments/assets/24605854-39cb-4ee8-884b-c78a714e540e)
![customer insight report](https://github.com/user-attachments/assets/0984723d-ab20-47c5-ba5f-5e290cc7c977)

🚲 Manufacturing Order Tracking & Dealer Performance Analytics (Power BI)
📌 Project Overview
This Power BI project analyzes a stage-based manufacturing and delivery process in a two-wheeler business.
Each order moves through multiple stages and typically takes 30–45 days to complete.

The dashboard enables business stakeholders to:
Track dealer performance-Identify delivery delays and SLA breaches-Analyze customer behavior-Understand model-wise demand and fulfillment efficiency

**This project focuses on business KPIs, data modeling, and advanced DAX, not just visuals.**

**🏭 Business Process**

Order Lifecycle Stages:Quotation-Confirmation-Engine Setup-Body Setup-Final Assembly-Quality Check (QC)-Delivery Start-Delivered
#Orders may experience stage-wise or overall delays, impacting dealer SLAs and customer satisfaction.
🎯 Project Objectives
Monitor dealer-wise order fulfillment performance-Track stage-level bottlenecks and delays-Measure SLA compliance-Analyze customer demographics and repeat behavior-Identify model-wise demand and delivery efficiency-Provide monthly trends for management decisions

**📊 Reports & KPIs**

**1️⃣ Dealer Performance Report**
Purpose: Evaluate dealer reliability and SLA adherence.
Key KPIs:Total Orders per Dealer-Average Delivery Time (Days)-On-Time Delivery %-Delayed Orders Count-Dealer SLA Compliance Score-Weighted score based on on-time vs delayed deliveries
Business Impact:
Helps management identify high-performing dealers and penalize chronic defaulters.

**2️⃣ Order Fulfillment Tracker**
Purpose: Operational visibility into order status and delays.
Key KPIs:Orders in Each Stage (live pipeline)-Completed Orders (Delivered)-In-Progress Orders-Average Delivery Duration by Dealer-Last Stage Update Timestamp-SLA Breach Count (stage-level & overall)
Business Impact:
Early detection of bottlenecks in manufacturing or logistics.

**3️⃣ Model-Wise Sales Performance**
Purpose: Understand product demand and fulfillment efficiency.
Key KPIs:Total Orders by Model-Revenue Estimation(On_Road_Price × Quantity)-Category Preference Analysis-Fuel Type Split (Petrol vs Electric)-Avg Delivery Time by Model
Business Impact:
Supports inventory planning, production prioritization, and EV adoption strategy.

**4️⃣ Customer Insights Report**
Purpose: Analyze buyer behavior and demographics.
Key KPIs:Repeat Customers Count-Orders by Gender-Customer Age Band Distribution-City-wise Customer Orders
Business Impact:
Enables targeted marketing, loyalty programs, and region-based sales planning.

**5️⃣ Monthly Trend & SLA Analysis**
Purpose: Track performance trends over time.
Key KPIs:Monthly Order Volume-Monthly On-Time Delivery %-Average Monthly Delivery Days-Monthly Delayed Orders
Business Impact:
Helps leadership measure operational improvements and seasonal demand patterns.

**🧠 Data Modeling Approach**
Star Schema Design
Fact Table: Orders
Dimension Tables: Dealer, Customer, Model, Date, Stage
Proper date intelligence enabled via a Date table
Optimized relationships for performance

**📐 Key DAX Measures Used**
Delivery Duration Calculations
On-Time vs Delayed Classification
SLA Compliance Percentage
Repeat Customer Identification
Month-over-Month Trend Metrics
Dynamic KPIs with conditional formatting
(DAX logic written to be scalable and reusable)

**🛠️ Tools & Technologies**
Power BI Desktop
DAX (Advanced Measures)
Power Query (Data Transformation)
Star Schema Data Modeling

**📈 Outcome & Value**
Single source of truth for order tracking
Reduced manual tracking of dealer delays
Improved decision-making using KPIs
Scalable dashboard design for future enhancements

**🔮 Future Enhancements**
Predictive delay analysis
Dealer ranking & penalty logic
Export-ready management reports
Integration with real-time order systems
