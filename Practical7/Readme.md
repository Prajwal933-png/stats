📘 README : Regression and Correlation Analysis
🎯 Objective

This practical explores how different factors influence teaching evaluations using regression analysis and correlation tests. The goal is to understand relationships among instructor characteristics such as gender, beauty, and age, and their impact on teaching ratings.

🧠 Concepts Covered

Simple Linear Regression

ANOVA (Analysis of Variance)

Correlation Analysis

Statistical Significance Testing (T-test & p-values)

Model Interpretation using StatsModels

📂 Dataset

Dataset Used: teachers_rating_an.csv
The dataset contains information about university instructors, including:

Gender — Male/Female

Age — Instructor’s age

Beauty — Rated beauty score

Rating — Teaching evaluation score

⚙️ Methods and Tasks

Regression with T-test:

Examines whether gender affects teaching evaluation ratings.

Uses an OLS regression model to test for significant differences.

Regression with ANOVA:

Tests whether beauty scores differ by age group.

Performs one-way ANOVA to check for significant variation among age groups.

Correlation Analysis:

Measures the relationship between beauty and teaching evaluation scores.

Uses Pearson’s correlation coefficient (r) to assess linear association strength.

🧩 Tools & Libraries

Python 3.x

pandas — Data handling

statsmodels — Regression and ANOVA

scipy — Statistical testing

matplotlib (optional) — Visualization

🚀 How to Run

Open the notebook PRACTICAL 7.ipynb in Jupyter Notebook or Google Colab.

Ensure the dataset teachers_rating_an.csv is in the same directory.

Run each cell sequentially to reproduce the analysis and outputs.

📊 Expected Outcomes

Statistical models quantifying how gender influences ratings.

ANOVA table showing whether beauty varies significantly by age.

Correlation coefficient and p-value describing the relationship between beauty and teaching ratings.

🧾 Conclusion

From this analysis, we can conclude:

Gender and Ratings:
Regression with a T-test indicates whether there is a statistically significant difference in teaching evaluations based on gender.

Beauty and Age (ANOVA):
The ANOVA results reveal if beauty scores vary significantly across different age groups. A non-significant result would imply that beauty ratings are consistent across ages.

Beauty and Ratings (Correlation):
The correlation analysis shows the strength and direction of association between beauty and teaching evaluations. A positive and significant correlation suggests that instructors with higher beauty scores tend to receive better teaching evaluations.
