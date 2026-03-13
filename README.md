# Enterprise Finance Master Data Resolution Platform

I built this project to clean and match vendor data coming from different systems.

Sometimes the same vendor appears many times with different names like LLC, Inc, short forms, or spelling changes.  
In this project, I matched those records and created one clean vendor record.

## What I did

- created vendor data from multiple systems
- cleaned and normalized vendor names
- matched duplicate vendor records
- created one golden vendor record
- joined finance transactions with the cleaned vendor data
- built a vendor 360 summary
- added simple vendor search

## Why I did this project

I did this project to understand how companies handle duplicate vendor data and make finance reporting more accurate.

## Tools I used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib

## Output files

This project creates files like:

- `raw_vendor_master.csv`
- `vendor_master_normalized.csv`
- `vendor_match_pairs.csv`
- `golden_vendor_master.csv`
- `finance_transactions_raw.csv`
- `finance_transactions_resolved.csv`
- `vendor_360_summary.csv`
- `cross_system_resolution_summary.csv`
- `top_duplicate_clusters.csv`

## What I learned

From this project, I learned how to:

- clean vendor master data
- match duplicate records
- create a golden record
- improve finance data quality
- build a better reporting base

## How to run

1. Open the notebook in Google Colab
2. Install the libraries
3. Run all cells
4. Check the output files
