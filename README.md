# Healthcare Dataset — Pandas Cleaning & Analysis

A hands-on data cleaning and exploratory analysis project on a real, messy healthcare dataset (55,500 rows) using Pandas.

## 🔨 What I Built
- End-to-end cleaning pipeline for a 55K-row healthcare dataset
- Feature engineering: `Length of Stay`, `Age Group`, `High Bill`
- Filtering, sorting, and groupby aggregations for insights (top billing cases, avg cost by condition)

## ⚠️ Problem I Faced
- Inconsistent name capitalization (`"Bobby JacksOn"`)
- Negative values in `Billing Amount`
- Duplicate rows skewing results
- Raw date columns unusable for calculations

## ✅ How I Fixed It
- `.str.title()` for name standardization
- Boolean filtering to remove negative billing rows
- `drop_duplicates()` to remove exact duplicates
- `pd.to_datetime()` + subtraction for `Length of Stay`
- `.apply()` with custom function & lambda for `Age Group` and `High Bill`

## 🛠️ Tools
Python, Pandas, Jupyter Notebook


