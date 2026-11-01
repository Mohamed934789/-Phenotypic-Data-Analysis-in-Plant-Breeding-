# 🌱 Phenotypic Data Analysis in Plant Breeding

## 📌 Project Overview
This project focuses on analyzing phenotypic data from **Recombinant Inbred Lines (RILs)** and their parents (*Xena* & *H94*).
The goal was to explore how **leaf traits** and **sugar composition** influence **biomass** and **seed yield**, and to identify potential **elite lines** for plant breeding.

---

## 📂 Dataset
The dataset included:
- **RIL population data** (traits measured for each line).
- **Parent data (Xena & H94)** for comparison.

### Key Traits:
- **Leaf Traits**:
  - LL1, LL2 → Leaf length (replicates)
  - LW1, LW2 → Leaf width
  - LA1, LA2 → Leaf area
  - SLA1, SLA2 → Specific leaf area

- **Biochemical Traits**:
  - Sucrose
  - Glucose
  - Fructose

- **Yield-related Traits**:
  - Biomass (BIO)
  - Seed weight (Sweight)

---

## 🔍 Analysis Workflow
1. **Data Cleaning**
   - Handling missing values
   - Averaging replicates (e.g., `LL_avg`, `LW_avg`, `SLA_avg`)
   - Creating derived traits (e.g., `TotalSugar = Sucrose + Glucose + Fructose`)

2. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics
   - Distribution plots for each trait
   - Scatter plots for trait relationships

3. **Correlation Analysis**
   - Checking correlations between yield traits and other variables
   - Heatmaps to visualize relationships

4. **Parent vs RIL Comparison**
   - Benchmarking RILs against parents
   - Highlighting elite lines outperforming both parents

5. **Visualization**
   - Python (Matplotlib & Seaborn)
   - Power BI interactive dashboard

---

## 📊 Key Insights
- **Biomass and Seed Weight** are strongly correlated.
- Leaf traits (length, width, area) are explored for association with yield traits.
- **Sucrose content** has an observed association on seed weight compared to glucose & fructose.
- Some RILs performed better than parents (Xena & H94) → **potential elite lines**.
- Trade-off observed between SLA (efficiency) and high yield.

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn)
- **Power BI** (interactive dashboards & visualizations)

---


## 📌 Future Work
- Apply statistical tests (ANOVA, t-test) to validate differences.
- Use ML models to predict yield from traits.
- Expand dataset with more replicates and environmental conditions.

---
## 👤 Author

**M. Kassab**
📧 Email: [m.kassab934@gmail.com](mailto:m.kassab934@gmail.com)
💼 LinkedIn: [Mohamed Kassab](https://www.linkedin.com/in/mohamed-kassab-b1b0482a1/)


## Reproduce and interpret

Install `requirements.txt` with Python 3.12 and run `Python.ipynb` here. XLS reading uses xlrd. The original workbook and PBIX are retained. Numeric-only correlations and relative inputs support clean execution. Reports are local ignored outputs. Correlations do not establish causal influence; no significance tests or prediction benchmark are claimed.
