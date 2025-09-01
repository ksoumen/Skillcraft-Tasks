# Skillcraft-Tasks
This repository is a collection of data analysis and machine learning projects implemented in Python, demonstrating end-to-end workflows from data preprocessing and exploratory data analysis (EDA) to visualization, predictive modeling, and interpretation.
# Data Analysis & Machine Learning Projects in Python

## 📌 Overview
This repository is a collection of **data analysis and machine learning projects** implemented in Python.  
Each project demonstrates a complete workflow — from **data cleaning and preprocessing to visualization, analysis, and modeling**.  

Key domains analyzed:
- 🛍️ Customer Purchase Behavior  
- 🚢 Titanic Dataset (Survival Prediction)  
- 👥 India Population Demographics  
- 🚗 US Accidents Data Analysis  

---

## 🔬 Project 1: US Accidents Data Analysis & Visualization
### Objective
To analyze US traffic accident records and identify patterns across **time, day, weather, lighting, road surface conditions, and causes**.

### Process
- **Data Exploration**: Used `.head()`, `.info()`, `.isnull().sum()` for structure & missing values.  
- **Feature Analysis**:  
  - Accidents by **Hour of Day** → bar chart (rush hours peak).  
  - Accidents by **Day of Week & Hour** → heatmap.  
  - **Top 10 Causes** → horizontal bar chart.  
  - Accidents by **Weather / Lighting / Road Surface** → bar charts.  

### Key Insights
- **Time Factor**: Accidents peak during rush hours (7–9 AM, 3–6 PM).  
- **Day Factor**: Weekdays (esp. Friday) have higher accident density.  
- **Weather**: Most accidents happen in *clear weather* → due to high traffic exposure.  
- **Lighting**: Daytime has more accidents, but night accidents (dark & poorly lit roads) remain critical.  
- **Road Surface**: Majority occur on *dry* roads, not necessarily in adverse weather.  
- **Top Causes**: “Unable to Determine” is common, but also **Failure to Yield, Speeding, Lane Violations, Signal Violations**.  

### Conclusion
- Accidents are influenced more by **human behavior & traffic volume** than weather/road conditions.  
- Preventive focus areas:  
  - Traffic management during peak hours.  
  - Better road lighting at night.  
  - Enforcement of traffic laws.  

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment**: Jupyter Notebook / VS Code  

---
