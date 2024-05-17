---
title: Units of regression
topic: Introduction to linear regression
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 8.1.1.12
difficulty:
- undefined
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- undefined
tags:
- GKF
- matching
assets: null
part1:
  type: matching
  pl-customizations:
    weight: 1
    blank: 'true'
    none-of-the-above: 'true'
myst:
  substitutions:
    params_vars_title: Units of regression
    params_vars_unit1: in
    params_vars_unit2: oz
    params_vars_problem_statement: height (in) from weight (oz)
    params_part1_option1_value: No units
    params_part1_option1_name: Correlation
    params_part1_option2_value: $in$
    params_part1_option2_name: Intercept
    params_part1_option3_value: $\frac{in}{oz}$
    params_part1_option3_name: Slope
    params_part1_option4_value: $oz$
    params_part1_option4_name: Distractor 1
    params_part1_option5_value: $\frac{oz}{in}$
    params_part1_option5_name: Distractor 2
    params_part1_statement1_value: Correlation
    params_part1_statement1_matches: Correlation
    params_part1_statement2_value: Intercept
    params_part1_statement2_matches: Intercept
    params_part1_statement3_value: Slope
    params_part1_statement3_matches: Slope
---
# {{ params_vars_title }}
Consider a regression predicting {{ params.vars.problem_statement }} for a sample of adult males.

## Part 1

What are the units of the correlation coefficient, the intercept, and the slope?

### Answer Section

### pl-answer-panel

Correlation: no units. Intercept: {{ params_vars_unit1 }}. Slope: {{ params_vars_unit1 }}/{{ params_vars_unit2 }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)