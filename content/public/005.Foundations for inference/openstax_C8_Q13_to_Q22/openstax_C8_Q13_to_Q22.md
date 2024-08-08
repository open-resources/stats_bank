---
title: Weight of Heads of Lettuce
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
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
part5:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N,B
    variables: mu,sigma
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\text{EBM} = $
part7:
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
    none-of-the-above: true
part8:
  type: multiple-choice
  pl-customizations:
    weight: 1
part9:
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
    none-of-the-above: true
    options-placement: bottom
myst:
  substitutions:
    params_vars_title: Weight of Heads of Lettuce
    params_x_bar: 1.9
    params_sigma: 0.12
    params_sample_stdev: 0.19
    params_sample_size: 18
    params_other_sample_size: 36
    params_alpha1: 0.01
    params_confidence1: 99
    params_z_score1: 2.58
    params_alpha2: 0.05
    params_confidence2: 95
    params_z_score2: 1.96
    params_part6_confidence: 99
    params_part6_z_score: 2.58
    params_part4_option1_value: The mean weight of a head of lettuce.
    params_part4_option2_value: The mean weight of all heads of lettuce.
    params_part4_statement1_value: $X$
    params_part4_statement1_matches: The weight of a head of lettuce.
    params_part4_statement2_value: $\bar{X}$
    params_part4_statement2_matches: The mean weight of a sample of 18 heads of lettuce.
    params_part7_option1_value: $\text{CL} = 98\%$
    params_part7_option2_value: $\text{CL} = 90\%$
    params_part7_statement1_value: CI 1
    params_part7_statement1_matches: $\text{CL} = 99\%$
    params_part7_statement2_value: CI 2
    params_part7_statement2_matches: $\text{CL} = 95\%$
    params_part8_ans1_value: The interval is larger because the level of confidence
      decreased. If the only change made in the analysis is a change in confidence
      level, then all we are doing is changing how much area is being calculated for
      the normal distribution. Therefore, a smaller confidence level results in larger
      areas and larger intervals.
    params_part8_ans1_feedback: Please try again!
    params_part8_ans2_value: The interval is smaller because the level of confidence
      increased. If the only change made in the analysis is a change in confidence
      level, then all we are doing is changing how much area is being calculated for
      the normal distribution. Therefore, a larger confidence level results in smaller
      areas and smaller intervals.
    params_part8_ans2_feedback: Please try again!
    params_part8_ans3_value: The interval is smaller because the level of confidence
      decreased. If the only change made in the analysis is a change in confidence
      level, then all we are doing is changing how much area is being calculated for
      the normal distribution. Therefore, a larger confidence level results in larger
      areas and larger intervals.
    params_part8_ans3_feedback: Please try again!
    params_part8_ans4_value: The interval is greater because the level of confidence
      increased. If the only change made in the analysis is a change in confidence
      level, then all we are doing is changing how much area is being calculated for
      the normal distribution. Therefore, a larger confidence level results in larger
      areas and larger intervals.
    params_part8_ans4_feedback: Nice work!
    params_part9_option1_name: CL-Increase
    params_part9_option1_value: The confidence level would increase.
    params_part9_option2_name: CL-Decrease
    params_part9_option2_value: The confidence level would decrease.
    params_part9_option3_name: EBM-Increase
    params_part9_option3_value: The error bound would increase.
    params_part9_option4_name: EBM-Decrease
    params_part9_option4_value: The error bound would decrease.
    params_part9_option5_value: The sample size would increase.
    params_part9_option6_value: The sample size would decrease.
    params_part9_statement1_value: What would happen if 36 heads of lettuce were sampled
      instead of 18, and the error bound remained the same?
    params_part9_statement1_matches: CL-Increase
    params_part9_statement2_value: What would happen if 36 heads of lettuce were sampled
      instead of 18, and the confidence level remained the same?
    params_part9_statement2_matches: EBM-Decrease
---
# {{ params_vars_title }}
A sample of {{ params.sample_size }} heads of lettuce was selected. Assume that the population distribution of head weight is normal. The weight of each head of lettuce was then recorded. The mean weight was {{ params.x_bar }} pounds with a standard deviation of {{ params.sample_stdev }} pounds. The population standard deviation is known to be {{ params_sigma }} pounds.

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

Match the random variables $X$ and $\bar{X}$ to the right definition

### Answer Section

### pl-answer-panel

As the sample size increases, there will be less variability in the mean, so the interval size decreases.

## Part 5

Please define the distribution that should be used. (Ex. $exp(1)$, $N(0,1)$, $B(5, 0.5)$)

### Answer Section

### pl-answer-panel

$X \sim N({{ params.x_bar }}, \frac{ {{ params_sigma }} }{\sqrt{ {{ params.sample_size }} }})$

## Part 6

What should the error bound be for the confidence interval with {{ params.part6_confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part6_ans }}

## Part 7

Please match the following confidence intervals to their Confidence Level.

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

## Part 8

Please select the answer that identifies and explains the what the difference between a {{ params_confidence1 }}% confidence interval and a {{ params_confidence2 }}% confidence interval would be.

### Answer Section

- {{ params_part8_ans1_value }}
- {{ params_part8_ans2_value }}
- {{ params_part8_ans3_value }}
- {{ params_part8_ans4_value }}

## Part 9

Please match each of the scenarios to the correct outcome.

### Answer Section

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)