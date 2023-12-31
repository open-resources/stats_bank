---
title: Gender and color preference
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.4
difficulty:
- undefined
randomization:
- 2
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Gender and color preference
    params_part1_ans1_value: 'False'
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: 'True'
    params_part1_ans2_feedback: The entire confidence interval is above 0.
    params_part2_ans1_value: 'True'
    params_part2_ans1_feedback: The lower bound is negative, which contradicts the
      claim that the male proportion is higher.
    params_part2_ans2_value: 'False'
    params_part2_ans2_feedback: The lower bound is negative, which contradicts the
      claim that the male proportion is higher.
    params_part3_ans1_value: 'True'
    params_part3_ans1_feedback: Correct!
    params_part3_ans2_value: 'False'
    params_part3_ans2_feedback: Incorrect!
    params_part4_ans1_value: 'True'
    params_part4_ans1_feedback: Correct!
    params_part4_ans2_value: 'False'
    params_part4_ans2_feedback: Incorrect!
    params_part5_ans1_value: 'False'
    params_part5_ans1_feedback: 'It is simply the negated and reordered values: (0.16,
      0.28).'
    params_part5_ans2_value: 'True'
    params_part5_ans2_feedback: Incorrect!
    params_lower_bound_percent_abs: 28.0
    params_upper_bound_percent_abs: 16.0
    params_lower_bound_percent_abs_p2: 16.0
    params_upper_bound_percent_abs_p2: 28.0
    params_lower_bound: -0.28
    params_upper_bound: -0.16
    params_male_sample_size: 1790
    params_female_sample_size: 3051
---
# {{ params_vars_title }}
A study asked {{ params.male_sample_size }} male and {{ params.female_sample_size }} female undergraduate college students their favorite color. A 95% confidence interval for the difference between the proportions of males and females whose favorite color is black $(p\_{male} - p\_{female})$ was calculated to be ({{ params.lower_bound }}, {{ params.upper_bound }}).
Based on this information, determine if the following statements about undergraduate college students are true or false.

## Part 1

We are 95% confident that the true proportion of males whose favorite color is black is {{ params.lower_bound_percent_abs }}% lower to {{ params.upper_bound_percent_abs }}% higher than the true proportion of females whose favorite color is black.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

## Part 2

We are 95% confident that the true proportion of males whose favorite color is black is {{ params.lower_bound_percent_abs_p2 }}% to {{ params.upper_bound_percent_abs_p2 }}% higher than the true proportion of females whose favorite color is black.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

## Part 3

95% of random samples will produce 95% confidence intervals that include the true difference between the population proportions of males and females whose favorite color is black.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

## Part 4

We can conclude that there is a significant difference between the proportions of males and females whose favorite color is black and that the difference between the two sample proportions is too large to plausibly be due to chance.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

## Part 5

The 95% confidence interval for $(p\_{female} - p\_{male})$ cannot be calculated with only the information given in this exercise.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)