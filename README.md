# Retail-data-analysis-Kafka

Here we compute various Key Performance Indicators (KPIs) for an e-commerce company, RetailCorp Inc. Real-time sales data of the company across the globe is provided. The data contains information related to the invoices of orders placed by customers all around the world.
Data source - https://archive.ics.uci.edu/ml/datasets/Online+Retail#

Fetched the data from Kafka server 
Code - to create schema of a single order. To calculate the new UDFs and any other utility functions if needed. To write the final summarised input values to the Console

Calculating time-based KPIs:
Code to calculate time-based KPIs tumbling window of one minute on orders across the globe. KPIs are calculated for a 10-minute interval for evaluation; so, ten 1-minute window batches is taken.

Calculating time- and country-based KPIs:
Code to calculate time- and country-based KPIs tumbling window of one minute on orders on a per-country basis. KPIs are calculated for a 10-minute interval for evaluation; so, ten 1-minute window batches have is taken.
