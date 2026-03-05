# Hotel Revenue Optimization

🎯 Objective
To analyze historical hotel booking data, forecast future room demand, and simulate pricing strategies using sensitivity analysis to maximize Gross Operating Profit (GOP)

📊 Executive Dashboard
<img width="1919" height="1013" alt="Dashboard" src="https://github.com/user-attachments/assets/0db5ef40-0ec9-48ce-9218-aefb6ad8a9e5" />

💡 Pricing Strategy & Sensitivity Analysis
This model finds the ideal revenue balance by stress-testing possible pricing choices against changing market conditions rather than depending on a single static projection.
1. We created a two-variable sensitivity matrix (What-If Data Table) to balance suggested changes to the Average Daily Rate (ADR) against possible variations in room demand.
2. Application: Property management can see profit levels clearly thanks to this matrix. It shows management how much room rates may be increased before a decline in demand adversely affects the overall predicted revenue by graphically illustrating the precise break-even points.

🛠️ Technical Execution (Excel)
This project uses Excel design to create a lightweight, widely accessible financial model without the need for conventional programming:
1. Data aggregation: To track historical ADR, RevPAR, and occupancy data, more over 100,000 raw booking records were cleaned and processed using pivot tables.
2. Demand Forecasting: To precisely capture seasonal travel spikes, an automated 6-month forecast model was created using Excel's FORECAST.ETS exponential smoothing methods.
3. Scenario Modeling: To evaluate pricing methods in a variety of hypothetical demand scenarios, a dynamic What-If Data Table matrix was created.

🗂️ Files
1. Hotel_Revenue_Model.xlsx: The complete, interactive financial model. Download to test the Slicers and strategy matrix.
2. hotel_bookings.csv: The raw dataset sourced from Kaggle.
