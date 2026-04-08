<img width="1207" height="395" alt="image" src="https://github.com/user-attachments/assets/b07c7924-9c88-4668-9649-686cc28d0fe9" />

# 📊 Employee Absenteeism Analysis  
### Cohort-Based & Statistical Approach for HR Decision Making

---

## 📌 Project Summary
This project analyzes employee absenteeism patterns using **categorical cohort analysis** and **statistical sampling techniques** to identify high-risk groups, hidden anomalies, and actionable HR insights.

The analysis uncovers the root causes behind **13,333 lost working hours** and provides **data-driven (evidence-based) recommendations** to improve workforce productivity and reporting accuracy.

---

## 🎯 Business Problem
Organizations often struggle to:
- Identify which employee groups contribute most to absenteeism
- Detect hidden or misclassified absence reasons
- Understand seasonal or operational drivers behind absence spikes

This project addresses these challenges through structured data analysis and cohort segmentation.

---

## 📊 Key Findings

- **High-Risk Cohort Identified**  
  Employees aged **30–45 years** contribute **58% (7,781 hours)** of total absenteeism

- **Data Anomaly Detected ("The Great Unknown")**  
  - 254 absence cases categorized as **"Other" (Code 28)**  
  - Represents **69% of the Adult cohort**  
  - Indicates a major reporting blind spot

- **Seasonal Pattern Discovered**  
  Significant absenteeism spikes observed in:
  - March  
  - October  
  → Suggesting operational pressure or external seasonal factors

---

## 🛠️ Data Source
- Secondary dataset: **Employee Absenteeism (Kaggle)**

---

## 🔄 Data Preparation

- **Reason Mapping**
  - Translated ICD codes (0–28) into descriptive labels
  - Implemented using **Excel VLOOKUP**

- **Feature Engineering (Age Cohort Segmentation)**
  - Dewasa: < 30 years  
  - Muda: 30–45 years  
  - Senior: > 45 years  

---

## 📐 Methodology

### 1. Categorical Cohort Analysis
Segmented employees based on age groups to analyze absenteeism behavior across life stages.

### 2. Statistical Sampling (Slovin’s Formula)

Used to determine representative sample size for anomaly investigation:

```
n = N / (1 + N e²)
```

Where:
- N = 254 (anomalous records)
- e = 5% (margin of error)

➡️ Required sample size: **156 respondents**

---

## 📈 Results

### Absenteeism Distribution

| Age Group        | Total Hours | Percentage |
|-----------------|------------|------------|
| Dewasa (30–45)   | 7,781      | 58.3%      |
| Muda (<30)     | 3,132      | 23.5%      |
| Senior (>45)    | 2,420      | 18.2%      |

---

## 🔍 Key Insight (Anomaly Analysis)

The 254 "Other" category records within the Adult cohort suggest that absenteeism is likely **non-medical**.

**Hypothesis:**
- Employees may belong to the **Sandwich Generation**
- Managing both children and elderly parents
- Leading to unreported personal or domestic responsibilities

---

## 🚀 Future Work

- **Internal vs External Classification**
  - Distinguish between organizational and personal absence drivers

- **Clustering (Machine Learning)**
  - Segment employees into behavioral personas, such as:
    - High Burnout Cluster  
    - Domestic Responsibility Cluster  

---

## 💡 Recommendations

- **Flexible Working Policy (Flexi-Time)**
  - Targeted for employees aged 30–45

- **Workload Evaluation**
  - Focus on peak months: March & October

- **Absence Reporting Redesign**
  - Improve categorization to reduce "Other" usage
  - Enhance data accuracy for future analysis

---

## 🧰 Tools & Skills Demonstrated

- **Microsoft Excel**
  - Pivot Tables  
  - VLOOKUP  
  - IF Functions  
  - Data Visualization  

- **Data Analysis Techniques**
  - Cohort Analysis  
  - Descriptive Analytics  
  - Statistical Sampling (Slovin’s Method)  

- **Business Skills**
  - Data Storytelling  
  - Insight Generation  
  - HR Analytics  

---

## 📂 Repository Guide

To explore the analysis:

1. Open the file:  
   **`Analisis Loyalitas dan Pola Absensi Karyawan.xlsx`**

2. Review:
   - Pivot tables  
   - Cohort segmentation  
   - Absenteeism trends  

---

## 📌 Key Takeaway
This project demonstrates how **simple tools (Excel + statistics)** can uncover **high-impact business insights**, detect hidden data issues, and support **strategic HR decision-making**.
