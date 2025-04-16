# Anxiety Before and After Exams

## 📌 Project Overview
This project investigates state anxiety fluctuations in students at different stages surrounding an exam. Simulated data replicates a typical within-subjects time-series design, originally part of a psychological research course exercise.

## 🎯 Objective
To evaluate how anxiety levels change over time — specifically:

- 1 week before,

- 1 day before, and

- immediately after an academic exam.

##  Tools Used
- [x] SPSS  
- [ ] R 

Simulated time-series data based on known anxiety patterns in test-taking contexts.

##  Study Design
- Design: Within-subjects (repeated measures)

- Participants: Undergraduate students (n ≈ 50)

- Measures:

  - anxiety_week_before: STAI-State score 1 week before the exam

  - anxiety_day_before: STAI-State score 1 day before the exam

  - anxiety_after_exam: STAI-State score immediately after the exam

## 📊 Statistical Methods
- Repeated Measures ANOVA

- Mauchly’s Test of Sphericity assessed

- Greenhouse-Geisser correction applied if necessary

- Post-hoc: Bonferroni-corrected pairwise comparisons between time points

- Visual: Line plot with error bars showing anxiety trajectory across time

## 📈 Key Results (Simulated Data)
-Main effect of time was significant: anxiety varied across the three phases.

- Post-hoc tests (Bonferroni-adjusted) showed:

  - Anxiety 1 day before the exam was significantly higher than both:

    - 1 week before (Mean diff = 22.16, p < .001)

    - After the exam (Mean diff = 19.38, p < .001)

  - Anxiety 1 week before was also significantly lower than after the exam (Mean diff = 2.78, p < .001)

##  Ethics & Privacy
- The dataset is fully simulated and anonymized

- No actual participant data is used or shared

##  Reproducibility
- SPSS dataset available in [Anxiety.sav](https://github.com/RoniF-pixel/Student-Projects-Portfolio/blob/main/Anxiety%20Before%20and%20After%20Exams/Anxiety.sav)

- Output plots and statistical tables in [Anxiety.pdf](https://github.com/RoniF-pixel/Student-Projects-Portfolio/blob/main/Anxiety%20Before%20and%20After%20Exams/Anxiety.pdf)

