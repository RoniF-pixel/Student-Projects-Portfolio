# Color and Memory Recall Project

## Project Description
This project is a **simulated experimental study** exploring the relationship between **font color** and **memory recall**, as well as **subjective word familiarity**. It is based on a prior undergraduate research project supervised and mentored by **Ronak Fathi**. The goal is to investigate whether color—specifically red, blue, or black—has any influence on how well people remember words and how familiar those words feel.

The dataset, analysis, and report are all created for instructional and demonstrative purposes, aimed at illustrating key principles in experimental design and non-parametric statistical analysis.

---

## Contents

### Files Included:
- **`color_memory_recall_data.csv`**: Simulated dataset of participant scores
- **`color_memory_analysis.Rmd`**: Full R Markdown report with visualizations, analysis, and interpretation
- **`README_Color_Memory_Project.md`**: This file, describing the project scope and contents

---

## Variables in Dataset
| Variable      | Description                                          |
|---------------|------------------------------------------------------|
| `Group`       | Font color group (Red, Blue, Black)                 |
| `Recall`      | Number of words recalled correctly (0–12 scale)     |
| `Familiarity` | Word familiarity rating (1–7 Likert scale)          |

---

## How to Run the Analysis
1. Open the `color_memory_analysis.Rmd` file in RStudio.
2. Make sure `color_memory_recall_data.csv` is in the same directory.
3. Install the required packages:
```r
install.packages(c("tidyverse", "psych", "FSA", "rstatix", "knitr"))
```
4. Click **Knit** to render the report to HTML.

---

## Statistical Techniques Used
- **Histogram plots** and **descriptive statistics** for distribution checking
- **Skewness and kurtosis** to justify use of non-parametric tests
- **Kruskal-Wallis test** for group comparisons (recall & familiarity)
- **Dunn’s test with Bonferroni correction** for post-hoc comparisons
- **Boxplots** for visual comparison between font color groups

---

## Summary of Key Results
- **Recall**: Red text showed **marginally better recall** (p = 0.06), suggesting increased saliency or attention.
- **Familiarity**: No statistically significant differences between the color groups.

---

## Author & Attribution
**Mentor**: *Ronak Fathi*  
This simulation is modeled after a real student-led project mentored by Ronak Fathi. It reflects best practices in experimental design and statistical reporting in the behavioral sciences.

---
**Disclaimer**: This dataset and project are entirely simulated and meant for educational and demonstrative purposes only.


