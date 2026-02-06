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
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 4
    allow-blank: false
    allow-fractions: false
    allow-partial-credit: true
    label: $CI_{ {{ params.confidence }}\% } = $
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{Margin of Error} = $
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n_{CL={{params.higher_confidence}}\%} = $
myst:
  substitutions:
    params:
      vars:
        title: Census Form Length
      x_bar: 8.4
      sigma: 2.3
      sample_size: 215
      other_sample_size: 365
      alpha: 0.1
      confidence: 90
      z_score: 1.6448536269514722
      higher_confidence: 99
      higher_z_score: 2.5758293035489004
      part6:
        ans1:
          value: The confidence level would decrease because a smaller sample size
            requires a smaller critical value to keep the margin of error the same.
          feedback: Try again please!
        ans2:
          value: The confidence level would increase because a smaller sample size
            requires a larger critical value to keep the margin of error the same.
          feedback: Correct!
        ans3:
          value: The confidence level would stay the same because the margin of error
            did not change.
          feedback: Try again please!
        ans4:
          value: TThere is not enough information to determine what happens.
          feedback: Try again please!
---
# {{ params.vars.title }}
The U.S. Census Bureau conducts a study to determine the time needed to complete the short form. The Bureau surveys {{ params.sample_size }} people. The sample mean is {{ params.x_bar }} minutes. There is a known standard deviation of {{ params.sigma }} minutes. The population distribution is assumed to be normal.

## Part 1

Identify the sample mean

### Answer Section

Please enter a numeric value in.

## Part 2

Identify the standard deviation

### Answer Section

Please enter a numeric value in.

## Part 3

Identify the sample size

### Answer Section

Please enter a numeric value in.

## Part 4

What is the {{ params.confidence }}% confidence interval?

### Answer Section

Please enter numeric values in both boxes.

## Part 5

What is the margin of error for the confidence interval with {{ params.confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

## Part 6

If the Census did another survey, kept the margin of error the same, and surveyed {{ params.other_sample_size }} people instead of 200, what would happen to the level of confidence? Why?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Part 7

Suppose the Census needed to be {{ params.higher_confidence }}% confident of the population mean length of time. Without changing the margin of error from part 6, how many people would need to be surveyed?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)