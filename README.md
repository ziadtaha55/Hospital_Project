# 🏥 Hospital Project

This repository contains a **Hospital Data Analytics Dashboard** and supporting files.  
The analysis explores hospital encounters, costs, coverage, procedures, and patient readmissions using **Power BI**.

---

## 🎯 Objectives & Questions

### Objective 1: Encounters Overview
1. **How many total encounters occurred each year?**  
   - ~27.9K encounters (2012–2022), with peaks in 2014 and 2022 (>3.5K).  
   - 📊 See: `Total Encounters & Procedures Overview.png`

2. **What percentage of all encounters belonged to each encounter class?**  
   - Ambulatory (~45%) was most common, followed by outpatient (~20%) and urgent care (~15%).  
   - 📊 See: `Procedures and Payer Analysis.png`

3. **What percentage of encounters were over 24 hours vs under 24 hours?**  
   - Under 24h: ~95.9%  
   - Over 24h: ~4.1%  
   - 📊 See: `Total Encounters & Procedures Overview.png`

---

### Objective 2: Cost & Coverage Insights
1. **How many encounters had zero payer coverage?**  
   - 13.59K encounters (~48.7%) had no coverage.

2. **Top 10 most frequent procedures and average base cost?**  
   - Health assessments, hospice care, and depression screenings (avg $1K–$4K).  

3. **Top 10 procedures with the highest average base cost?**  
   - Electrical cardioversion (~1.38K) was the highest, followed by thrombectomy and hemodialysis.  

4. **Average total claim cost for encounters, by payer?**  
   - Medicaid > $6K (highest).  
   - Medicare & Dual Eligible (lowest).  
   - 📊 See: `Procedures and Payer Analysis.png`

---

### Objective 3: Patient Behavior Analysis
1. **How many unique patients were admitted each quarter over time?**  
   - Consistent admissions, some peaks >600 patients per quarter.  
   - 📊 See: `Patient Demographics & Readmission Data.png`

2. **How many patients were readmitted within 30 days?**  
   - 9.81K (≈35.2%) were readmissions within 30 days.  
   - 📊 See: `Total Encounters & Procedures Overview.png`

3. **Which patients had the most readmissions?**  
   - Mrs. Kimberly Collier & Mr. Mariano O’Kon (>1,000 readmissions).  
   - 📊 See: `Patient Demographics & Readmission Data.png`

---

## 📊 Dashboards
- ![Patient Demographics & Readmission Data](Patient%20Demographics%20%26%20Readmission%20Data.png)  
- ![Procedures and Payer Analysis](Procedures%20and%20Payer%20Analysis.png)  
- ![Total Encounters & Procedures Overview](Total%20Encounters%20%26%20Procedures%20Overview.png)  

---

## ✅ Key Insights
- 27.9K encounters recorded (2012–2022).  
- Ambulatory was the largest encounter class (~45%).  
- ~48.7% of encounters had **no payer coverage**.  
- Frequent procedures: health assessments, hospice care, depression screening.  
- Medicaid showed the **highest average cost** (> $6K).  
- ~35% of encounters were readmissions within 30 days.  
- Some patients had **>1,000 readmissions**.  

---

## 📂 Files in Repo
- `Hospital_Dashboard.pbix` → Power BI dashboard.  
- `Hospital_Final_Project.xlsx` → Supporting dataset.  
- `Patient Demographics & Readmission Data.png`  
- `Procedures and Payer Analysis.png`  
- `Total Encounters & Procedures Overview.png`  
- `README.md` (this file).  

---

👨‍⚕️ *This project highlights key patterns in hospital utilization, costs, and patient readmission behavior.*
