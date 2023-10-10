# SAT Scores Exploration: Charter vs. Public Schools in Dallas County (2015-2021) - A Deep Dive into Economic Disparities and Teacher Salaries
## Overview
This project offers a deep analysis of SAT scores from charter and public schools across Dallas County from 2015 to 2021. While the primary aim is to compare charter and public schools, a secondary focus dives into the nuances of economic disparities among students and the potential correlation of teacher salaries with SAT scores.

## Table of Contents
+ ### Dataset Description
+ ### Avenues of Exploration
+ ### Value Proposition
+ ### Quick Stats
+ ### Visualizations
+ ### Conclusions
+ ### References

## Dataset Description
The dataset encompasses SAT scores from various schools across Dallas County, categorized as either charter or public. Each entry captures:

+ Type (Charter/Public)
+ Year (from 2015 to 2021)
+ Economic Status: Economically Disadvantaged or Not.
+ Teacher Salary: Average base pay for teaching staff.
+ Average SAT Score

## Null & Alternate Hypotheses
1. Public Schools vs. Charter Schools SAT Score:
Null Hypothesis: The average SAT scores for public schools are equal to those of charter schools.
Alternate Hypothesis: The average SAT scores for public schools are not equal to those of charter schools.
  + Given the data provided, one might use a paired t-test for each year (as the data appears to be paired by year) to test this hypothesis. The significance of the result would indicate if there's a consistent difference between the two types of schools over the years.

2. Correlation between Teacher Salary and Overall SAT Score:
Null Hypothesis: There is no correlation between average teacher salaries and overall average SAT scores.
Alternate Hypothesis: There is a correlation between average teacher salaries and overall average SAT scores.

3. SAT Scores: Economically Disadvantaged vs. Not Economically Disadvantaged:
Null Hypothesis: The average SAT scores for Economically Disadvantaged students are equal to those of Not Economically Disadvantaged students.
Alternate Hypothesis: The average SAT scores for Economically Disadvantaged students are not equal to those of Not Economically Disadvantaged students.

## Avenues of Exploration
1. **Performance Trends:** Analyze the evolution of SAT performance over the years.
2. **Charter vs. Public:** Compare average SAT scores between charter and public schools.
3. **Economic Disparity:**  Examine SAT scores based on students' economic status.
4. **Correlation with Teacher Salary:** Delve into any connections between teacher salaries and SAT performance.

## Value Proposition
This analysis endeavors to elucidate the educational landscape of Dallas ISD, benefiting stakeholders such as policymakers, educators, and parents. By understanding these dynamics, informed decisions can be made regarding academic strategies, resource allocation, and more.

## Quick Stats
+ **Total Observations:** 218 School in Dallas County
+ **Number of Charter Schools:** 120
+ **Number of Public Schools:** 98
+ **Average Teacher Salary:** From 2015-2021 51,492.64
+ **Average SAT Score Overall:** 977.83 

## Visualizations
![Public School Average](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Avg%20SAT%20pub%20school.png)
![Charter School Average](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Average%20SAT%20Scores%20for%20All%20Students%20Over%20the%20Years%20in%20Charter%20School.png)
![Average Dallas SAT Score](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Average%20Total%20Scores%20for%20Total%20Students%20in%20Dallas%20County%20Over%20the%20Years.png)
![Base Pay for Total Teaching Staff Over The Year](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Average%20Base%20Pay%20for%20TOTAL%20TEACHING%20STAFF%20Over%20the%20Years.png)

![Average Economically Disadavntage SAT Score](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Average%20Total%20Scores%20for%20Economically%20Disadvantaged%20Students%20in%20Dallas%20County%20Over%20the%20Years.png)
![Average Not Economically Disadvantage SAT Score](https://github.com/BranditoEH/sat_scores_dallas_exploration/blob/main/Graphics/Average%20Total%20Scores%20for%20Not%20Economically%20Disadvantaged%20Students%20in%20Dallas%20County%20Over%20the%20Years.png)






## Conclusions

**1. SAT Score Trends:**
+ Public Schools: SAT scores for public schools showed a noticeable increase from 2015 to 2018 but experienced a slight decrease in subsequent years.
+ Charter Schools: SAT scores for charter schools witnessed a significant rise from 2015 to 2018 but seemed to plateau post-2018.

**2. Public vs. Charter Schools:**
+ Public schools generally outperform charter schools in SAT scores across all the years presented. The gap seems to have been closing between 2017 and 2019, but public schools still maintain an edge.

**3. Teacher Salary Trends:**
+ There has been a general upward trend in teacher salaries from 2015-2020. However, the average base pay in 2020-2021 dropped back to the 2018-2019 level, despite a generally increasing trend before that.
+ No direct correlation can be concluded between teacher salaries and SAT scores just from the data presented, but it's worth noting that while teacher salaries saw their biggest jump between 2015 and 2020, SAT scores for both charter and public schools plateaued or slightly decreased in the last two years of this period.

**4. Economic Disparity in SAT Scores:**
+ Students who are **Not Economically Disadvantaged consistently outperform their Economically Disadvantaged peers** in SAT scores throughout the years .
+ The gap in scores between these two groups appears to be widening slightly, especially from 2018 onwards.

**5. Overall Average Scores:**
+ The overall average SAT scores for all students in Dallas County seem to follow a trend similar to public schools: there's an increase from 2015 to 2018, followed by a stabilization and minor decrease in the subsequent years.

**6. Areas for Further Investigation:**
+ It might be interesting to explore why public schools generally outperform charter schools. Are there differences in resources, teaching methods, or student demographics that influence this outcome?
+ The factors leading to the SAT score plateau post-2018 would be an area of interest. Is there a change in the SAT format, teaching methodologies, or any external factors influencing this?
+ A deeper dive into the widening SAT score gap between Economically Disadvantaged and Not Economically Disadvantaged students could provide insights into areas where targeted interventions might be effective.
It's essential to remember that while these conclusions provide insights, they are based on the data found and may not capture the entire picture. Correlation does not imply causation, and deeper research would be needed to make definitive statements or policy recommendations.

## References
Texas Education Agency
