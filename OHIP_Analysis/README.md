# OHIP-14 Surgical Outcomes Analysis

## 📘 Overview

This project analyzes oral health–related quality of life (OHRQoL) following orthognathic (jaw) surgery using the OHIP-14 survey instrument. Data were collected at 3, 6, and 12-month postoperative timepoints as part of an NIH-led craniofacial research protocol.

The goal was to evaluate the patient recovery trajectory and determine whether early improvements in OHRQoL were statistically and clinically significant.

---

## 🎯 Objectives

- Assess trends in OHIP-14 scores post-surgery
- Identify statistically significant changes over time
- Determine if early recovery (month 3) is a meaningful outcome window
- Support future study design with evidence-backed recommendations

---

## 🧰 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- REDCap (data collection)
- Jupyter Notebook
- Clinical research best practices
- Basic statistical testing (paired comparisons, descriptive stats)

---

## 📊 Methods

1. **Data Preparation**  
   - Imported de-identified OHIP-14 data from REDCap exports  
   - Cleaned data: managed missing values, ensured longitudinal consistency  
   - Mapped OHIP item responses into domain scores (e.g., functional limitation, psychological discomfort)

2. **Statistical Analysis**  
   - Calculated mean OHIP-14 scores at each timepoint (3, 6, 12 months)  
   - Visualized score trends using line plots  
   - Assessed changes using basic comparative statistics (e.g., paired t-tests or difference-in-means)

---

## 💡 Key Findings

- Statistically significant improvement in OHRQoL by **month 3** post-surgery  
- Minimal additional improvements observed at months 6 and 12  
- Suggests early recovery as a key phase in patient outcome trajectories  
- Proposed using **3-month follow-up** as a meaningful primary endpoint in future studies

---

## ⚠️ Limitations

- Small sample size may limit generalizability  
- Missing data at certain timepoints reduced completeness  
- Limited demographic diversity in the dataset  
- Future protocols may benefit from increased early follow-up frequency and broader patient inclusion

---

## 🧭 Next Steps

- Explore subgroup analysis (e.g., age, gender, surgical type)
- Expand study to include larger patient cohort
- Consider validating findings against other PROMs (e.g., SF-36, EQ-5D)

---

## 👩‍⚕️ About the Author

I’m a certified Physician Assistant supporting NIH surgical outcomes research with a growing focus on clinical data analysis and health informatics. This project is part of my transition portfolio into data analytics roles focused on healthcare and real-world evidence.

---

## 📁 Files

- `ohip_analysis.ipynb` – Jupyter notebook with full analysis workflow  
- `ohip_cleaned.csv` – Cleaned de-identified OHIP-14 dataset (if shareable)  
- `images/` – Visualizations and plots used in the analysis

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/your-name) or explore my portfolio at [GitHub](https://github.com/your-username).
