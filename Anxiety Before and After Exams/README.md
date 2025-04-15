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

Simulated time-series data based on known anxiety patterns in test-taking contexts

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
- Anxiety peaked 1 day before the exam and dropped significantly after (p < .001)

- Anxiety 1 week before was significantly lower than 1 day before (p < .01)

- Post-exam anxiety returned to near-baseline levels

- These simulated results reflect well-documented patterns of anticipatory stress and relief post-assessment.

##  Ethics & Privacy
- The dataset is fully simulated and anonymized

- No actual participant data is used or shared

##  Reproducibility
- SPSS dataset available in [anxiety_exam_timing.sav]()

- Output plots and statistical tables in [anxiety_exam_results.pdf]()

- Full SPSS syntax in [SPSS_within_subjects_syntax.txt]()
