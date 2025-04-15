## 📌 Project Overview
This project investigates how sleep quality impacts academic performance in university students. Designed as a predictive, cross-sectional study, the recreated version here is based on a real student-led research project, using simulated data for demonstration in my portfolio.

## 🎯 Objective
To examine whether sleep quality (as measured by the Pittsburgh Sleep Quality Index, PSQI) is a significant predictor of GPA, after accounting for demographic and lifestyle factors.

## 🛠 Tools Used
- [x] SPSS  
- [ ] R 

Simulated dataset modeled on the structure of a real academic survey study

## 📊 Data Description
**Source:** Simulated responses modeled after actual undergraduate research

**Participants:** Undergraduate students from three universities (n ≈ 120)

**Variables:**

- gpa: Self-reported Grade Point Average

- psqi_score: Total score on the Pittsburgh Sleep Quality Index

- gender: Binary-coded variable (0 = male, 1 = female)

- major: Categorical (dummy-coded) academic field

- caffeine_use: Number of caffeinated beverages consumed daily

## 📐 Statistical Methods
- Descriptive statistics for all variables

- Hierarchical multiple regression analysis:

- Step 1: Predict GPA from gender and major

- Step 2: Add psqi_score to test its incremental predictive value

- Step 3: Add caffeine_use as a lifestyle covariate

- Multicollinearity diagnostics (VIF, tolerance)

- Post-hoc visualization: Scatterplot of GPA vs. PSQI, with confidence bands

## 📈 Key Results (Simulated Data)
- Sleep quality (PSQI) was a statistically significant predictor of GPA even after controlling for gender and major

- ΔR² = 0.14, p < .01

- Caffeine use did not significantly enhance the model

- No multicollinearity issues were detected across predictors

- These results are based on simulated data intended to reflect realistic findings in health psychology and education research.

##  Ethics & Privacy
- The dataset is completely simulated and anonymized for educational purposes

- No actual participant responses are included in this portfolio

##  Reproducibility
- SPSS dataset available in [sleep_gpa.sav]()

- Full regression output and visualizations are compiled in [sleep_results.pdf]()


