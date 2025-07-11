# 🦷 Longitudinal Analysis of Oral Health-Related Quality of Life Using OHIP-14

## 📘 Overview

This project analyzes changes in oral health–related quality of life (OHRQoL) following orthognathic (jaw) surgery, using the OHIP-14 survey instrument. Data were collected at four key timepoints: **pre-op**, **3 month post-op**, **6 month post-op**, and **1 year post-op**. 

The goal was to evaluate whether surgery leads to statistically and clinically meaningful improvements across multiple domains, using patient-reported outcomes (PROs) in a real-world longitudinal setting.

---

## 🎯 Objectives

- Assess trends in OHIP-14 scores over time following surgery
- Identify domains with statistically significant change
- Determine when the most rapid improvement in OHRQoL occurs
- Support the clinical understanding of recovery trajectories and support future study design with evidence-backed recommendations

---

## 🧰 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Statistical testing (paired t-tests, slope calculations)
- Visualizations of patient recovery trajectories

---

## 📊 Methods

1. **Data Preparation**
   - Cleaned and reshaped OHIP-14 data for three postoperative timepoints
   - Verified scoring system for the OHIP-14 instrument
   - Converted long-format survey data into a format suitable for plotting and comparison

2. **Analysis & Visualization**
   - Computed summary statistics by domain and timepoint
   - Performed paired t-tests between baseline and follow-up scores
   - Calculated slopes of score change to assess rate of recovery
   - Visualized trends in both total OHIP scores and domain-specific changes

---

## 💡 Key Findings

- Significant reductions in total OHIP-14 scores were observed following surgery
- The **steepest slope** of improvement occurred between **baseline and month 3**, suggesting rapid recovery in early postoperative phase
- Continued improvement occurred through 1 year post-op, but at a slower rate
- Psychological and functional domains showed marked early gains

---

## ⚠️ Limitations

- Small sample size limits generalizability of findings  
- Some missing data at later timepoints reduced analytic power  
- External clinical variables (e.g., surgical complexity, patient comorbidities) were not included in this analysis

---

## 🧭 Next Steps

- Apply same methodology to larger and more diverse cohorts  
- Conduct subgroup analysis by demographic or surgical factors  
- Integrate with additional clinical data to explore predictors of recovery

---

## 👩‍⚕️ About the Author

I'm a certified Physician Assistant and NIH research professional transitioning into clinical data analytics. I work with surgical outcome data, REDCap databases, and real-world patient-reported metrics. This project is part of my applied data portfolio.

---

## 📁 Project Files

- `Longitudinal Analysis of OHIP.ipynb` – Full notebook with data processing, visualizations, and interpretation  
- `README.md` – Summary of methodology and findings  
- *(Note: Data file not included due to privacy constraints)*

---

