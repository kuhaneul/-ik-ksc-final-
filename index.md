---
layout: home
---

# EX09: Data Analysis for Continuous Improvement

## Summary
For this project, I analyzed anonymized COMP 110 survey data to explore whether students with lower self-reported understanding are more likely to want optional pre-lecture videos.

## Analysis
I combined survey data from two sections and selected the columns `pre_lecture_videos` and `understanding`, both rated on a 1-7 Likert scale. After filtering out empty responses, I produced three visualizations:

**Plot 1: Scatter Plot**
A scatter plot of understanding vs. pre-lecture video demand showing the raw relationship across all respondents.

**Plot 2: Box Plot**
A box plot grouping students by understanding score, showing the distribution of pre-lecture video demand at each level.

**Plot 3: Bar Chart**
A bar chart showing average pre-lecture video demand per understanding level.

## Conclusion
Students who reported lower understanding tended to rate pre-lecture videos as more helpful. This suggests the course should consider producing short optional pre-lecture videos, particularly before topics that historically cause the most confusion. The main trade-off is production time for instructors and the risk that students use videos to skip lecture entirely.