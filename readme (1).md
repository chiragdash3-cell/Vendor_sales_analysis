# Vendor Sales Analysis



> An complete data analytics pipeline that transforms raw vendor sales data into actionable business insights — leveraging **SQL** for efficient data wrangling, **Python** for cleaning and  advanced analysis, and **Power BI** for building dynamic, interactive dashboards.

---

## Project overview
1. Built a **data analysis pipeline** from raw CSVs to an interactive **Power BI dashboard**.
2. Analyzed **vendor purchase patterns** and **contribution percentages**.
3. Highlighted **high-margin**, **low-sales** brands to uncover opportunities.
4. Delivered actionable **insights** for data-driven **business strategy**.

---

## Workflow

Data ➡️ Database ➡️ Data Cleaning & Preparation ➡️ EDA ➡️ Power BI Dashboard

---

## Tech stack
- **Database:** DuckDB
- **Programming:** Python (pandas, NumPy, matplotlib, seaborn), SQL
- **Visualization:** Power BI
- **Other tools:** Git, GitHub

---

## Steps
1. **Data ingestion:** Loaded large vendor sales CSV files into DuckDB.
2. **Data analysing:** Ran SQL queries and basic aggregations to understand vendor contribution.
3. **Data cleaning:** Pulled SQL results into Python and cleaned/transformed with pandas.
4. **Exploratory Data Analysis (EDA):** Visualized trends, distributions, and correlations with matplotlib & seaborn.
5. **Business insights:** Addressed problems like:
   - Which vendors contribute most to purchase dollars?
   - Which brands have low sales but high margins?
   - Which vendor segments are most profitable?
6. **Dashboard:** Designed an interactive Power BI dashboard to present findings.

---

## Project structure
```
vendor-sales-analysis/
│
├── data/                # (Optional) small sample CSVs (not full raw data)
├── notebooks/           # all Jupyter notebooks
│   ├── Data_ingestion.ipynb          # load raw CSVs into DuckDB
│   ├── Data_analysing.ipynb          # SQL + pandas analysis for insights
│   ├── Data_cleaning.ipynb           # clean and preprocess data
│   └── Exploratory_data_analysis.ipynb  # EDA with matplotlib & seaborn
│
├── dashboard/           # Power BI files & exports
│   ├── Vendor_sales_analysis.pbix    # interactive BI dashboard
│   └── Vendor_sales_dashboard.png    # snapshot for README
│
└── README.md            # main project documentation

```

---



---

## Usage
Run analysis notebooks step by step:
1. Open `notebooks/Data_ingestion.ipynb`
2. Then `notebooks/Data_analysing.ipynb`
3. Then `notebooks/Data_cleaning.ipynb`
4. Finally `notebooks/Exploratory_data_analysis.ipynb`


Open the Power BI file (`dashboard/Vendor_sales_analysis.pbix`) to interact with the final dashboard.

---

## Analysis & Insights
- Identified top vendors contributing to revenue.
- Highlighted brands with strong margins but weaker sales volume.
- Discovered purchase trends by vendor category.
- Visualized vendor purchase distribution and seasonal patterns.

---

## Dashboard
The Power BI dashboard includes:
- Vendor-level contribution analysis.
- Purchase and margin breakdown.
- Trend and comparative analysis.

<img width="1084" height="608" alt="image" src="https://github.com/user-attachments/assets/fef80568-a443-4557-8262-d2e735497186" />


---





