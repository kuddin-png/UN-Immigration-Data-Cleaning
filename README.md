# UN Immigration Data Cleaning

This repository contains a Jupyter Notebook that reshapes the UN Canada immigration spreadsheet into the requested country-indexed DataFrame.

## Files
- `UN_Immigration_Data_Cleaning.ipynb` — explained, executed notebook.
- `README.md` — project overview and run instructions.

## Requirements
- Python 3.9+
- pandas
- openpyxl
- Jupyter Notebook / JupyterLab

Install dependencies:

```bash
pip install pandas openpyxl notebook
```

## Run
Open `UN_Immigration_Data_Cleaning.ipynb` in Jupyter and run all cells from top to bottom. The notebook reads the assignment's Google Sheets Excel export, skips the introductory rows, removes metadata/code columns, renames the descriptive fields, sets `Country` as the index, and arranges the years 1980–2013 followed by `Total`.

The source sheet must be accessible to the runtime. If it cannot be reached, the notebook demonstrates the requested structure using only the five visible example rows and years legible in the assignment screenshot. That preview is explicitly marked as incomplete; rerun in an environment with access to the spreadsheet to produce the full table.

## Data source
United Nations, *International Migration Flows to and from Selected Countries: The 2015 Revision* (Canada, by citizenship), supplied Google Sheet:
https://docs.google.com/spreadsheets/d/1OGs8KoHGEZDxyFdaxAKmZbeO1BiSWVQ6/edit

UN dataset overview:
https://www.un.org/development/desa/pd/data/international-migration-flows
