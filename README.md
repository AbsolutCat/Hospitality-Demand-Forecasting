# Hotel Revenue Optimization
Objective
To analyze historical hotel booking data, forecast future room demand, and simulate pricing strategies using sensitivity analysis to maximize Gross Operating Profit (GOP)

Executive Dashboard
<img width="1919" height="1013" alt="Dashboard" src="https://github.com/user-attachments/assets/0db5ef40-0ec9-48ce-9218-aefb6ad8a9e5" />

Pricing Strategy & Sensitivity Analysis
Rather than relying on a single static forecast, this model stress-tests potential pricing decisions against varying market conditions to find the optimal revenue balance.
1. Developed a two-variable sensitivity matrix (What-If Data Table) balancing proposed Average Daily Rate (ADR) adjustments against potential fluctuations in room demand.
2. Application: This matrix provides property management with a clear, mathematical view of profit thresholds. It visually demonstrates the exact break-even points, showing management how much room rates can be raised before a drop in demand negatively impacts total projected revenue.

Technical Execution
This project bypasses traditional programming to build a lightweight, universally accessible financial model using advanced Excel architecture:
1. Data Aggregation: Cleaned and processed 100,000+ raw booking records using Pivot Tables to track historical ADR, RevPAR, and Occupancy metrics.
2. Demand Forecasting: Engineered an automated 6-month prediction model utilizing Excel's FORECAST.ETS exponential smoothing algorithms to accurately capture seasonal travel spikes.
3. Scenario Modeling: Built a dynamic What-If Data Table matrix to stress-test pricing strategies across multiple theoretical demand scenarios.

Files
1. Hotel_Revenue_Model.xlsx: The complete, interactive financial model. Download to test the Slicers and strategy matrix.
2. hotel_bookings.csv: The raw dataset sourced from Kaggle.
