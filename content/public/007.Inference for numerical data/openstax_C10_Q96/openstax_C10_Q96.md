---
title: Sedan Mileage
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 10
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.12
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{test statistic} = $
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $p = $
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Sedan Mileage
      n1: 40
      xbar1: 30
      sx1: 2
      sigma1: 4
      n2: 17
      xbar2: 36
      sx2: 12
      sigma2: 6
      part1:
        ans1:
          value: two means, unknown variances
          feedback: Try again! We are given the population standard deviations
        ans2:
          value: two means, known variances
          feedback: Good job! We know the population standard deviations
        ans3:
          value: single mean
          feedback: Try again! We have more than one sample present
        ans4:
          value: two proportions
          feedback: Try again! There are no proportions in this scenario
        ans5:
          value: single proportion
          feedback: Try again! There are no proportions in this scenario
        ans6:
          value: matched or paired samples
          feedback: Try again!
      part2:
        ans1:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \lt \mu_2$'
          feedback: Good job!
        ans2:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \le \mu_2$'
          feedback: Try again!
        ans3:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \gt \mu_2$'
          feedback: Try again!
        ans4:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \ge \mu_2$'
          feedback: Try again!
        ans5:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \ne \mu_2$'
          feedback: Try again!
        ans6:
          value: '$H_0: \mu_1 \ne \mu_2$ and $H_A: \mu_1 = \mu_2$'
          feedback: Try again!
      part3:
        ans1:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the mean miles
            per gallon of non-hybrid sedans and hybrid sedans.
          feedback: Good job!
        ans2:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the population
            mean miles per gallon of non-hybrid sedans and hybrid sedans.
          feedback: Try again!
        ans3:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the variance of
            miles per gallon of non-hybrid sedans and hybrid sedans.
          feedback: Try again!
        ans4:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the mean miles
            per gallon of hybrid sedans and non-hybrid sedans.
          feedback: Try again! This is close, but has a subtle error.
      part4:
        ans1:
          value: Normal distribution
          feedback: Good job!
        ans2:
          value: Student's t-distribution
          feedback: Try again!
        ans3:
          value: Chi-square distribution
          feedback: Try again!
        ans4:
          value: F-distribution
          feedback: Try again!
      alpha: 0.05
      part7:
        ans1:
          value: Reject the null hypothesis because the p-value is less than 0.05
          feedback: Good Job
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than 0.05
          feedback: Try again!
        ans3:
          value: Reject the null hypothesis because the p-value is greater than 0.05
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            0.05
          feedback: Try again
---
# {{ params.vars.title }}
Some manufacturers claim that non-hybrid sedan cars have a lower mean miles-per-gallon (mpg) than hybrid ones. Suppose that consumers test {{ params.n2 }} hybrid sedans and get a mean of {{ params.xbar2 }} mpg with a standard deviation of {{ params.sx1 }} mpg.
{{ params.n1 }} non-hybrid sedans get a mean of {{ params.xbar1 }} mpg with a standard deviation of {{ params.sx2 }} mpg.
Suppose that the population standard deviations are known to be {{ params.sigma2 }} and {{ params.sigma1 }}, respectively.

Conduct a hypothesis test to evaluate the manufacturers claim.

For the following questions, let $\mu_1$ be the mean mileage for non-hybrid sedans and $\mu_2$ be the mean mileage for hybrid sedans.

## Part 1

Identify the correct hypothesis test to perform.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Part 2

Identify the null and alternative hypotheses.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}
- {{ params.part2.ans5.value }}
- {{ params.part2.ans6.value }}

## Part 3

What does the random variable $\bar{X}\_1 - \bar{X}\_2$ represent?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Identify the distribution to use for the test.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

What is the test statistic? Please provide at least 4 decimal places of precision.

### Answer Section

Please enter a number.

## Part 6

Calculate the p-value for this test statistic. Please provide at least 4 decimal places of precision.

### Answer Section

Please enter a number.

## Part 7

What would your conclusion be at a signifiance level of $\alpha={{ params.alpha }}$ be?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)