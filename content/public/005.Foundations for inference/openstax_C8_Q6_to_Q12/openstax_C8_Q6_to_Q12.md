---
title: Census Form Length
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 8.1
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.4
- 5.1.1.6
- 5.1.1.7
difficulty:
- medium
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
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    allow-blank: false
    label: $\bar{x} = $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    allow-blank: false
    label: $\sigma = $
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n = $
part4:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N,B
    variables: mu,sigma
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\text{EBM} = $
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
part8:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n_{CL={{params.higher_confidence}}\%} = $
myst:
  substitutions:
    params_vars_title: Census Form Length
    params_x_bar: 7.9
    params_sigma: 2.2
    params_sample_size: 180
    params_other_sample_size: 30
    params_alpha: 0.05
    params_confidence: 95
    params_z_score: 1.96
    params_graph_z_score: 1.96
    params_higher_confidence: 99
    params_higher_z_score: 2.58
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Correct!
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Try again please!
    params_part7_ans1_value: The level of confidence would decrease because decreasing
      $n$ makes the confidence interval wider, so at the same error bound, the confidence
      level decreases.
    params_part7_ans1_feedback: Correct!
    params_part7_ans2_value: The level of confidence would increase because increasing
      $n$ makes the confidence interval smaller, so at the same error bound, the confidence
      level increases.
    params_part7_ans2_feedback: Try again please!
    params_part7_ans3_value: The level of confidence would increase because decreasing
      $n$ makes the confidence interval smaller, so at the same error bound, the confidence
      level increases.
    params_part7_ans3_feedback: Try again please!
    params_part7_ans4_value: The level of confidence would decrease because increasing
      $n$ makes the confidence interval wider, so at the same error bound, the confidence
      level decreases.
    params_part7_ans4_feedback: Try again please!
---
# {{ params_vars_title }}
The U.S. Census Bureau conducts a study to determine the time needed to complete the short form. The Bureau surveys {{ params.sample_size }} people. The sample mean is {{ params.x_bar }} minutes. There is a known standard deviation of {{ params_sigma }} minutes. The population distribution is assumed to be normal.

## Part 1

Identify the sample mean

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\bar{x} = {{ params.x_bar }}$

## Part 2

Identify the standard deviation

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\sigma = {{ params_sigma }}$

## Part 3

Identify the sample size

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$n = {{ params.sample_size }}$

## Part 4

Please define the distribution that should be used. (Ex. $exp(1)$, $N(0,1)$, $B(5, 0.5)$)

### Answer Section

### pl-answer-panel

$X \sim N({{ params.x_bar }}, \frac{ {{ params_sigma }} }{\sqrt{ {{ params.sample_size }} }})$

## Part 5

Is the following graph a proper representation of the {{ params_confidence }}% confidence interval?

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Part 6

What should the error bound be for the confidence interval with {{ params_confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part6_ans }}

## Part 7

If the Census did another survey, kept the error bound the same, and surveyed {{ params.other_sample_size }} people instead of 200, what would happen to the level of confidence? Why?

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}
- {{ params_part7_ans3_value }}
- {{ params_part7_ans4_value }}

### pl-answer-panel

As the sample size increases, there will be less variability in the mean, so the interval size decreases.

## Part 8

Suppose the Census needed to be {{ params.higher_confidence }}% confident of the population mean length of time. Without changing the error bound from part 6, how many people would need to be surveyed?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part8_ans }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)