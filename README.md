📊 Statistical Analysis of Boston Housing Data

📌 Project Overview

This project explores the **Boston Housing dataset** through data visualization and statistical analysis. The aim was to identify patterns in housing prices and examine relationships between various socioeconomic and structural factors.
The analysis applies **graphical methods** to understand data distribution and **statistical hypothesis testing** to validate findings.

## 🔍 Objectives

* Visualize and summarize the housing dataset.
* Identify relationships between housing price and predictor variables.
* Apply statistical tests (t-test, correlation, regression, ANOVA) to test hypotheses.
* Interpret p-values to decide whether to accept or reject null hypotheses.

---

## 📈 Data Visualization Techniques

To gain insights, I represented the data using:

* **Box Plots** → To detect outliers and compare distributions.
* **Scatter Plots** → To explore relationships between median home value and predictors (e.g., RM, LSTAT).
* **Histograms** → To examine the distribution of numerical variables.
* **Bar Plots** → To summarize categorical variables and compare averages.

---

## 📊 Statistical Analysis Performed

1. **t-Test**

   * Compared means between groups (e.g., high vs. low crime rate areas).
   * Evaluated whether differences in housing values were statistically significant.

2. **Correlation Analysis**

   * Computed Pearson correlation coefficients between variables.
   * Found strong negative correlation between LSTAT (% lower status population) and MEDV (median house value).

3. **Regression Analysis**

   * Built a linear regression model to predict housing prices using multiple predictors.
   * Interpreted coefficients to understand variable influence.

4. **ANOVA (Analysis of Variance)**

   * Tested whether housing values differed significantly across categorical variables (e.g., proximity to Charles River).
   * Used p-values to confirm statistical significance.

---

## 📌 Hypothesis Testing Approach

* **Null Hypothesis (H₀):** No relationship between predictor and housing prices.
* **Alternative Hypothesis (H₁):** A significant relationship exists.
* **Decision Rule:** If p-value < 0.05 → Reject H₀, accept H₁.

**Findings:**

* LSTAT, RM, and PTRATIO showed statistically significant effects on housing prices.
* Location-based factors (e.g., proximity to Charles River) also influenced prices.

---

## ✅ Key Results

* Positive correlation between **number of rooms (RM)** and house value.
* Negative correlation between **LSTAT** and house value.
* Regression model explained a large portion of variability in housing prices.
* Several hypotheses were rejected, confirming strong links between socioeconomic factors and housing values.

---

## 🛠️ Tools & Libraries

* Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels)
* Jupyter Notebook

---

## 📂 Repository Structure

* `data/` → Boston housing dataset
* `notebooks/` → Jupyter notebooks for visualization and analysis
* `results/` → Graphs, regression outputs, and statistical summaries

---

## 🎯 Conclusion

This project demonstrates the application of **exploratory data analysis, hypothesis testing, and regression modeling** on real-world housing data. It highlights how statistical methods can provide actionable insights into socioeconomic and urban planning challenges.

---

⚡ Pro tip: You should also add a few **graphs (boxplot, regression line, correlation heatmap)** as images in your README for extra impact.

Do you want me to also **make a short “Project Highlights” version** (like 4–5 bullet points) so you can use it directly on your LinkedIn “Projects” section?

