# ndns-polyphenol-blood-pressure-eda
Exploratory Data Analysis of the association between polyphenol-rich dietary patterns and blood pressure in UK adults using National Diet and Nutrition Survey (NDNS) Years 1-15 data. Built with Python, pandas &amp; seaborn.

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB.svg?style=flat&logo=seaborn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=jupyter&logoColor=white)

---

## 📋 Project Overview

This project investigates whether higher consumption of polyphenol-rich foods (tea, berries, fruits, vegetables, cocoa, nuts, etc.) is associated with lower blood pressure in UK adults. 

**Objectives:**
- Derive a polyphenol-rich dietary pattern score from detailed food diary data
- Explore its relationship with measured systolic and diastolic blood pressure
- Perform comprehensive EDA with visualizations and statistical analysis
- Create a reproducible, portfolio-worthy analysis using real UK public health data

---

## 📊 Dataset

**National Diet and Nutrition Survey (NDNS) Rolling Programme – Years 1-15 (2008–2023)**  
- **Source**: UK Data Service (Study SN: 6533)  
- **Access**: Safeguarded data – [Apply here](https://datacatalogue.ukdataservice.ac.uk/studies/study/6533)  
- **Population**: Nationally representative sample of UK adults (19+ years)  
- **Key Variables**: 4-day food diaries, nurse-measured blood pressure, BMI, socio-demographics, survey weights

> **Note**: Due to data access restrictions, raw data is **not** included in this repository. Follow the link above to obtain it.

---

## 🛠️ Project Structure

```bash
ndns-polyphenol-blood-pressure-eda/
├── data/
│   └── raw/                  # ← .gitignore'd (contains downloaded NDNS files)
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_visualization.ipynb
│   └── 04_statistical_analysis.ipynb
├── src/                      # Reusable Python scripts
├── requirements.txt
├── README.md
└── .gitignore
