# EdTech-Student-Dropout-Prediction
# 🎓 Student Dropout Early Warning Analysis

> Identifying at-risk students in online education using 
> the Open University Learning Analytics Dataset (OULAD)

---

## 📌 Project Overview

Student dropout is one of the biggest challenges facing online 
universities. This project analyses 32,593 student records to 
identify demographic and academic warning signs that predict 
whether a student will withdraw before completing their course.

**This project demonstrates:**
- Real-world educational data cleaning and preparation
- Exploratory data analysis on imbalanced demographic data
- Actionable insight generation for an EdTech context

---

## 📊 Dataset

| File | Records | Description |
|---|---|---|
| studentInfo.csv | 32,593 | Demographics + final results |
| studentAssessment.csv | 173,912 | Assessment scores |
| studentRegistration.csv | 32,593 | Registration dates |
| assessments.csv | 206 | Assessment metadata |
| courses.csv | 22 | Course structure |

**Source:** [Open University Learning Analytics dataset](https://analyse.kmi.open.ac.uk/open-dataset)

---

## 🔍 Key Findings

### Overall Dropout Rate
!(https://github.com/Shikha997/EdTech-Student-Dropout-Prediction/blob/main/Overall%20Dropout%20Rate.png)
Overall Dropout Rate.png
- Overall dropout rate: 31.2%
  Dropout rate - 0 previous attempts: 30.6%
  Dropout rate - 1 previous attempt:  34.9%
  Students with 1 prev attempt are 1.1x more likely to drop out
- Withdrawal is the second most common outcome after Pass

---

### Age is a Strong Dropout Predictor
!(https://github.com/Shikha997/EdTech-Student-Dropout-Prediction/blob/main/Dropout%20Rate%20by%20Age.png)
- Younger students (0-35) showed the highest withdrawal rates
- Students aged 55+ were the most likely to complete their course

---

### Previous Failures Increase Risk
!(https://github.com/Shikha997/EdTech-Student-Dropout-Prediction/blob/main/Dropout%20by%20Previous%20Attempts.png)
- Students attempting a module for the second or third time
  had significantly higher dropout rates
- Suggests repeated failure is a compounding risk factor

---

### Education Level Matters
!(https://github.com/Shikha997/EdTech-Student-Dropout-Prediction/blob/main/Dropout%20by%20Education%20Level.png)
- Students with lower entry qualifications withdrew more frequently
- HE-qualified students showed stronger completion rates

---

### Deprivation Linked to Dropout
!(https://github.com/Shikha997/EdTech-Student-Dropout-Prediction/blob/main/Dropout%20Rate%20by%20Deprivation%20Band%20IMD.png)
- Students in the most deprived areas (0-10% IMD) had 
  noticeably higher dropout rates
- Suggests financial and social pressures play a role

---

## 🔍 Key Findings

- **31.2%** of students withdrew before completing 
  their course — nearly 1 in 3

- Students in the **most deprived areas (0-10% IMD)** 
  dropped out at **37.2%** compared to **25.9%** for the 
  least deprived making them **44% more likely** to withdraw. 
  This suggests financial and social pressures are 
  significant barriers to course completion.

- Students **retaking a module** after a previous failure 
  showed a **14% higher dropout rate** (34.9% vs 30.6%), 
  indicating prior struggle is a compounding risk factor.

- Deprivation shows a **clear gradient** dropout rate 
  consistently falls as wealth increases, from 37.2% 
  down to 25.9% across IMD bands.

## 💡 Recommendations for EdTech Platforms

Based on these findings, early intervention should target:

1. 🔴 **Students under 35** registering for the first time
2. 🔴 **Students with previous failed attempts** — proactive outreach
3. 🔴 **Students in high deprivation bands** — financial support signposting
4. 🟡 **Students with lower entry qualifications** — additional learning support

---

## 🛠️ Tools & Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Skills demonstrated** — Data cleaning, EDA, 
  missing value treatment, data visualization

---

## 🚀 How to Reproduce This Analysis

1. Clone this repo:
```bash
git clone https://github.com/yourusername/student-dropout-analysis
```

2. Download the OULAD dataset from the 
[official page](https://analyse.kmi.open.ac.uk/open_dataset)

3. Place all CSV files in the `/data` folder

4. Open `notebook.ipynb` in Jupyter and run all cells

---

