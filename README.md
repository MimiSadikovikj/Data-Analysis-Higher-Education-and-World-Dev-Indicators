# 📊 University Rankings and World Development Indicators – Data Analysis Project

This project analyzes the relationship between university rankings (from **Times Higher Education**) and country-level development indicators (from the **World Bank’s WDI dataset**). The analysis seeks to understand how education investments and national indicators correlate with or predict changes in university performance globally.

---

## 📌 Objectives

The project aims to answer the following questions:

1. **How do university rankings change over time?**
2. **Which university attributes contribute most to better or declining ranks?**
3. **How do university characteristics correlate with country-level development indicators?**

---

## 📂 Datasets Used

- **Times Higher Education (THE)** rankings: Contains university performance metrics including teaching, research, and citations.
- **World Development Indicators (WDI)**: Global country-level indicators like GDP per capita, education expenditure, and public spending metrics.

---

## 🛠 Technologies and Tools

- Python (Jupyter Notebook)
- pandas, numpy, seaborn, matplotlib, plotly
- pycountry for country code and continent mapping
- scikit-learn for building predictive models

📦 Dependencies listed in [`requirements.txt`](./requirements.txt)

---

## 🔍 Methodology Overview

### 🔧 Data Preprocessing
- Cleaned and reshaped THE and WDI datasets.
- Mapped countries to continents.
- Interpolated missing values.
- Computed a **custom "total_score"** metric for universities.
- Created **"mean world rank"** by grouping universities by country and year.

### 📈 Exploratory Data Analysis
- Time-series plots of rankings for selected countries (USA, Singapore, Switzerland).
- Compared ranking trends against indicators like:
  - **Government expenditure on education (% of GDP)**
  - **Current education expenditure (% of total public expenditure)**

### 📊 Predictive Modeling
- Identified top university attributes influencing rank.
- Compared trends across continents and identified top-growing institutions.

---

## 📊 Key Insights

- **European universities** showed significant upward ranking trends.
- **Singapore** demonstrated a positive correlation between education investment and improved ranks.
- In contrast, **the USA** saw rising investment but worsening mean rank – potentially due to dataset coverage or increased number of universities.
- The **most impactful ranking factors** were found to be teaching, research, and citations.

---

## 📎 Project Files

- `Notebook.ipynb`: Full analysis code and visualizations.
- `DOPP Report.pdf`: Final written report summarizing findings.
- `DOPP Presentation.pptx`: Slide deck for project presentation.
- `requirements.txt`: Python dependency list.

---

## 👥 Team

**DOPP Group 11 – TU Wien**
- Ilija Filipovski
- Marko Pajkovski
- Dario Jugo
- Mirjana Sadikovikj

---

## ✅ Conclusion

This analysis shows how country-level indicators and institutional strategies affect global university rankings. Results suggest that while investment in education is critical, its impact varies based on structural and regional factors. The methodology developed here can be extended for more granular or predictive insights in future research.
