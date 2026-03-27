---
title: Babies on Airplanes
topic: Inference for categorical data
author: Gavin Kendal-Freedman
source: 11
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.11
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
    order: fixed
part2:
  type: integer-input
  pl-customizations:
    weight: 1
    allow-blank: false
    label: $df = $
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: number-input
  pl-customizations:
    weight: 1
    comparison: decdig
    digits: 2
part5:
  type: number-input
  pl-customizations:
    weight: 1
    comparison: decdig
    digits: 4
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Babies on Airplanes
      expected_mean: 7
      sample_mean: 7.4
      sample_size: 22
      expected_variance: 15
      sample_std_dev: 4.9
      part1:
        ans1:
          value: A chi-squared test of a single variance
          feedback: Good Job!
        ans2:
          value: A chi-squared goodness of fit test
          feedback: Try again!
        ans3:
          value: A chi-squared test of independence
          feedback: Try again!
        ans4:
          value: A chi-squared test of homogeneity
          feedback: Try again!
      part3:
        ans1:
          value: '$H_0: \sigma = 3.9$, $H_A: \sigma > 3.9$'
          feedback: Good Job!
        ans2:
          value: '$H_0: \sigma = 3.9$, $H_A: \sigma < 3.9$'
          feedback: Try again.
        ans3:
          value: '$H_0: \sigma = 3.9$, $H_A: \sigma \neq 3.9$'
          feedback: Try again.
        ans4:
          value: '$H_0: \sigma^2 = 3.9$, $H_A: \sigma^2 > 3.9$'
          feedback: Try again.
        ans5:
          value: '$H_0: \sigma^2 = 3.9$, $H_A: \sigma^2 < 3.9$'
          feedback: Try again.
        ans6:
          value: '$H_0: \sigma^2 = 3.9$, $H_A: \sigma^2 \neq 3.9$'
          feedback: Try again.
        ans7:
          value: '$H_0: \sigma = 15$, $H_A: \sigma > 15$'
          feedback: Try again.
        ans8:
          value: '$H_0: \sigma = 15$, $H_A: \sigma < 15$'
          feedback: Try again.
        ans9:
          value: '$H_0: \sigma = 15$, $H_A: \sigma \neq 15$'
          feedback: Try again.
      significance_level: 1%
      part6:
        ans1:
          value: Reject the null hypothesis because the p-value is less than the significance
            level
          feedback: Try again.
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than the significance level
          feedback: Good Job!
        ans3:
          value: Reject the null hypothesis because the p-value is greater than the
            significance level
          feedback: Try again.
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            the significance level
          feedback: Try again.
---
# {{ params.vars.title }}
Airline companies are interested in the consistency of the number of babies on each flight, so that they have adequate safety equipment. They are also interested in the variation of the number of babies. Suppose that an airline executive believes the average number of babies on flights is {{ params.expected_mean }} with a variance of {{ params.expected_variance }} at most. The airline conducts a survey. The results of the {{ params.sample_size }} flights surveyed give a sample average of {{ params.sample_mean }} with a sample standard deviation of {{ params.sample_std_dev }}. Conduct a hypothesis test of the airline executive’s belief.

## Part 1

What type of chi-squared test would be most appropriate to use?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Identify the $df$.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

State the null and alternative hypotheses for this test.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}
- {{ params.part3.ans5.value }}
- {{ params.part3.ans6.value }}
- {{ params.part3.ans7.value }}
- {{ params.part3.ans8.value }}
- {{ params.part3.ans9.value }}

## Part 4

State the $\chi^2$ test statistic.

### Answer Section

Please enter a number to at least two decimal places of precision.

## Part 5

Find the p-value for this test statistic.

### Answer Section

Please enter a number to at least four decimal places of precision.

## Part 6

At a significance level of {{ params.significance_level }}, would you reject or fail to reject the null hypothesis? Why?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)