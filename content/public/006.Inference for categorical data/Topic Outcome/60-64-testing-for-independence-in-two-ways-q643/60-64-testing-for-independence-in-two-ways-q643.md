---
title: College smokers
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
- 6.1.1.6
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
assets:
- sample.html
part1:
  type: number-input
  pl-customizations:
    rtol: 0.1
    weight: 1
    allow-blank: false
    label: 'Lower bound of 95% CI = '
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Upper bound of 95% CI = '
part3:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Required sample size n = '
myst:
  substitutions:
    params_vars_title: College smokers
    params_vars_n: 258
    params_vars_x: 62
    params_vars_CI_low: 18.817
    params_vars_CI_high: 29.245
    params_vars_n_new: 7014.0
    params_vars_ME_description: 1
---
# {{ params_vars_title }}
We are interested in estimating the proportion of students at a university who smoke. Out of a random sample of {{ params_vars_n }} students from this university, {{ params_vars_x }} students smoke.

## Part 1: (a)

Calculate the lower bound of a 95% confidence interval for the proportion of students at this university who smoke. (Reminder: Check conditions.)

### Answer Section

Please enter in a numeric value.

## Part 1: (b)

Calculate the upper bound of a 95% confidence interval for the proportion of students at this university who smoke.

### Answer Section

Please enter in a numeric value.

## Part 1: (c)

In one sentence interpret this interval in context.

### Answer Section

Please enter in a text response.

### pl-answer-panel

We are 95% confident that {{ params.vars.CI_low }}% to {{ params.vars.CI_high }}% of all students at this university smoke.

## Part 2

If we wanted the margin of error to be no larger than {{ params.vars.ME_description}}% at a 95% confidence level for the proportion of students who smoke, how big of a sample would we need?

### Answer Section

Please enter in a numeric value.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)