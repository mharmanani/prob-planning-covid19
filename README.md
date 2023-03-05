# Modelling the Spread of COVID-19 in Indoor Spaces using Automated Probabilistic Planning

This repository is the official implementation of [Modelling the Spread of COVID-19 in Indoor Spaces using Automated Probabilistic Planning](https://www.overleaf.com/read/xhqgwzynbwzb). 

## Abstract
The coronavirus disease 2019 (COVID-19) pandemic has been ongoing for around 3 years, and has infected over 750 million
people and caused over 6 million deaths worldwide at the time of writing. Throughout the pandemic, several strategies for
controlling the spread of the disease have been debated by healthcare professionals, government authorities, and international
bodies. To anticipate the potential impact of the disease, and to simulate the effectiveness of different mitigation strategies, a
robust model of disease spread is needed. In this work, we explore a novel approach based on probabilistic planning and
dynamic graph analysis to model the spread of COVID-19 in indoor spaces. We also endow the planner with means to control
the spread of the disease trough non-pharmaceutical interventions (NPIs) such as mandating masks, vaccines, capacity limits,
and social distancing. We demonstrate that the use of automated probabilistic planning is effective in predicting the amount of
infections that are likely to occur in shared spaces, and that they are capable of designing competent interventions to limit the
spread of the disease

## File Structure
```
data: contains benchmark datasets used to compare the performance of our planners
src
|_ models: contains the domains and planners modelling the problem
|_ script: contains utlity scripts, data analyses, and other useful logic used to supplement the work done by the planners
```