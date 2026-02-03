---
title: Personnel Management
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 8.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.9
- 5.1.1.18
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
    label: $\mu=$
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\sigma=$
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n=$
part4:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N,B,E,Unif,Geom,Poisson,Chi2,t,F
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part5:
  type: symbolic-input
  pl-customizations:
    label: $\bar{X}\sim$
    custom_functions: N,B,E,Unif,Geom,Poisson,Chi2,t,F
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $P({{ params.lower_bound }} < X < {{ params.upper_bound }})=$
part7:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $P({{ params.lower_bound }} < \bar{X} < {{ params.upper_bound }})=$
part8:
  type: multiple-choice
  pl-customizations:
    weight: 1
part9:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{Percentile}_{ {{ params.percentile }} }=$
myst:
  substitutions:
    params:
      vars:
        title: Personnel Management
      confidence_level: 95
      sample_size: 12
      mean: 4.7
      stdev: 1.3
      lower_bound: 4.38
      upper_bound: 5.03
      part8:
        ans1:
          value: The distributions are different accounts for the different probabilities.
          feedback: Good job!
        ans2:
          value: The two distributions are the same, so the probabilities should be
            the same.
          feedback: Try again please!
        ans3:
          value: The distributions have a different mean, but same standard deviation.
          feedback: Try again please!
        ans4:
          value: The distributions have different shapes.
          feedback: Try again please!
      percentile: 94.0
---
# {{ params.vars.title }}
Yoonie is a personnel manager in a large corporation. Each month she must review {{ params.sample_size }} of the employees. From past experience, she has found that the reviews take her approximately {{ params.mean }} hours each to do with a population standard deviation of {{ params.stdev }} hours.
Let $X$ be the random variable representing the time it takes her to complete one review. Assume $X$ is normally distributed.
Let $\bar{x}$ be the random variable representing the mean time to complete the {{ params.sample_size }} reviews. Assume that the {{ params.sample_size }} reviews represent a random set of reviews.

## Part 1

Identify $\mu$.

### Answer Section

Please enter a numeric value in.

## Part 2

Identify $\sigma$.

### Answer Section

Please enter a numeric value in.

## Part 3

Identify the sample size.

### Answer Section

Please enter a numeric value in.

## Part 4

Identify the distribution for $X$.

### Answer Section

## Part 5

Identify the distribution for $\bar{X}$.

### Answer Section

## Part 6

Find the probability that **one** review will take Yoonie from {{ params.lower_bound }} to {{ params.upper_bound }} hours.

### Answer Section

## Part 7

Find the probability that **mean** of a month's reviews will take Yoonie from {{ params.lower_bound }} to {{ params.upper_bound }} hours.

### Answer Section

Please enter a numeric value in.

## Part 8

What causes the probabilities in parts 6 and 7 to be different?

### Answer Section

- {{ params.part8.ans1.value }}
- {{ params.part8.ans2.value }}
- {{ params.part8.ans3.value }}
- {{ params.part8.ans4.value }}

## Part 9

Find the ${{ params.percentile }}$ percentile for the mean time to complete one month's reviews.

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)