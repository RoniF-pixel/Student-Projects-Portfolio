# Mindfulness and Exam Stress Project

## Project Title
**Mindfulness and Exam Stress: A Pre-Post Intervention Simulation**

## Project Description
This project simulates a **within-subjects psychological study** investigating the effect of mindfulness practice on stress levels among final-year undergraduates during exam week. Participants’ stress was assessed using the **DASS-21 Stress Subscale** before and after a one-week mindfulness intervention. They also logged the number of minutes they practiced mindfulness daily.

The study is based on real research mentored by **Ronak Fathi**, simulating the process of data collection, statistical testing, and report writing in an academic setting. It is designed for instructional use in applied psychological statistics and intervention evaluation.

---

## Included Files
- `mindfulness_exam_stress_data.csv` – Simulated dataset (60 participants)
- `Mindfulness_Exam_Stress_Analysis.Rmd` – Full R Markdown file with complete analysis
- `README_Mindfulness_Exam_Stress.md` – This project documentation file

---

## Dataset Description
| Variable           | Description                                                   |
|-------------------|---------------------------------------------------------------|
| `Participant_ID`  | Unique identifier for each participant                        |
| `Practice_Minutes`| Total mindfulness practice time across 7 days (in minutes)    |
| `Stress_Pre`      | Pre-intervention DASS-21 stress score (0–42 scale)            |
| `Stress_Post`     | Post-intervention DASS-21 stress score (0–42 scale)           |
| `Stress_Reduction`| Difference between pre- and post-intervention stress levels   |

---

## Statistical Analysis Overview
All statistical analyses are performed in R using nonparametric and correlational methods:

- **Wilcoxon Signed-Rank Test**: Compared pre- and post-intervention stress scores
- **Effect Size (r)**: Computed from Wilcoxon z-score
- **Spearman Correlation**: Examined the relationship between mindfulness practice and stress reduction
- **Visualizations**: Histogram of reduction and scatterplot of practice vs. reduction

---

## Instructions to Run
1. Open the `.Rmd` file in RStudio.
2. Ensure `mindfulness_exam_stress_data.csv` is in your working directory.
3. Install required R packages:
```r
install.packages(c("tidyverse", "ggpubr", "rstatix", "knitr"))
```
4. Knit the document to HTML or PDF.
   - To render as PDF, update the YAML header:
```yaml
output:
  pdf_document:
    latex_engine: xelatex
```

---

## Key Findings
- Stress significantly reduced following the mindfulness intervention (**p < .001**).
- More minutes of mindfulness practice were moderately correlated with greater stress reduction (**ρ = 0.68, p < 0.001**).
- The effect size from the Wilcoxon test was also computed.

---

## Attribution
**Mentor**: *Ronak Fathi*  
This project simulates a real research design developed under the mentorship of Ronak Fathi and is intended as a teaching tool for research students and analysts studying mindfulness and psychological intervention.

---

**Note**: All data are simulated for educational purposes and do not represent actual participant responses.


