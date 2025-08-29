# 🏅 Olympics Dataset Analysis (1896–2016)

## 📌 Overview
This project performs an **exploratory data analysis (EDA)** of over **270,000 Olympic athlete records** spanning **120 years of Olympic history (1896–2016)**.  
The analysis focuses on **athlete demographics, medal trends, gender participation, and country performance**.  
All work is implemented in **Python** using **Pandas, NumPy, Matplotlib, and Seaborn** inside Jupyter Notebooks.  

---

## 🎯 Objectives
- Understand **athlete demographics**: age, height, weight distributions.  
- Track **medal trends** across sports, countries, and years.  
- Analyze **gender participation** growth over time (Summer & Winter Olympics).  
- Identify **key factors influencing medal-winning performance**.  

---

## 🗂️ Dataset
- `athlete_events.csv` — Records of 270k+ athletes (events, sports, medals, demographics).  
- `noc_regions.csv` — Mapping of National Olympic Committees (NOC) to countries/regions.  
(Source: [Kaggle – 120 years of Olympic history](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results))  

---

## 🔧 Methodology
1. **Data Preprocessing**
   - Loaded and merged `athlete_events.csv` with `noc_regions.csv`.  
   - Handled missing values and duplicates.  
   - Created clean, structured dataframe for analysis.  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of age, height, weight across sports and years.  
   - Medal trends by sport, gender, and country.  
   - Gender participation over time.  
   - Country-wise performance (Top medal winners).  

3. **Visualizations**
   - 📊 Age histograms and medal probabilities.  
   - 📈 Male vs Female participation trends (line plots).  
   - 🌍 Country medal counts (bar plots, heatmaps).  
   - ⚖️ Height–Weight scatter plots colored by medal and gender.  

---

## 📊 Key Insights
- Athletes aged **22–25 most likely to win Gold**; under 20 → Silver/Bronze.  
- **Medal-winning weight range:** typically **70–90 kg**.  
- Women gymnasts: medal probability highest at **40–50 kg**; men above **50 kg**.  
- **Women’s participation** has grown drastically post-1980 in both Summer & Winter Olympics.  
- USA, Russia/USSR, and Germany are historically the **top medal-winning nations**.  

---



## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Olympics-Analysis.git
   cd Olympics-Analysis
