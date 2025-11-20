# FedEx-Exploratory-Data-Analysis

## Project Summary
FedEx Logistics operates within a complex and rapidly evolving global supply chain environment, where efficiency, visibility, and cost optimization are critical to maintaining competitive advantage. As global commerce expands and customer expectations rise, the ability to manage international shipments with precision has become essential. This project focuses on analyzing a comprehensive logistics dataset that captures end-to-end shipment processes, providing insights into purchase orders, transportation modes, vendor agreements, delivery timelines, and product-specific characteristics. The goal is to leverage this dataset to enhance operational performance, identify inefficiencies, and support data-driven supply chain decision-making.

At the core of the dataset is detailed purchase order and shipment information, including PO numbers, price quotations, sales orders, and Advanced Shipment Notices. These fields establish the commercial and operational foundation for each transaction, enabling analysts to trace how orders progress from creation to final delivery. Complementing these are critical timeline variables—such as the dates when purchase orders were sent to vendors, scheduled delivery dates, actual delivery dates, and recorded delivery confirmations. Together, these elements allow for precise measurement of on-time performance, delay analysis, and lead-time variability.

A key component of global logistics is the adherence to INCO terms, which define the responsibilities and risk allocation between buyers and vendors. The dataset includes vendor-specified INCO terms (e.g., EXW, FCA, CIF), allowing analysts to understand how handoff points and liability obligations impact transit times, freight costs, and delivery reliability. These terms also directly influence the shipment mode, with records specifying whether items were shipped via air, ocean, ground, or multimodal combinations. Shipment mode selections are critical for evaluating trade-offs between cost, speed, and cargo characteristics.

The dataset also provides granular detail on product and item attributes, including dosage forms, molecule/test type, product group classifications, brand, and manufacturing site. In industries such as pharmaceuticals, where many FedEx Logistics clients operate, product characteristics directly influence packaging, handling, customs requirements, and delivery urgency. Fields such as unit price, pack price, unit of measure, and line item value allow for robust cost analytics at both the product and shipment levels. These variables support financial assessments such as freight-to-value ratios, product profitability, and cost-per-unit-delivered comparisons across vendors and regions.

Operational efficiency is further evaluated through metrics related to freight cost, insurance cost, shipment weight, and vendor performance. By connecting cost data with timelines and outcomes, the dataset enables the identification of bottlenecks, cost drivers, and inefficiencies. Analysts can examine whether certain vendors consistently lead to delays, whether specific shipping modes result in higher freight expenditure, or how manufacturing location affects scheduling accuracy and delivery speed. Additionally, the dataset captures management ownership—such as which internal FedEx team oversees each shipment—providing another dimension for operational accountability and performance benchmarking.

With its breadth of fields spanning commercial, operational, logistical, and product-specific dimensions, the dataset offers an invaluable opportunity to conduct deep supply chain diagnostics. Insights derived from this analysis can support improvements in forecasting, vendor selection, shipment planning, and customer service. Moreover, by identifying patterns in delays, cost anomalies, or underperforming routes, FedEx Logistics can refine its global logistics strategy to better meet customer demands while controlling expenses.

Ultimately, this project aims to transform raw logistics data into actionable intelligence. Through comprehensive analysis, FedEx Logistics can streamline operations, enhance delivery reliability, optimize freight spend, and strengthen its ability to manage the complexities of international distribution in an increasingly competitive global market.

## Problem Statement
FedEx Logistics manages a complex global supply chain with diverse vendors, shipment modes, products, and regions. However, the company struggles to efficiently analyze its logistics data to understand delays, cost drivers, and operational bottlenecks. While detailed information exists—such as purchase orders, delivery dates, INCO terms, product attributes, and freight costs—it is not being used effectively to improve decision-making.

This lack of clear visibility leads to inconsistent delivery performance, higher shipping expenses, and difficulties in evaluating vendor reliability or optimizing transportation choices. The core problem is the absence of a unified analytical approach that can turn raw logistics data into actionable insights.

This project aims to address that gap by analyzing the dataset to identify patterns, diagnose inefficiencies, and provide recommendations that improve delivery timelines, reduce costs, and strengthen overall supply chain performance.

## Business Objective
To analyze FedEx Logistics’ shipment and purchase order data to improve delivery performance, reduce logistics costs, and enhance overall supply chain efficiency.

## Solution to Business Objective after conducting EDA
1️. Strengthen Vendor and Manufacturing Site Performance

- Prioritize high-performing vendors and review contracts with those causing consistent delays.

2️. Optimize Shipment Mode Selection

- Use Air Charter only for emergencies due to extremely high freight costs.

- Shift non-urgent and bulky shipments to Ocean or Truck modes to reduce cost.

3️. Improve Demand Forecasting and Order Planning

- Bulk quantities and large delays indicate inconsistent planning.

- Implement better forecasting to reduce emergency shipments and avoid high last-minute freight charges.

4️. Focus on High-Risk Countries

- Countries with high delays (e.g., Congo, Togo) need targeted operational improvements:

  - Early order placement

  - Local partnerships

  - Buffer stock strategies

5️. Monitor Key Cost Drivers

- Weight, shipment mode, and product group drive freight cost and delays.

- Implement dashboards to track:

  - Freight cost per kg

  - Cost per shipment mode

  - On-time delivery rates

6️. Reduce Dependency on Few Vendors

- A handful of vendors/manufacturers handle most shipments → supply chain risk.

- Expand supplier base where possible to avoid disruptions.

7️. Automate Data Tracking & Analytics

- Use automated reporting tools to monitor:

  - Delivery delays

  - Vendor performance

  - Freight anomalies

  - High-value shipments requiring security

## Conclusion
This analysis highlights key patterns in the supply chain, showing that shipment volumes, costs, and delays vary widely across vendors, product groups, shipment modes, and countries. A few vendors and manufacturing sites handle most shipments, creating dependency risks, while certain shipment modes—especially Air Charter—drive high freight costs. Delivery delays in specific countries indicate operational challenges that need attention.

Overall, improving vendor coordination, optimizing shipment modes, strengthening forecasting, and focusing on high-delay regions can significantly enhance delivery reliability and reduce costs. With data-driven planning and better resource allocation, FedEx Logistics can achieve a more efficient and resilient global supply chain.
