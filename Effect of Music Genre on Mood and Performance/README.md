# Effect of Music Genre on Mood and Performance

## 📌 Project Overview
This project examines the effect of background music on mood and cognitive performance in a workplace setting. The original study design was adapted from student research, and recreated using simulated data from a randomized experiment involving employees at a midsize tech company.

## 🎯 Objective
To investigate:

- Whether music genre (Classical vs. Pop vs. Silence) affects post-task mood, after controlling for pre-task mood.

- Whether music genre influences task performance (logic puzzle accuracy).

##  Tools Used
- [x] SPSS  
- [ ] R 

Simulated experimental data modeled after a workplace scenario

##  Study Design
- Source: Simulated

- Design: Randomized between-subjects (3 groups)

- Variables:

  - group: Type of music (Classical, Pop, Silence)

  - pre_mood: Mood before task (scale 0–10)

  - post_mood: Mood after task (scale 0–10)

  - task_score: Number of correct answers on a logic puzzle task

- Sample size: 20

  - Classical: 7

  - Pop: 6

  - Silence: 7

## 📊 Statistical Methods
- Descriptive statistics

- ANCOVA to assess mood improvement (post-mood ~ group + pre-mood as covariate)

- One-way ANOVA to compare task performance across groups

- Post-hoc tests for group comparisons (if significant)

## 📈 Key Results (Simulated Data)
- ANCOVA:

  - Significant main effect of music genre on post-mood after controlling for pre-mood.

  - Classical music group had significantly higher mood scores than Pop and Silence groups.

- ANOVA on Task Score:

  - No significant differences in task performance across music conditions.

  - Post-hoc: No pairwise comparisons were statistically significant.

Note: These results are based on a small, simulated sample and should be interpreted accordingly.
##  Ethics & Privacy
- The dataset is entirely simulated to model a realistic workplace study

- No real employee data is shared

##  Reproducibility
- SPSS dataset available in [music_mood_performance.sav]()

- Statistical output and visualizations in [music_effect_results.pdf]()

- ANCOVA & ANOVA syntax included in [SPSS_syntax.txt]()


