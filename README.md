# Cookie Cats A/B Test Analysis

Cookie Cats is a popular mobile puzzle game by Tactile Entertainment. Players connect tiles of the same color to clear levels. This project analyzes an A/B test where the first gate was moved from level 30 to level 40, focusing on its impact on player retention.

## Overview

This repository contains the analysis of an A/B test conducted on Cookie Cats to evaluate the effect of moving the first gate from level 30 to level 40 on player retention. The analysis includes ETL (Extract, Transform, Load) processes, data visualization, outlier management, and statistical hypothesis testing.

## Visualizing Data Insights

Explore the data trends and insights gained from analyzing player game rounds and retention rates.

![Box Plot](https://github.com/srkirot/Mobile_Games_AB_Testing/assets/166246544/c588ad5f-6c2b-469f-8797-02fe52401e82)
*Box plot of Number of Games Played*

![Bar Plot](https://github.com/srkirot/Mobile_Games_AB_Testing/assets/166246544/3dbe923d-1028-4f68-872e-c87e2d0e84cc)

*Bar plot of Count of Observations by Version*

## Analyzing Player Retention

Understand how the change in gate placement influenced player retention after one and seven days.

- **Retention for gate 30:**
  - Day 1: 44.82%
  - Day 7: 19.02%

- **Retention for gate 40:**
  - Day 1: 44.23%
  - Day 7: 18.20%

## Hypothesis Testing

- H0: 𝜇1=𝜇2 (There is no significant difference in retention between gate 30 and gate 40)
- H1: 𝜇1≠𝜇2 (There is a significant difference in retention between gate 30 and gate 40)

Statistical tests were performed to determine significant differences between gate 30 and gate 40.

- **Student's t-test for retention 7:**
  - p-value = 0.0016 (significant difference found)

- **Levene's test for equality of variances:**
  - p-value = 0.0744 (similar variances for retention 1)
  - p-value = 0.0016 (different variances for retention 7)

## Conclusion

Your results indicate that:

- There is a significant difference in 7-day retention between gate 30 and gate 40.
- The variances of retention 1 are similar between both groups.

## Next Steps

Explore further insights or expand the analysis to other game metrics.
