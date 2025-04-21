# Perfectionism and Procrastination Project

## Project Overview
This project investigates the relationship between perfectionism and procrastination in academic settings. It is a simulated version of a real research project originally conducted under the mentorship of **Ronak Fathi** with a team of undergraduate psychology students. The purpose of this simulation is to demonstrate how to apply structural equation modeling (SEM) and moderation analysis in the context of psychological traits and academic behavior.

The dataset used here is synthetically generated but mirrors the patterns and analytical strategy of the original research.

## Files Included

- `perfectionism_procrastination_data.csv`: Simulated dataset of 93 student observations.
- `perfectionism_analysis.Rmd`: R Markdown report that includes:
  - Research background
  - Descriptive statistics
  - SEM (path analysis)
  - Model fit assessment (CFI, RMSEA)
  - Moderation analysis (interaction between self-oriented perfectionism and GPA)
  - Full interpretation and discussion
- `README.md`: This file – providing context and usage guidance.

## Variable Descriptions

| Variable              | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `GPA`                | Grade Point Average on a 0–20 scale                                         |
| `SelfOriented`       | Self-Oriented Perfectionism score (e.g., internal high standards)           |
| `SociallyPrescribed` | Socially Prescribed Perfectionism (e.g., perceived external expectations)   |
| `OtherOriented`      | Other-Oriented Perfectionism (expecting others to be perfect)               |
| `Procrastination`    | Score on the Procrastination Assessment Scale – Students (PASS)             |

## Summary of Analysis

### Structural Equation Modeling (SEM)
- Modeled procrastination as a function of three types of perfectionism.
- Significant predictor: **Self-Oriented Perfectionism (β ≈ 0.42, p < .001)**
- Non-significant predictors: Socially Prescribed, Other-Oriented Perfectionism
- Fit indices (CFI, RMSEA) reported to assess model adequacy

### Moderation Analysis
- Investigated whether GPA moderated the effect of Self-Oriented Perfectionism on procrastination
- GPA × Perfectionism interaction was **non-significant**, suggesting GPA does not buffer or amplify the impact

## Instructions to Run the Project

1. Open `perfectionism_analysis.Rmd` in RStudio.
2. Ensure the file `perfectionism_procrastination_data.csv` is in your working directory.
3. Install required R packages (if not already installed):
   ```r
   install.packages(c("tidyverse", "psych", "lavaan", "semPlot", "interactions"))
   ```
4. Knit the R Markdown file to HTML or PDF using the **Knit** button in RStudio.

## About the Mentor

**Ronak Fathi** is a researcher and mentor with experience in guiding undergraduate student projects in psychology and statistics. This simulation project is built on the structure and methodology of a real-world study Ronak supervised, aimed at exploring how individual difference traits affect student academic behavior.

## License & Usage

This project is for **educational and demonstrative purposes** only. The data is not real, but the analysis and approach reflect valid research practices. You are welcome to adapt this project for teaching, training, or personal learning.

---

For questions or collaboration opportunities, please contact [**Ronak Fathi**](https://github.com/RoniF-pixel).


