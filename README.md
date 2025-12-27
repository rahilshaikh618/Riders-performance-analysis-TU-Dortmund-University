# Rider Performance Analysis – TU Dortmund University

## 📌 Project Overview

This project presents a statistical analysis of rider performance data derived from a cycling manager game. The objective is to investigate whether rider performance differs across **rider classes** and **stage classes**, and whether an interaction exists between these two factors.

The analysis was developed as part of the **Application Report for the M.Sc. in Data Science at TU Dortmund University**, following strict academic and statistical guidelines.

---

## 🎯 Objectives

* Analyze rider performance measured by **points**
* Compare performance across different **rider classes**
* Examine performance variation across **stage classes**
* Test for **interaction effects** between rider class and stage class
* Apply appropriate **descriptive and inferential statistical methods**

---

## 📊 Dataset Description

The dataset originates from a cycling manager game where riders earn points based on their performance in individual stages of a multi-stage tour.

### Key Variables

* **Points** – Metric variable representing rider performance
* **Rider Class** – Nominal categorical variable

  * All Rounder
  * Climber
  * Sprinter
  * Unclassified
* **Stage Class** – Nominal categorical variable

  * Flat
  * Hilly
  * Mountain

The dataset contains no missing values and is suitable for statistical analysis.

---

## 🧠 Methodology

The project follows a structured statistical workflow:

1. **Data Inspection**

   * Data loading, structure validation, missing value checks

2. **Descriptive Analysis**

   * Mean, median, standard deviation, range
   * Grouped analysis by rider class and stage class
   * Boxplot visualization for performance comparison

3. **Inferential Analysis**

   * One-way ANOVA:

     * Rider class effect
     * Stage class effect
   * Two-way ANOVA:

     * Interaction between rider class and stage class
   * Assumption checks (normality, variance homogeneity, independence)

4. **Interpretation & Discussion**

   * Practical interpretation in a cycling context
   * Limitations and future work

---

## 📈 Key Techniques Used

* Descriptive Statistics
* Data Visualization (Boxplots)
* One-way ANOVA
* Two-way ANOVA with Interaction
* Statistical Assumption Assessment

---

## 🛠️ Technologies & Tools

* **Python 3**
* **pandas** – Data manipulation
* **matplotlib / seaborn** – Visualization
* **statsmodels** – Statistical modeling (ANOVA)
* **Jupyter Notebook**

---

## 📁 Project Structure

```
├── data/
│   └── riders.csv
├── notebooks/
│   └── TU_Dortmund.ipynb
├── report/
│   └── Application_Report.pdf
├── README.md
```

*(Folder names may vary depending on repository organization.)*

---

## 📄 Academic Context

This project was prepared in accordance with the **TU Dortmund University Application Report Guidelines** for the Master of Science in Data Science program.
All statistical methods are mathematically justified, and results are presented using appropriate academic standards.

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/rider-performance-analysis.git
   ```
2. Navigate to the project directory
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook
   ```
4. Run `TU_Dortmund.ipynb`

---

## 📌 References

* Montgomery, D. C. (2017). *Design and Analysis of Experiments*. Wiley.
* Fahrmeir, L., et al. (2013). *Regression: Models, Methods and Applications*. Springer.
* Python Software Foundation (2023). Python Language Reference.
* Seabold, S., & Perktold, J. (2010). *Statsmodels*.

---

## 👤 Author

**Mohd Rahil**
B.Tech Computer Science & Engineering
Aspiring Data Scientist | M.Sc. Data Science Applicant (TU Dortmund University)

🔗 LinkedIn: [https://www.linkedin.com/in/mohammadrahil142](https://www.linkedin.com/in/mohammadrahil142)

---

## ⭐ If you find this useful

Feel free to ⭐ the repository or connect with me for discussions on data science, statistics, and analytics.

---
