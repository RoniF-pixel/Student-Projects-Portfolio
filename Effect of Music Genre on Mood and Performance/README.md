# Effect of Music Genre on Mood and Performance

## 📌 Project Overview
This project examines how different music genres affect employee mood and task performance in a workplace setting. Originally inspired by a student research idea, the recreated version here uses simulated data and reflects a professional environment.

## 🎯 Objective
To explore whether music genre (Classical vs. Pop vs. Silence) influences mood and task performance among working adults.

##  Tools Used
- [x] SPSS  
- [ ] R 

Simulated experimental data modeled after a workplace scenario

##  Study Design
- Design: Randomized between-subjects experiment

- Participants: Employees from a midsize tech company (n ≈ 90)

- Conditions:

  - Group 1: Classical music

  - Group 2: Pop music

  - Group 3: Silence (control)

- Measures:

  - pre_mood: Mood rating before the task (1–10 scale)

  - post_mood: Mood rating after listening to music

  - task_score: Accuracy on a timed logic puzzle

## 📊 Statistical Methods
- Descriptive statistics

- ANCOVA to assess mood improvement (post-mood ~ group + pre-mood as covariate)

- One-way ANOVA to compare task performance across groups

- Post-hoc tests for group comparisons (if significant)

## 📈 Key Results (Simulated Data)
- Mood:

   - Participants in the Classical music group reported significantly improved mood compared to Silence and Pop groups (p < .05)

- Performance:

   - No significant differences in task performance across groups

- These findings align with research suggesting that classical music may improve emotional states but not necessarily cognitive performance in short tasks.

##  Ethics & Privacy
- The dataset is entirely simulated to model a realistic workplace study

- No real employee data is shared

##  Reproducibility
- SPSS dataset available in [music_mood_performance.sav]()

- Statistical output and visualizations in [music_effect_results.pdf]()

- ANCOVA & ANOVA syntax included in [SPSS_syntax.txt]()


