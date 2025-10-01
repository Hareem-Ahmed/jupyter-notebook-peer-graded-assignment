📊 Statistical Analysis of Boston Housing Data

📌 Overview

This project analyzes the **Boston Housing dataset** using data visualization and hypothesis testing methods. The aim was to identify factors influencing median home values and test for statistical significance using different techniques.

The analysis covers:

* Data visualization (Boxplot, Bar Plot, Scatter Plot, Histogram)
* Hypothesis testing (t-test, Correlation, ANOVA, Regression)
* Interpretation of p-values to accept or reject null hypotheses

📊 Analysis Steps

1. **Boxplot – Median Value of Owner-Occupied Homes (MEDV)**

   * Visualized the distribution of median housing values.
   * Tested whether proximity to the Charles River affected house prices.
   * **Result:** Houses near the river had significantly higher median values (p < 0.05).

2. **Bar Plot – Charles River Variable**

   * Compared the distribution of houses bounded vs. not bounded by the Charles River.

3. **Boxplot – MEDV vs Age Groups**

   * Grouped houses into 3 categories:

     * ≤ 35 years
     * 35–70 years
     * ≥ 70 years
   * Compared median housing values across age groups.
   * **Result:** Significant differences existed between groups (p < 0.05, ANOVA).

4. **Scatter Plot – Nitric Oxide (NOX) vs Non-Retail Business Acres (INDUS)**

   * Analyzed the relationship between NOX concentration and the proportion of industrial land use.
   * **Result:** Positive correlation confirmed (p < 0.05).

5. **Histogram – Pupil-Teacher Ratio (PTRATIO)**

   * Showed the distribution of PTRATIO across different towns.

6. **Regression – Weighted Distance to Employment Centers (DIS)**

   * Tested if distance from employment centers predicted median house value.
   * **Result:** Negative relationship found (as distance increased, MEDV decreased).

📌 Hypothesis Testing Summary

* **t-Test:** Significant difference in housing values near Charles River (Reject H₀).
* **Correlation:** NOX and INDUS positively correlated (Reject H₀).
* **ANOVA:** Significant differences in MEDV across housing age groups (Reject H₀).
* **Regression:** Distance to employment centers negatively impacted MEDV.

✅ Key Findings

* Location and environment strongly affect housing prices.
* Median home value increases with proximity to the Charles River.
* Higher NOX levels are associated with more industrial land use.
* Distance from employment centers negatively impacts housing value.
* House age categories show significant pricing differences.

 🛠️ Tools & Libraries

* **Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels
* **Jupyter Notebook**

🔎 Note

This analysis was originally completed as part of an **IBM Data Science course assignment**. This has been documented and structured here as a standalone project to demonstrate **statistical analysis, hypothesis testing, and visualization techniques**.
