---
title: Orange tabbies
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.0
- 6.1.1.1
- 6.1.1.2
- 6.1.1.3
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
  type: number-input
  pl-customizations:
    rtol: 0.001
    weight: 1
    allow-blank: false
part3:
  type: dropdown
  pl-customizations:
    weight: 1
part4:
  type: dropdown
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Orange tabbies
    params_vars_sample_size1: 30
    params_vars_times: 64
    params_vars_sample_size3: 101
    params_vars_sample_size4: 73
    params_part1_ans1_value: 'True'
    params_part1_ans2_value: 'False'
    params_part3_ans1_value: 'True'
    params_part3_ans2_value: 'False'
    params_part4_ans1_value: 'True'
    params_part4_ans2_value: 'False'
---
# {{ params_vars_title }}
Suppose that 90% of orange tabby cats are male. Determine if the following statements are true or false.

## Part 1

The distribution of sample proportions of random samples of size {{ params.vars.sample_size1 }} is left skewed.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

## Part 2

Using a sample size that is {{ params_vars_times }} times as large will cause the standard error to be how many multiples of itself large?

### Answer Section

Please enter in a numeric value.

### pl-answer-panel

We take the square root of the sample size in the $SE$ formula.

## Part 3

The distribution of sample proportions of random samples of size {{ params.vars.sample_size3 }} is approximately normal.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

### pl-answer-panel

Check whether the independence and success-failure conditions are being met. Take also into account the Central Limit Theorem (CLT).

## Part 4

The distribution of sample proportions of random samples of size {{ params.vars.sample_size4 }} is approximately normal.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

### pl-answer-panel

Check whether the independence and success-failure conditions are being met. Take also into account the Central Limit Theorem (CLT).

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)