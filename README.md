# Gender Wage Gap Heterogeneity in France (2021)

This project was developed as part of the **"Machine Learning for Econometrics"** course. It aims to analyze gender wage disparities in France in 2021 using high-dimensional controls and causal inference techniques.

## 👥 The Team
* Vladislava Anashkina
* Mona Bennis
* Cynthia Francis
* Maria Micaela Linares Gomez
* Anahi Reyes Miguel

## 📌 Project Overview
We use the 2021 "Bases Tous salariés" dataset to identify the "unexplained" gender wage penalty by accounting for occupational sorting, geographic location, and individual characteristics.

## 📂 Folder Structure

```plaintext
.
├── data
│   ├── raw         # Original FD_SALAAN_2021.csv (Stored via Git LFS)
│   └── processed   # Cleaned sample_dataset.csv for modeling
├── docs            # Research papers 
├── notebooks
│   ├── causal_forest_V1.html # Rendered HTML report of Causal Forest
│   ├── causal_forest_V1.Rmd # Causal Forest R implementation
│   └── cf_full_table.tex    # Exported LaTeX results table
│   ├── EDA.ipynb            # Exploratory Data Analysis & Causal Graph
│   ├── Metalearners.ipynb   # Metalearners notebook
│   ├── VA_Replication.ipynb # Post-Lasso Replication notebook
└── .gitattributes
└── .gitignore
├── README.md