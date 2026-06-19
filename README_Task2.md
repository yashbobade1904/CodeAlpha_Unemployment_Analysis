# CodeAlpha Data Science Internship — Task 2: Unemployment Analysis with Python

## 📌 Objective
Analyze unemployment rate data across Indian states, clean and explore it, investigate the impact of Covid-19, identify key patterns, and present insights relevant to economic/social policy.

## 📂 Datasets
- `Unemployment_in_India.csv` — Region × Rural/Urban, monthly, May 2019 – Jun 2020
- `Unemployment_Rate_upto_11_2020.csv` — Region with zone & lat/long, monthly, Jan 2020 – Oct 2020

## 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn (visualization)

## 🔍 Approach
1. **Data Cleaning** — removed blank rows, stripped whitespace from column names/values, parsed dates.
2. **EDA & Trend Analysis** — national monthly trend (Rural vs Urban), state-wise averages, zonal comparison.
3. **Covid-19 Impact Analysis** — compared pre-Covid, peak-lockdown (April 2020), and post-peak unemployment rates.
4. **Relationship Analysis** — correlation between labour participation rate and unemployment rate.

## 📊 Key Insights
- National unemployment **more than doubled (~137% increase)** in April 2020 versus the pre-Covid baseline.
- **Urban areas were hit harder** than rural areas during the lockdown spike.
- Impact was **highly uneven across states** — some saw 30+ percentage point spikes, others barely moved.
- **South and West zones recovered fastest**, while other zones took longer to return to pre-Covid levels.
- Labour participation rate and unemployment rate showed only a **weak correlation**, suggesting job-creation policy matters as much as workforce-participation policy.

## ▶️ How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
2. Keep both CSV files in the same folder as the notebook.
3. Open `Task2_Unemployment_Analysis.ipynb` in Jupyter / VS Code / Google Colab and run all cells.

## 📁 Repo Contents
- `Task2_Unemployment_Analysis.ipynb` — full analysis & visualization code with outputs
- `Unemployment_in_India.csv`, `Unemployment_Rate_upto_11_2020.csv` — datasets
- `README.md` — this file

---
*Submitted as part of the CodeAlpha Data Science Internship.*
