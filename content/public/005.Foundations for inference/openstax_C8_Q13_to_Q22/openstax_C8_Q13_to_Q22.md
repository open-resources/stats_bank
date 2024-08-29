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
    params:
      vars:
        title: Weight of Heads of Lettuce
      x_bar: 1.8
      sigma: 0.18
      sample_stdev: 0.09
      sample_size: 22
      other_sample_size: 11.0
      alpha1: 0.1
      confidence1: 90
      z_score1: 1.645
      alpha2: 0.05
      confidence2: 95
      z_score2: 1.96
      part6_confidence: 90
      part6_z_score: 1.645
      part4:
        option1:
          value: The mean weight of a head of lettuce.
        option2:
          value: The mean weight of all heads of lettuce.
        statement1:
          value: $X$
          matches: The weight of a head of lettuce.
        statement2:
          value: $\bar{X}$
          matches: The mean weight of a sample of 22 heads of lettuce.
      part7:
        option1:
          value: $\text{CL} = 98\%$
        option2:
          value: $\text{CL} = 99\%$
        statement1:
          value: CI 1
          matches: $\text{CL} = 90\%$
        statement2:
          value: CI 2
          matches: $\text{CL} = 95\%$
      part8:
        ans1:
          value: The interval is larger because the level of confidence decreased.
            If the only change made in the analysis is a change in confidence level,
            then all we are doing is changing how much area is being calculated for
            the normal distribution. Therefore, a smaller confidence level results
            in larger areas and larger intervals.
          feedback: Please try again!
        ans2:
          value: The interval is smaller because the level of confidence increased.
            If the only change made in the analysis is a change in confidence level,
            then all we are doing is changing how much area is being calculated for
            the normal distribution. Therefore, a larger confidence level results
            in smaller areas and smaller intervals.
          feedback: Please try again!
        ans3:
          value: The interval is greater because the level of confidence increased.
            If the only change made in the analysis is a change in confidence level,
            then all we are doing is changing how much area is being calculated for
            the normal distribution. Therefore, a larger confidence level results
            in larger areas and larger intervals.
          feedback: Please try again!
        ans4:
          value: The interval is smaller because the level of confidence decreased.
            If the only change made in the analysis is a change in confidence level,
            then all we are doing is changing how much area is being calculated for
            the normal distribution. Therefore, a larger confidence level results
            in larger areas and larger intervals.
          feedback: Nice work!
      part9:
        option1:
          name: CL-Increase
          value: The confidence level would increase.
        option2:
          name: CL-Decrease
          value: The confidence level would decrease.
        option3:
          name: EBM-Increase
          value: The error bound would increase.
        option4:
          name: EBM-Decrease
          value: The error bound would decrease.
        option5:
          value: The sample size would increase.
        option6:
          value: The sample size would decrease.
        statement1:
          value: What would happen if 11.0 heads of lettuce were sampled instead of
            22, and the error bound remained the same?
          matches: CL-Decrease
        statement2:
          value: What would happen if 11.0 heads of lettuce were sampled instead of
            22, and the confidence level remained the same?
          matches: EBM-Increase
---
# {{ params.vars.title }}
A sample of {{ params.sample_size }} heads of lettuce was selected. Assume that the population distribution of head weight is normal. The weight of each head of lettuce was then recorded. The mean weight was {{ params.x_bar }} pounds with a standard deviation of {{ params.sample_stdev }} pounds. The population standard deviation is known to be {{ params.sigma }} pounds.

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

Match the random variables $X$ and $\bar{X}$ to the right definition

### Answer Section

## Part 5

Please define the distribution that should be used. (Ex. $exp(1)$, $N(0,1)$, $B(5, 0.5)$)

### Answer Section

## Part 6

What should the error bound be for the confidence interval with {{ params.part6_confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

## Part 7

Please match the following confidence intervals to their Confidence Level.

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

## Part 8

Please select the answer that identifies and explains the what the difference between a {{ params.confidence1 }}% confidence interval and a {{ params.confidence2 }}% confidence interval would be.

### Answer Section

- {{ params.part8.ans1.value }}
- {{ params.part8.ans2.value }}
- {{ params.part8.ans3.value }}
- {{ params.part8.ans4.value }}

## Part 9

Please match each of the scenarios to the correct outcome.

### Answer Section

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)