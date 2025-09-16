# Vendor Sales Analysis

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> An **end-to-end data analysis portfolio project** where I transformed raw vendor sales data into actionable insights using SQL, Python, and Power BI.

---

## Table of contents
- [Project overview](#project-overview)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Workflow](#workflow)
- [Project structure](#project-structure)
- [Getting started](#getting-started)
- [Usage](#usage)
- [Analysis & Insights](#analysis--insights)
- [Dashboard](#dashboard)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project overview
This project demonstrates a **complete data analysis pipeline** applied to vendor sales data. The workflow begins with raw CSV files and ends with a fully interactive Power BI dashboard for decision-making.

The aim of the project was to explore vendor purchase patterns, identify contribution percentages, highlight brands with high margins vs low sales, and deliver insights that could support better business strategy.

---

## Features
- Efficiently load large CSV files into a database using **DuckDB**.
- Run **SQL queries** to explore, aggregate, and clean raw sales data.
- Integrate SQL results into **Python DataFrames** for further processing.
- Perform **data cleaning and transformation** using **pandas**.
- Conduct **Exploratory Data Analysis (EDA)** with **NumPy, Matplotlib, and Seaborn**.
- Generate **visual insights** to address business problems.
- Build a **professional Power BI dashboard** to present insights interactively.

---

## Tech stack
- **Database:** DuckDB
- **Programming:** Python (pandas, NumPy, matplotlib, seaborn)
- **Visualization:** Power BI
- **Other tools:** SQL, Git, GitHub

---

## Workflow
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
├── requirements.txt     # Python dependencies
├── README.md            # main project documentation
└── LICENSE
```

---

## Getting started
Clone the repository:
```bash
git clone https://github.com/USERNAME/vendor-sales-analysis.git
cd vendor-sales-analysis
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Ensure you have DuckDB installed, then place your raw CSVs in the `data/` folder.

---

## Usage
Run analysis notebooks step by step:
1. Open `notebooks/Data_ingestion.ipynb`
2. Then `notebooks/Data_analysing.ipynb`
3. Then `notebooks/Data_cleaning.ipynb`
4. Finally `notebooks/Exploratory_data_analysis.ipynb`

Or run the main analysis script if provided:
```bash
python analysis.py
```

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

*(Add screenshots or GIFs of your dashboard here from `/dashboard/Vendor_sales_dashboard.png`)*

---

## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

---

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Contact
Maintainer — Your Name  
📧 email@example.com  
🔗 [GitHub](https://github.com/USERNAME/vendor-sales-analysis)

---

## Changelog
See [CHANGELOG.md](CHANGELOG.md) for release notes and version history.

