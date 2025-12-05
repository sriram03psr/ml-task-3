**Household Electric Power Consumption**



Dataset: 
https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption 

Dataset Provided Columns: 
• Date 
• Time 
• Global_active_power 
• Global_reactive_power 
• Voltage 
• Global_intensity 
• Sub_metering_1 
• Sub_metering_2 
• Sub_metering_3 

Task 1 — EDA 

Plot the time-series trend of Global_active_power and identify missing or abnormal readings. 

Analyze daily or hourly patterns to find high-usage and low-usage periods. 

Task 2 — Supervised Learning (Time-Series Forecasting) 

Combine Date and Time into a single timestamp and prepare windowed time-series data. 

Build forecasting models to predict next-hour Global_active_power. 

Train and test the forecasting model and evaluate using time-series error metrics. 

Plot predicted vs actual Global_active_power. 

Task 3 — Unsupervised Learning 

Detect unusual usage patterns using anomaly detection techniques. 

Build a clustering model on daily consumption profiles. 

Task 4 — AI Task (Simple Rule-Based AI) 

Simple Consumption Category Generator 

Based on the predicted Global_active_power, assign a category: 

Low Usage 

Medium Usage 

High Usage 

Display the assigned usage category. 

Generate one simple rule-based suggestion for each category. 

Print one example output. 

Visualize the clusters. 

Identify characteristics of each cluster (e.g., low-use vs high-use days). 
