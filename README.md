
# 📊 Examining Bias in the VI-SPDAT: Machine Learning, Housing Placement, and Systemic Intervention
Graduate Capstone Final Github


This project explores the use of supervised machine learning models to predict VI-SPDAT assessment scores based on wellness and demographic data, The initial scope of the project sought to uncover biases in VI-SPDAT scores, but the model's performance was not much better than chance. This project has become a defining part of my graduate school experience, and I hope that it leads to data and its ability to improve the real world. 

---

## 📁 Data Viz Link:
An accompanying data vizualization that explores the VI-SPDAT and LA's homelessness profile. 
[https://github.com/ajeunel](https://public.tableau.com/app/profile/ajeune.lynch/viz/Capstone_Tableau_17458003946070/Dashboard1)

If the link in the Tableau Public dashboard is has issues, please view the articles here: 

https://themarkup.org/show-your-work/2023/02/28/how-we-investigated-l-a-s-homelessness-scoring-system
https://ceo.lacounty.gov/ardi/bpeh/
---

## 📌 Project Overview

This capstone project investigates:
- How accurately VI-SPDAT scores can be predicted using wellness subscores and demographic data.
- Housing placement outcomes by race,gender and age 
- Los Angeles's County's targeted efforts at reducing homelessness for its Black residents

---

## Notes
- This codebook is far from perfect, and serves as an exploration on testing different ML models. Human-centered data is difficult to use, but its analysis can reveal truths that may save lives.
- CSV files are uploaded to show each step of the process.
- The Python codebook contains use of the y_coef for a model that was being trained. This information was used to test the sample size against the whole group and to plot predicted vs. acutal rates of housing placement. With an AUC = 0.605, the model did not sufficiently predict beyond happenstance, so it was not used in the analysis and will not have a corresponding .csv file. 

---

## 💬 Credits

Created as part of a Master's capstone project on ethical machine learning for human services assessment tools.
