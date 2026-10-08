# 🛒 Walmart Store Sales Analysis


An end-to-end data analytics project analyzing weekly sales performance across 45 Walmart stores — from data cleaning and exploratory analysis to business insights, using Python.


## 📌 Project Overview


- **Goal**: Analyze retail sales patterns, measure the impact of holidays and external economic factors (fuel price, CPI, unemployment), and identify key revenue drivers across store types.
- **Dataset**: [Kaggle — Walmart Recruiting: Store Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting) (public dataset, weekly sales 2010–2012)
- **Tools**: Python (pandas, NumPy, matplotlib, seaborn), Jupyter Notebook, Tableau
- **Interactive Dashboard**: [Walmart Sales Analysis — Tableau Public](https://public.tableau.com/app/profile/dave.han6326/viz/WalmartStoreSalesAnalysis/1_1)


## 🔑 Key Findings


1. **Store format drives performance**: Type A stores (avg 182K sq ft) generate $20,100 in average weekly sales — 2.1x the $9,520 of Type C stores (avg 41K sq ft).
2. **Holidays lift sales +7.1%**: Holiday weeks average $17,036 in weekly sales vs $15,901 in non-holiday weeks, across all 45 stores.
3. **Clean, analysis-ready dataset**: Audited 421,570 weekly records (Feb 2010-Oct 2012) — resolved negative sales anomalies, imputed missing values, and joined three tables with zero row loss.


## 📁 Repository Structure


```text
walmart-sales-analysis/
├── notebooks/
│   ├── 01_data_cleaning.ipynb   # Data type conversion, missing-value handling, table merges
│   ├── 02_eda.ipynb             # Exploratory analysis & sales visualizations
│   └── 03_sql_validation.ipynb  # SQLite database build & SQL/pandas cross-validation
├── .gitignore
└── README.md
```


## 🚀 How to Run


1. Download the dataset from the Kaggle link above and place `train.csv`, `stores.csv`, `features.csv` in `data/`.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open the notebooks in order, or click "Open in Colab".
