---
title: Bus wait time
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 7.3
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
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: ${{ params.percentile }} \text{ Percentile} = $
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
myst:
  substitutions:
    params:
      vars:
        title: Bus wait time
      min_time: 5
      length: 108
      max_time: 113
      sample_size: 81
      percentile: 99
      random_value: 25
      part2:
        ans1:
          value: 'Yes'
          feedback: You got it! The probability of observing a sample average less
            than 25 minutes is 0.000
        ans2:
          value: 'No'
          feedback: Try Again! Consider what the Z-score and p-value tell us about
            how likely it is to observe a sample average less than 25 minutes.
        ans3:
          value: Not enough information
          feedback: Try Again!
---
# {{ params.vars.title }}
The time to wait for a particular rural bus is distributed uniformly from {{ params.min_time }} to {{ params.max_time }} minutes. {{ params.sample_size }} are randomly sampled to learn how long they waited.

## Percentiles

The {{ params.percentile }} percentile sample average wait time (in minutes) for a sample of {{ params.sample_size }} riders is

### Answer Section

Please enter a number accurate to two decimal places.

## Average Wait Time

Would you be surprised, based upon numerical calculations, if the sample average wait time (in minutes) for {{ params.sample_size }} riders was less than {{ params.random_value }} minutes?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)