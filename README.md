# Non-Parametric Statistical Analysis

## 📌 Project Overview
This project demonstrates the application of **non-parametric statistical tests** to analyze data that **does not meet parametric assumptions** (e.g., normality).  
Non-parametric tests are commonly used in **actuarial, medical, and financial data** to identify significant differences between groups.

---

## 🎯 Objectives
- Apply **Wilcoxon Rank-Sum / Mann-Whitney test** for comparing 2 groups  
- Apply **Kruskal-Wallis test** for comparing 3 or more groups  
- Generate data visualizations (boxplots, violin plots) for better interpretation  
- Interpret and report results clearly  

---

## 📊 Dataset
- Simulated dataset of scores across 3 groups (A, B, C)  
- Each group contains 15 observations  
- Columns:
  - `Group` → Categorical variable (A, B, C)  
  - `Score` → Numerical variable  

*(If using real data, replace the simulated dataset with your CSV file in the `data/` folder.)*

---

## 🛠 Tools & Software
- **R** (`wilcox.test`, `kruskal.test`, `ggplot2`, `dplyr`)  
- **Python** (`scipy.stats`, `pandas`, `seaborn`, `matplotlib`)  
- Optional: SPSS for verification  

---

## 📈 Methods Used
1. **Wilcoxon Rank-Sum Test**
   - Compares two independent groups  
   - Non-parametric alternative to the independent t-test

2. **Kruskal-Wallis Test**
   - Compares three or more independent groups  
   - Non-parametric alternative to one-way ANOVA

3. **Data Visualization**
   - Boxplots and violin plots to visualize distribution and outliers  

---

## 📉 Key Findings *(Example from simulated data)*

- **Wilcoxon Test (Group A vs B)**  
  - p-value = 0.048 → Significant difference between groups A and B

- **Kruskal-Wallis Test (Groups A, B, C)**  
  - p-value = 0.005 → At least one group differs significantly

- **Visualizations**  
  - Boxplots show median differences  
  - Violin plots show distribution and spread of each group

---

## 🎓 Skills Demonstrated
- Non-parametric hypothesis testing  
- Statistical interpretation of non-normal data  
- Data visualization using R / Python  
- Clear documentation and reporting  


## 📁 Repository Structure

## 📁 Repository Structure

├── data/
├── scripts/
├── results/
├── report/
└── README.md




## 📎 Author
**Hillary Mike**  
BSc Actuarial Science with IT – Year 4  
[Portfolio](https://mike-hillary.github.io) | [GitHub](https://github.com/mike-hillary)

---

## 🔗 References
- Kaplan, E. L., & Meier, P. (1958). Non-parametric estimation from incomplete observations. *Journal of the American Statistical Association*.  
- Conover, W. J. (1999). *Practical Nonparametric Statistics*.  
- SciPy Documentation: https://docs.scipy.org

