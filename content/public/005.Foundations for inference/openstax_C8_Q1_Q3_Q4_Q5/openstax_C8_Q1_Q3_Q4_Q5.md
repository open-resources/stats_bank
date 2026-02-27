---
title: Weight of Elephants
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: original
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
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $\bar{x} = $
part2:
  type: integer-input
  pl-customizations:
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
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 4
    allow-blank: false
    allow-fractions: false
    allow-partial-credit: true
    label: $CI_{ {{ params.confidence }}\% } = $
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{Margin of Error} = $
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Weight of Elephants
      x_bar: 234
      stdev_p: 15
      stdev_s: 8
      sample_size: 40
      other_sample_size: 541
      alpha: 0.05
      confidence: 95
      z_score: 1.959963984540054
      part7:
        ans1:
          value: As the sample size increases, there will be less variability in the
            mean, so the interval size decreases.
          feedback: Correct!
        ans2:
          value: As the sample size increases, there will be more variability in the
            mean, so the interval size increases.
          feedback: Try again please!
        ans3:
          value: As the sample size increases, there will be less variability in the
            mean, so the interval size increases.
          feedback: Try again please!
        ans4:
          value: As the sample size increases, there will be more variability in the
            mean, so the interval size decreases.
          feedback: Try again please!
---
# {{ params.vars.title }}
The standard deviation of the weights of elephants is known to be approximately {{ params.stdev_p }} pounds. We wish to construct a {{ params.confidence }}% confidence interval for the mean weight of newborn elephant calves. {{ params.sample_size }} newborn elephants are weighed. The sample mean is {{ params.x_bar }} pounds. The sample standard deviation is {{ params.stdev_s }} pounds.

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

Please define the distribution that should be used. (Ex. $exp(1)$, $N(0,1)$, $B(5, 0.5)$)

### Answer Section

## Part 5

What is the {{ params.confidence }}% confidence interval?

### Answer Section

## Part 6

What is the margin of error for the confidence interval with {{ params.confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

## Part 7

What will happen to the confidence interval obtained, if {{ params.other_sample_size }} newborn elephants are weighed instead of {{ params.sample_size }}? Why?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)