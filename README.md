# Telecom Tariff Revenue Comparison

## Overview
This project analyzes mobile tariff plans to identify which plan generates the highest revenue per user.  
The analysis aggregates usage data (calls, messages, data) and computes monthly revenue to compare plans.

## Dataset
The dataset typically includes:

- User-level activity (number and duration of calls, messages sent, data used).
- Tariff plan information.
- Revenue per user and per month.

> Note: Raw data is not included in this repository.  
> The notebook assumes you store the relevant CSV files locally in a `data/` folder.

## Tech stack
- Python: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`
- Statistics: `scipy.stats` (if used for hypothesis testing)

## Business questions
1. Which tariff plan brings higher average monthly revenue per user?
2. Is the difference in revenue between plans statistically significant?
3. How do usage patterns (calls, messages, data) differ between plans?

## Methodology
1. Data cleaning and preparation.
2. Aggregation of usage and revenue at the user-month level.
3. Comparison of average revenue between plans.
4. (Optional) Hypothesis testing to validate differences between plans.

## Example insights
- One plan may yield higher revenue but rely heavily on a small subset of heavy users.
- Another plan may have more stable but lower revenue per user.
- Differences in data usage patterns can explain revenue gaps between plans.

## How to run
1. Clone this repository.
2. Place the CSV files into a `data/` folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
