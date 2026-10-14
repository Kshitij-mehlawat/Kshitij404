# Retail Order Sales Analysis

Exploratory analysis of a fictional 60-row retail dataset (59 unique orders after removing one exact duplicate), with a Power BI-ready cleaned CSV.

## Files

- `SampleDataSet.ipynb` — data cleaning, exploratory analysis, visualizations, findings, and conclusions. Run from this folder; it reads `Demo.csv` beside the notebook.
- `Demo.csv` — source dataset.
- `cleaned_orders_for_powerbi.csv` — cleaned export for importing into Power BI Desktop.
- `SampleDataSet.pbix` — save the Power BI report here if you want to include the editable dashboard file. It was not present in the supplied files when this project was added.

## Main findings

- North had the highest estimated regional revenue (249,538).
- Retail led channel revenue (258,687) and had the lowest channel return rate (9.1%).
- Office Supplies led category revenue (210,886); Electronics had the highest category return rate (30.8%).
- Returned orders averaged 9.0 delivery days and a 1.9 customer rating, versus 4.5 days and 4.1 for non-returned orders.

Revenue is estimated after discounts and **before returns/refunds**. Refund amounts and product costs are not included. Findings describe this small sample and do not establish causation.

## Run

Open `SampleDataSet.ipynb` in Jupyter and run all cells from top to bottom. The notebook uses pandas, NumPy, and Matplotlib.
