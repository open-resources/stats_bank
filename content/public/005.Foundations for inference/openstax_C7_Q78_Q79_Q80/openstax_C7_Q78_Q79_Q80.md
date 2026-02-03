---
title: Furniture Delivery
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.6
- 5.1.1.7
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\text{Average Wait Time} = $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $p = $
part4:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n = $
myst:
  substitutions:
    params:
      vars:
        title: Furniture Delivery
      start_time: 9
      length: 5
      end_time: 2
      part1:
        ans1:
          value: $X \sim U(0, 5)$
          feedback: You got it!
        ans2:
          value: $X \sim U(9, 2)$
          feedback: Try Again!
        ans3:
          value: $X \sim N(2,1)$
          feedback: Try Again!
        ans4:
          value: $X \sim N(9,1)$
          feedback: Try Again!
        ans5:
          value: $X \sim N(0,1)$
          feedback: Try Again!
        ans6:
          value: $X \sim \operatorname{Exp}(2)$
          feedback: Try Again!
        ans7:
          value: $X \sim \operatorname{Exp}(9)$
          feedback: Try Again!
      sample_size: 18
      confidence_level: 98%
---
# {{ params.vars.title }}
Richard’s Furniture Company delivers furniture from {{ params.start_time }} A.M. to {{ params.end_time }} P.M. continuously and uniformly. We are interested in how long (in hours) past the {{ params.start_time }} A.M. start time that individuals wait for their delivery.

## Distribution

What distribution does $X$ follow?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}
- {{ params.part1.ans7.value }}

## Wait Time

What is the average wait time for a delivery?

### Answer Section

Please enter answer rounded to two decimal places.

## Part 3

Suppose that it is now past noon on a delivery day. The probability that a person must wait at least one and a half more hours is:

### Answer Section

Please enter answer rounded to two decimal places.

## Part 4

Richard's Furniture Company wants to estimate the mean wait time for delivery. They want to be {{ params.confidence_level }} confident their estimate is within 0.5 hours. What is the minimum number of samples they need to achieve this level of confidence?

### Answer Section

Please enter an integer value.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)