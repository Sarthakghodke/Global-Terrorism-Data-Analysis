# Global Terrorism Data Analysis (1970–2021)

## 📌 Project Overview
This project performs an end-to-end data analytics study on global terrorism
incidents from 1970 to 2021 using the Global Terrorism Database (GTD).

The goal is to uncover long-term trends, geographic patterns, attack methods,
and the overall impact of terrorism across the world using data analysis and
visualization techniques.

---

## 📂 Dataset Information
- **Source:** Global Terrorism Database (GTD)  
  https://www.start.umd.edu/data-tools/GTD
- **Time Period:** 1970 – 2021
- **Total Records:** ~214,000 incidents
- Due to GitHub file size limitations, a representative processed sample dataset
  is included in this repository.

---

## 🧹 Data Cleaning & Processing
The dataset was cleaned and prepared using Python:

- Removed duplicate and inconsistent records
- Handled missing values across multiple features
- Standardized date, region, and attack-type fields
- Merged datasets from different time periods
- Created a processed dataset suitable for analysis and visualization

Detailed steps are available in the Jupyter notebook.

📘 Notebook: `notebooks/data_cleaning_analysis.ipynb`

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Year-wise terrorism trends
- Regional and country-level distributions
- Attack types and weapon categories
- Casualties and impact metrics

Visualizations were created using Matplotlib and Seaborn.

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was developed to visualize global terrorism
patterns and impacts.

### Key Insights
- Terrorist incidents increased sharply after 2005 and peaked around 2014
- Most attacks were domestic rather than international
- Explosives and firearms were the most commonly used weapons
- A small number of regions accounted for a large share of total incidents

Due to GitHub file size limitations, the Power BI (.pbix) file is not uploaded.
Dashboard screenshots are provided below.

### Dashboard Preview
![Dashboard Overview](images/dashboard_overview.png)

![Impact Analysis](images/impact_analysis.png)

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## 📁 Project Structure
