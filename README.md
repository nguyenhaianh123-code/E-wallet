## Project Overview

This project analyzes payment and transaction data within an e-wallet ecosystem to understand the current performance and operational status of the platform.

The objective is to evaluate how users interact with the system through payments and transactions, measure product-level performance, and identify patterns that reflect business health and growth opportunities.

## Datasets
1. transactions.csv

Contains transaction-level data, including:

transaction_id <br>
merchant_id <br>
volume <br>
transType <br>
transStatus <br>
sender_id <br>
receiver_id <br>
timeStamp

This dataset is used to:
- Analyze transaction behavior
- Measure transaction success rate
- Evaluate transaction volume distribution
- Identify user activity patterns

2. payment_report.csv

Contains monthly aggregated payment volume by product:

report_month <br>
payment_group <br>
product_id <br>
source_id <br>
volume

This dataset is used to:
- Analyze monthly payment trends
- Measure product-level contribution to total payment volume
- Identify growth or decline across time

3. product.csv

Contains product-level metadata:
product_id <br>
category <br>
team_own

This dataset is used to:

- Segment performance by product category
- Evaluate team ownership performance
- Join with payment data for deeper business insights
