# Gender Wage Gap Heterogeneity in France (2021)

This project was developed as part of the **"Machine Learning for Econometrics"** course. It aims to analyze gender wage disparities in France in 202 using high-dimensional controls and causal inference techniques.

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
├── notebooks
│   ├── EDA.ipynb   # Exploratory Data Analysis & Causal Graph
│   └── Model.ipynb # Post-Lasso & DoubleML implementation
├── docs            # Research papers 
├── README.md
└── .gitignore