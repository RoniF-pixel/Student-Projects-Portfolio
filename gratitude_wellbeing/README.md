# Gratitude Journaling and Well-being Study

This project is a simulated longitudinal study designed to examine the effects of **gratitude journaling** on **subjective happiness** and **stress levels** over a 2-week period. The analysis was conducted in **R** using a combination of mixed-effects modeling, t-tests, and multiple imputation for missing data. This project was developed as part of a teaching portfolio to demonstrate mentoring in applied psychological research and data analysis.

##  Study Design

- **Design**: 2-week longitudinal intervention
- **Participants**: 60 simulated subjects
- **Groups**: 
  - **Gratitude Journaling** group
  - **Neutral Journaling** (control) group

##  Measures

| Measure | Description |
|--------|-------------|
| Happiness (pre & post) | Subjective Happiness Scale |
| Weekly Stress (pre & post) | Self-rated weekly stress |
| Compliance | Number of days journaled (out of 14) |

##  Analysis

- **Mixed-effects model**: Examined changes in happiness across time and between groups with random intercepts per subject.
- **Independent t-test**: Compared stress reduction between groups.
- **Multiple imputation**: Simulated missing data handling using the `mice` package.

##  Dataset

The dataset `gratitude_wellbeing_data.csv` contains:
- `SubjectID`: Unique identifier for each participant
- `Group`: Gratitude or Neutral
- `Happiness_Pre`, `Happiness_Post`
- `Stress_Pre`, `Stress_Post`
- `Compliance_14Day`: Number of days the participant completed the journaling task

##  Key Results

- **Happiness**: Gratitude group showed significantly greater improvement (_p_ = 0.0011)
- **Stress**: Gratitude group experienced a larger reduction in stress (_p_ = 0.019)

##  How to Run

To reproduce this project:
1. Download all files.
2. Open `gratitude_wellbeing_report.Rmd` in RStudio.
3. Knit to HTML or run chunks interactively.

##  References

- Emmons, R. A., & McCullough, M. E. (2003). Counting blessings versus burdens.
- Lyubomirsky, S., Sheldon, K. M., & Schkade, D. (2005). Pursuing happiness.
- Field, A. (2013). *Discovering Statistics Using R*.

##  Author

**Ronak Fathi**  
Portfolio of student mentoring in experimental psychology and statistics

