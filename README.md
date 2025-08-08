# Global Water Consumption Analysis 🌍💧

**Objective:** Identify the main factors influencing water consumption and efficiency across countries.

---

## 📊 Dataset
- **Sources:**  
  [Kaggle – Global Water Usage Statistics](https://www.kaggle.com/datasets/shuvokumarbasak4004/global-water-usage-statistics),  
  [World Bank – GDP per capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD),  
  [World Bank – Total GDP](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD),  
  [World Bank – Urban population (% of total)](https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS),  
  [World Bank – Annual freshwater withdrawals (% of internal resources)](https://data.worldbank.org/indicator/ER.H2O.FWIN.ZS)

- **Size:** ~179 countries
- **Custom Metric:** Water Usage Efficiency = Total GDP / Water Consumption

---

## 🛠️ Tools & Methods
- **Python:** Pandas, NumPy, Seaborn, Plotly
- **Stats:** Pearson correlation, Linear Regression, ANOVA (via SPSS)
- **Visualization:** Interactive choropleth maps, bar/line charts

---

## 🔍 Key Findings
- **Population** is the strongest predictor of total water consumption.
- **GDP per capita** correlates with efficiency, but not total usage.
- Regional disparities suggest policy and infrastructure impact efficiency.

---

## 📂 Repository Structure
water-consumption-analysis/
- ├─ data/
- │ ├─ raw/ # Original CSVs (Worldometer, World Bank, Kaggle)
- │ └─ processed/ # Cleaned & merged datasets
- ├─ notebooks/
- │ └─ 01_water_analysis.ipynb # Main Jupyter Notebook
- ├─ reports/
- │ ├─ figures/ # PNGs for README + PDF report
- │ └─ water_analysis_summary.pdf
- ├─ requirements.txt
- └─ README.md

---

## 📷 Sample Visuals
![Choropleth Map](reports/figures/water_map.png)  
![Regression Plot](reports/figures/regression_plot.png)

---

## 🚀How to Run
- pip install -r requirements.txt
- jupyter lab
- Then open notebooks/01_water_analysis.ipynb and run all cells.

---

## 📄 Report
The full analysis is available in [**water_analysis_summary.pdf**](reports/water_analysis_summary.pdf).

---
