---
title: Monthly Television Usage
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.0
- 7.1.1.4
- 7.1.1.5
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
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\bar{x}=$
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $s_x=$
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n=$
part4:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $df=$
part5:
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: matrix-component-input
  pl-customizations:
    allow-fractions: true
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\text{CI}=$
    allow-partial-credit: true
part8:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{EBM}=$
part9:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Monthly Television Usage
      sample_size: 105
      mean: 162
      stdev: 33
      df: 104
      lower_bound: 156.48869302193157
      upper_bound: 167.51130697806843
      confidence_level: 91
      error_bound: 5.511306978068428
      other_confidence: 98
      part5:
        option0:
          value: The mean number of hours Americans spend watching television per
            month.
        statement1:
          value: $X$
          matches: The number of hours an American spent watching television per month.
        statement2:
          value: $\bar{X}$
          matches: The mean number of hours spent watching television per month from
            a sample of 105 Americans.
      part6:
        ans1:
          value: $t_{104}$
          feedback: Correct!
        ans2:
          value: $t_{105}$
          feedback: Try again please!
        ans3:
          value: $\operatorname{N}(0,1)$ (Standard Normal)
          feedback: Try again please!
        ans4:
          value: $\operatorname{N}(162, 33)$
          feedback: Try again please!
      part9:
        ans1:
          value: The error bound would decrease because less area would be needed
            to capture the true population mean.
          feedback: Try again please!
        ans2:
          value: The error bound would increase because more area would be needed
            to capture the true population mean.
          feedback: Correct!
        ans3:
          value: The error bound would decrease because more area would be needed
            to capture the true population mean.
          feedback: Try again please!
        ans4:
          value: The error bound would increase because less area would be needed
            to capture the true population mean.
          feedback: Try again please!
        ans5:
          value: The error bound remains the same regardless of the confidence level.
          feedback: Try again please!
---
# {{ params.vars.title }}
{{ params.sample_size }} Americans were surveyed to determine the number of hours they spend watching television each month. It was revealed that they watched an average of {{ params.mean }} hours each month with a standard deviation of {{ params.stdev }} hours. Assume that the underlying population distribution is normal.

## Part 1

Identify $\bar{x}$

### Answer Section

Please enter a numeric value in.

## Part 2

Identify $s_x$

### Answer Section

Please enter a numeric value in.

## Part 3

Identify $n$

### Answer Section

Please enter a numeric value in.

## Part 4

Identify the degrees of freedom.

### Answer Section

Please enter a numeric value in.

## Part 5

Match the random variables $X$ and $\bar{X}$ to the correct definitions.

### Answer Section

## Part 6

Which distribution should you use for this problem?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Part 7

Construct a {{ params.confidence_level }}% confidence interval for the population mean hours spent watching television per month. What is the confidence interval?

### Answer Section

## Part 8

What is the error bound for the {{ params.confidence_level }}% confidence interval you constructed in part 7?

### Answer Section

Please enter a numeric value in.

## Part 9

Why would the error bound change if the confidence level was changed to {{ params.other_confidence }}%?

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}
- {{ params.part9.ans3.value }}
- {{ params.part9.ans4.value }}
- {{ params.part9.ans5.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)