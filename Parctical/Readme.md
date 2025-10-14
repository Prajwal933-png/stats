
## 🧾 README

### Project Title

*Faculty Demographics and Tenure Analysis*

### Overview

This notebook explores relationships between demographic and professional characteristics of university faculty members using simulated data. The analysis covers tenure status, visible minority representation, age, gender, and teaching evaluation scores.
It demonstrates proficiency in data handling, descriptive statistics, and visualization using Python.

### Objectives

1. Calculate the percentage of visible minorities who are tenured professors.
2. Determine whether the average age differs by tenure status.
3. Compare visualization types to identify the best plot for representing age data.
4. Explain the difference between pyplot.bar() and pyplot.barh() and visualize gender distribution.
5. Find the median evaluation score for tenured professors.

### Technologies Used

* *Python 3*
* *pandas* — Data manipulation
* *NumPy* — Numerical computation
* *Matplotlib / Seaborn* — Data visualization

### How to Run

1. Open the notebook Prajwal4.ipynb in *Jupyter Notebook* or *JupyterLab*.
2. Run each cell sequentially from top to bottom.
3. Review printed outputs and visualizations to understand the findings.

### Data

A synthetic dataset of 100 faculty members is generated using NumPy’s random functions, ensuring reproducibility and realistic distributions for analysis.

---

## 🧩 Conclusion

From the simulated analysis, the following insights can be drawn:

* A certain percentage of visible minority faculty are tenured (value depends on the random seed).
  This provides an estimate of representation among senior faculty.
* The *average age* of tenured professors tends to be *higher* than that of untenured professors, which aligns with expectations due to career progression.
* Among visualizations, *histograms* or *boxplots* effectively represent the distribution of age, providing clear insights into spread and central tendency.
* The difference between pyplot.bar() and pyplot.barh() lies in *orientation* — bar() plots vertical bars, while barh() plots horizontal ones.
* The *median evaluation score* for tenured professors tends to cluster around *4.0–4.5*, suggesting consistently strong performance.

Overall, this notebook illustrates how Python-based data analysis can uncover demographic and academic patterns, even in small or simulated datasets.

---
