
# 🌍 COVID-19 Global Impact Analysis (EDA)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on global COVID-19 data to explore how cases, deaths, and vaccinations evolved over time across different countries and regions.  
The aim is to identify trends, patterns, and correlations that can help policymakers, healthcare organizations, and researchers evaluate interventions and prepare for future health crises.

---

## 🗂 Dataset
- **Source:** [COVID-19 World Dataset (Kaggle)](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)
- **Description:** Contains daily COVID-19 statistics including confirmed cases, deaths, recoveries, and vaccination counts for multiple countries and regions.
- **Files:**
  - `data/covid19_data.csv` → Raw dataset from Kaggle
  - `data/processed_data.csv` → Cleaned dataset after preprocessing

---

## 🎯 Objectives
- Analyze **case trends per country**
- Compare **mortality rates** across countries
- Explore **vaccination rate vs case reduction**
- Study **time-series trends** during the pandemic

---

## 📊 Key Visualizations
- **Bar Charts:** Top affected countries by total cases and deaths
- **Line Charts:** Daily case trends (global + country-level)
- **Scatter Plots:** Vaccination rate vs daily new cases
- **Heatmaps:** Correlation between cases, deaths, and vaccinations
- **Pie Charts:** Share of cases by continent/region
- **Moving Averages:** Smoothed time-series trends

Sample Visualization:  
![Cases Trend](images/cases_trend.png)

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`

---

## 📂 Project Structure
```

covid19-eda/
│
├── data/
│   ├── covid19\_data.csv

├── images/
│   ├── cases\_trend.png
│   ├── vaccination\_vs\_cases.png
│   └── mortality\_rate.png
│
├── notebooks/
│   └── covid19\_eda.ipynb
│
├── README.md
└── requirements.txt

````

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Siddique-Aham/covid19-eda.git
   cd covid19-eda
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/covid19_eda.ipynb
   ```

---

## 📌 Problem Statement

The COVID-19 pandemic has significantly impacted global health, economies, and daily life. Understanding the progression of cases, mortality rates, and the effect of vaccination campaigns is crucial for informed decision-making. This project analyzes global COVID-19 data to uncover trends, patterns, and relationships that can help in assessing the effectiveness of interventions and preparing for future outbreaks.

---

## 📜 License

This project is licensed under the MIT License.

---

## ✨ Author

**Mohammad Aham**
📧 Email: siddiqueaham05@gmail.com
🔗 GitHub: [Siddique-Aham](https://github.com/Siddique-Aham)

```

---

