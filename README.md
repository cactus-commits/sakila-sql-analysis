# SQL - Sakila Rental Analysis

Exploratory data analysis on the Sakila DVD rental database - migrated from SQLite to DuckDB, analyzed with Python and SQL, and visualized in an Evidence dashboard.

Built as part of my data engineering studies.

## Stack
DuckDB, Python, Pandas, Evidence, SQL

## What's in here
sakila_eda.ipynbEDA notebook — SQL queries + pandas analysis + chartsevidence/Interactive BI dashboard built with Evidencesql/Raw SQL queries used in the analysis

| File/Folder | What it is
|-------|-------------------|
|`sakila_eda.ipynb` | EDA notebook — SQL queries + pandas analysis + charts |
|`evidence/` | Interactive BI dashboard built with Evidence |
|`sql/` | Raw SQL queries used in the analysis |

## How to Run

### Notebook
```bash
jupyter notebook sakila_eda.ipynb
```
### Evidence dashboard
```bash
cd evidence
npm install
npm run dev
```

## What I explored

First time combining DuckDB with a BI tool. Dug into film stats, rental pricing, customer spend, and revenue by category, plus a few questions of my own.
