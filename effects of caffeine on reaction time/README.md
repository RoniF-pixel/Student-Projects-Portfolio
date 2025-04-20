# Caffeine and Reaction Time: Simulated Experimental Study

This project simulates a lab experiment to study the **effects of caffeine on human reaction time**. It was created as part of a mentoring portfolio, showcasing experimental design, data analysis, and reporting in R Markdown. The project introduces students to real-world data analysis techniques used in psychology, health sciences, and statistics.

---

##  Study Design

- **Type**: Between-subjects experimental design
- **Groups**:
  - **Caffeine**: Received caffeinated coffee
  - **Decaf**: Received decaffeinated coffee (placebo)
  - **NoDrink**: Received no beverage
- **Measurements**:
  - **Reaction Time**: Go/No-Go Task (in milliseconds)
  - **Heart Rate**: Before and after treatment
  - **Gender**: Male / Female

---

##  Files

- `caffeine_reaction_time_data.csv` — Simulated dataset (60 participants)
- `caffeine_study_report.Rmd` — Full R Markdown report with code, analysis, and interpretation
- `README.md` — This file

---

##  Statistical Analysis

- **Two-way ANOVA**: Reaction Time ~ Group * Gender
- **ANCOVA**: Reaction Time adjusted for baseline heart rate
- **Heart Rate Change**: Analyzed with one-way ANOVA and Tukey post-hoc test
- **Assumption Checks**: Normality of residuals, homogeneity of variances

---

##  Key Findings

- **Caffeine** significantly improves reaction time (*p < .01*)
- No significant effect of **Gender**
- **Heart rate** increased significantly only in the caffeine group

---

##  How to Run

1. Open the `caffeine_study_report.Rmd` file in RStudio.
2. Ensure you have the following R packages installed:
install.packages(c("car", "knitr"))
3. Click Knit to generate the HTML report.

---

##  References

- Lieberman, H. R., et al. (1987). The effects of low doses of caffeine on human performance and mood.
- Smith, A. (2002). Effects of caffeine on human behavior.
- Field, A. (2013). Discovering Statistics Using R.

---

##  Author
Ronak Fathi
Mentor | Statistician | Data Analyst

Project created as part of a teaching portfolio for mentoring in experimental design and data analysis.


