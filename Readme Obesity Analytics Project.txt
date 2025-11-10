# USA Obesity Analytics Dashboard (Python + Excel + Power BI)

## 📌 Project Overview

This project delivers a complete end‑to‑end **data analytics workflow** using CDC‑style obesity data. It includes **data cleaning (Excel), Python preprocessing, SQLite querying, and an interactive Power BI dashboard**. The goal is to understand **yearly trends, geographic variation, and demographic factors influencing obesity** across the United States.

This serves as a **portfolio‑ready project** demonstrating analytical thinking, data modelling, visualization, and storytelling.

---

## ✅ Key Objectives

* Analyze obesity trends (2011–2023 range depending on dataset slice).
* Compare obesity across **gender, age, race/ethnicity, income, and education**.
* Identify **high‑obesity states** and understand socio‑economic patterns.
* Build an interactive **Power BI dashboard** with slicers, KPIs, and insights.
* Demonstrate an end‑to‑end reporting workflow.

---

## 🗂️ Project Pipeline (Step-by-Step)

### **1. Data Extraction (Excel)**

* Loaded the raw CDC CSV file in Excel.
* Filtered rows where Topic = **Obesity**.
* Kept only required columns.
* Cleaned missing values (Unknown for Age/Sex/Education/Income/Race).
* Exported final cleaned file: `small_obesity_cdc.csv`.

### **2. Data Cleaning & Processing (Python)**

Performed in Jupyter/Colab.

* Imported CSV using pandas.
* Verified numeric types.
* Replaced NaNs with "Unknown".
* Optional: wrote dataset into **SQLite** for SQL queries.

### **3. SQL Analysis (SQLite)**

Executed by connecting pandas to SQLite.

* Derived averages by year, sex, education, income, and race.
* Retrieved Top 10 states.
* Exported query results for Power BI use.

### **4. Visualization (Power BI)**

Built a clean 2‑page dashboard:

* **Page 1:** KPIs, obesity trend by year, top 10 states, gender chart.
* **Page 2:** Age, Education, Income, Race breakdown.
* Added slicers for dynamic filtering.
* Applied a custom professional theme.

### **5. Insights & Storytelling**

* Obesity increased over time, peaking around **37% in the 2023 slice**.
* Southern states remain consistently high.
* Obesity increases with age and decreases with education/income.
* Gender gap: women slightly higher than men.
* Racial disparities persist (Black & Hispanic groups highest).

---

## 🧩 Tools & Technologies

* **Python:** pandas, sqlite3
* **Excel:** Pre‑cleaning, filtering
* **SQLite:** Querying, grouping
* **Power BI Desktop:** Dashboard creation
* **GitHub:** Repository management

---



## 📁 Repository Structure

```
/USA_Obesity_Analytics
 ├── data
 │    └── small_obesity_cdc.csv
 ├── notebooks
 │    ├── 01_clean_and_sqlite.ipynb
 │    └── 02_visualizations.ipynb
 ├── powerbi
 │    └── USA_Obesity_Analysis.pbix
 └── README.md
```


## 🚀 How to Run Locally

### **1. Clone the repository**

```bash
git clone https://github.com/yourusername/USA_Obesity_Analytics.git
```

### **2. Open notebooks**

Use Jupyter or Google Colab.

### **3. Open Power BI Dashboard**

Open file from:

```
powerbi/USA_Obesity_Analysis.pbix
```

---

## 📌 Future Enhancements

* Add BMI trend modeling
* Include physical activity and nutrition variables
* Build a predictive model for obesity risk

---

## 👤 Author

**Shwet Anand**
Data Analyst | Healthcare Analytics | Python | Power BI

---

## ✅ License

Open-source. Free to use for educational and portfolio purposes.
