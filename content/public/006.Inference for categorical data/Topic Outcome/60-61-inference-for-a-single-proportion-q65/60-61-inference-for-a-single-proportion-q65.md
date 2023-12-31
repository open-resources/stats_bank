---
title: Gender equality
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.3
- 6.1.1.5
- 6.1.1.6
- 6.1.1.7
- 6.1.1.8
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
- AB
assets: null
part1:
  type: dropdown
  pl-customizations:
    weight: 1
part2:
  type: dropdown
  pl-customizations:
    weight: 1
part3:
  type: dropdown
  pl-customizations:
    weight: 1
part4:
  type: dropdown
  pl-customizations:
    weight: 1
part5:
  type: dropdown
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Gender equality
    params_vars_sample_size: 1985
    params_vars_proportion: 54.0
    params_vars_margin_of_error: 2.19
    params_vars_lower_bound: 51.81
    params_vars_upper_bound: 56.19
    params_vars_margin_of_error_part4: 1.096
    params_vars_selected_option1: If we considered many random samples of 1985 Americans,
      and we calculated 95% confidence intervals for each, 95% of these intervals
      would include the true population proportion of Americans who think it's the
      government's responsibility to promote equality between men and women.
    params_vars_selected_option2: In order to decrease the margin of error to 0.021925203411024982%,
      we would need to quadruple (multiply by 4) the sample size.
    params_part1_ans1_value: 'True'
    params_part1_ans2_value: 'False'
    params_part2_ans1_value: 'False'
    params_part2_ans2_value: 'True'
    params_part3_ans1_value: 'True'
    params_part3_ans2_value: 'False'
    params_part4_ans1_value: 'True'
    params_part4_ans2_value: 'False'
    params_part5_ans1_value: 'True'
    params_part5_ans2_value: 'False'
---
# {{ params_vars_title }}
The General Social Survey asked a random sample of {{ params.vars.sample_size }} Americans the following question: "On the whole, do you think it should or should not be the government's responsibility to promote equality between men and women?" {{ params_vars_proportion }}% of the respondents said it "should be". At a 95% confidence level, this sample has {{ params.vars.margin_of_error }}% margin of error. Based on this information, determine if the following statements are true or false.

## Part 1

We are 95% confident that between {{ params.vars.lower_bound }}% and {{ params.vars.upper_bound }}% of Americans in this sample think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

A confidence interval is constructed to estimate the population proportion, not the sample proportion.

## Part 2

We are 95% confident that between {{ params.vars.lower_bound }}% and {{ params.vars.upper_bound }}% of all Americans think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

The $95$% $CI:$ ${{ params_vars_proportion }}$% $\pm$ ${{ params.vars.margin_of_error }}$%.

## Part 3

{{ params.vars.selected_option1 }}

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

## Part 4

{{ params.vars.selected_option2 }}

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

## Part 5

Based on this confidence interval, there is sufficient evidence to conclude that a majority of Americans think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)