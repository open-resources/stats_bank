---
title: Vegetarian college students
topic: Inference for categorical data
author: Alejandro Builes
source: 6.1
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.0
- 6.1.1.1
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
    params_vars_title: Vegetarian college students
    params_part1_ans1_value: 'True'
    params_part1_ans2_value: 'False'
    params_part2_ans1_value: 'False'
    params_part2_ans2_value: 'True'
    params_part3_ans1_value: 'True'
    params_part3_ans2_value: 'False'
    params_part4_ans1_value: 'True'
    params_part4_ans2_value: 'False'
    params_part5_ans1_value: 'True'
    params_part5_ans1_feedback: Incorrect. The standard error isn't halved when the
      sample size is doubled.
    params_part5_ans2_value: 'False'
---
# {{ params_vars_title }}
Suppose that 8% of college students are vegetarians. Determine if the following statements are true or false.

## Part 1

The distribution of the sample proportions of vegetarians in random samples of size 60 is approximately normal since $n \geq 30$.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

Doesn't satisfy success-failure condition.

## Part 2

The distribution of the sample proportions of vegetarian college students in random samples of size 50 is right skewed.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

The success-failure condition is not satisfied. In most samples we would expect $\hat{p}$ to be close to 0.08, the true population proportion. While $\hat{p}$ can be much above 0.08, it is bound below by 0, suggesting it would take on a right skewed shape. Plotting the sampling distribution would confirm this suspicion.

## Part 3

A random sample of 125 college students where 12% are vegetarians would be considered unusual.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

### pl-answer-panel

$SE\_{\hat{p}}=0.0243$, and $\hat{p}=0.12$ is only $\frac{0.12-0.08}{0.0243} = 1.65$ $SEs$ away from the mean, which $0.0243$ would not be considered unusual.

## Part 4

A random sample of 250 college students where 12% are vegetarians would be considered unusual.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

### pl-answer-panel

$\hat{p}=0.12$ is $2.32$ standard errors away from the mean, which is often considered unusual.

## Part 5

The standard error would be reduced by one-half if we increased the sample size from 125 to 250.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

### pl-answer-panel

Decreases the $SE$ by a factor of $\frac{1}{\sqrt{2}}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)