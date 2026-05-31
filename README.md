# Telecom-Analysis-
An end-to-end data analytics project evaluating market dynamics, subscriber distributions, and operational KPIs in the Indian telecommunications sector. This repository showcases a complete data pipeline from raw data engineering to executive-level interactive visualization.

**Data Pipeline & Architecture **
1. Data Cleaning & Engineering (Microsoft Excel)
Power Query ETL: Consolidated raw, fragmented telecom datasets (over 7,000 rows) into a single master table. Standardized date structures, handled null values, and cleaned carrier naming inconsistencies.

Conditional Logic: Grouped smaller regional operators under a unified "Others" classification to streamline visual clarity.

Pivot Table Summarization: Built dynamic multi-dimensional pivot engines to calculate aggregated metrics, handle state-wise hierarchies, and generate weighted averages for complex telecom KPIs.

2. Interactive Dashboards (Excel & Tableau)
This project features dual-dashboard implementations to demonstrate versatility across industry-standard business intelligence tools:

Tableau Dashboard: Focuses on high-performance geospatial mapping, advanced combination charts, and smooth spatiotemporal tracking across multi-year data.

Excel Dashboard: Built using a modern, card-based grid layout featuring an integrated left-hand global slicer panel for seamless cross-filtering by Year, Month, State, and Operator.

📊 Key Telecom Metrics Tracked
Total Active Subscribers: Real operational user bases vs. nominal registrations.

VLR % (Visitor Location Register): The active proportion of live SIM cards connected to the network—a critical industry metric for network utilization.

Market Share Distribution: Competitive volume distribution among top tier players (Airtel, Jio, Vi, BSNL).

Wireless vs. Wireline: Growth trend comparisons between legacy wireline infrastructure and modern wireless networks.
