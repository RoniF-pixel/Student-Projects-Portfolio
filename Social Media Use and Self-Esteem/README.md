# Social Media Use and Self-Esteem

## 📌 Project Overview
This project explores how different patterns of social media usage relate to college students’ self-esteem. The study was part of an undergraduate behavioral research series I supervised, recreated here with simulated data for portfolio demonstration purposes.

## 🎯 Objective
To investigate whether the amount and type of social media use (active vs. passive) are associated with self-esteem levels among college students.

##  Tools Used
 - [x] SPSS  
 - [ ] R 

Simulated survey data modeled after actual undergraduate research

## 📊 Data Description
- **Source:** Simulated data created to match the structure and style of a real student study

- **Participants:** Undergraduate students (n ≈ 100)

- **Variables:**

   - self_esteem_score: Total score from the Rosenberg Self-Esteem Scale

   - social_media_use: Average number of hours spent on social media per day

- **use_type:** Categorical indicator of usage style (0 = passive, 1 = active)

- **use_x_type:** Interaction term (computed as social_media_use × use_type)

 ## Statistical Methods
 - Descriptive statistics (means, SDs by group)

 - Spearman correlation (self-esteem vs. hours of use)

 - Multiple linear regression

 - Model: self_esteem_score ~ social_media_use + use_type + use_x_type

 - Scatterplot visualization with fitted regression lines

##  Key Results (Simulated Data)
 - Passive use was significantly negatively associated with self-esteem (p < .05)

 - Active use showed no significant effect

 - The interaction term was not significant, suggesting no differential impact of usage hours by usage type

 - These patterns are typical of findings in the literature on passive vs. active digital behavior and are recreated here for educational demonstration.

 ## Ethics & Privacy
 - The dataset is entirely simulated; no real student data is included

 - All variables and patterns were designed to reflect plausible psychological research outcomes without compromising individual privacy

## Reproducibility
 - SPSS dataset available in [Social Media.sav](https://github.com/RoniF-pixel/Student-Projects-Portfolio/blob/main/Social%20Media%20Use%20and%20Self-Esteem/Social%20Media.sav)

 - Statistical output and scatterplot available in [SocialMedia.pdf](https://github.com/RoniF-pixel/Student-Projects-Portfolio/blob/main/Social%20Media%20Use%20and%20Self-Esteem/SocialMedia.pdf)


