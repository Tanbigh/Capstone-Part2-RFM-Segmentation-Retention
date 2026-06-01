# Capstone Part 2: RFM Segmentation & Retention Strategy

## Project Overview

This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis combined with additional behavioral signals. The objective is to identify customer groups and recommend targeted retention strategies.

## Dataset

The following datasets were used:

* customers.csv
* orders.csv
* support_tickets.csv
* web_events_snapshot.csv
* intervention_history.csv

## Features Used

### RFM Features

* Recency
* Frequency
* Monetary Value

### Additional Signals

* Support Ticket Count
* Sessions (30 days)
* Product Views (30 days)
* Campaign Clicks (30 days)

## Customer Segments

The following customer segments were created:

1. Champions
2. Loyal Customers
3. Potential Loyalists
4. Dormant
5. At Risk
6. High Value Unhappy

## Repository Contents

* rfm_segmentation.ipynb
* segments.csv
* retention_strategy.md
* manual_review_cases.md
* requirements.txt

## Key Business Findings

* Champions generate the highest revenue and engagement.
* Dormant customers show high inactivity and low spending.
* At Risk customers have strong historical value but declining activity.
* High Value Unhappy customers require support intervention.
* Potential Loyalists represent the largest growth opportunity.

## Retention Priority

1. High Value Unhappy
2. At Risk
3. Champions
4. Loyal Customers
5. Potential Loyalists
6. Dormant

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `rfm_segmentation.ipynb` and run all cells.

## Author

Tanbi Ghosh

