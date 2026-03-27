---
title: 2 and 4 Year College Enrollments
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
    label: $\text{test statistic}  = $
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
        title: 2 and 4 Year College Enrollments
      sample_size: 34
      two_year_mean: 4,317
      two_year_sd: 5,221
      four_year_mean: 4,538
      four_year_sd: 8,278
      part1:
        ans1:
          value: two means, unknown variances
          feedback: Good job! Even though we know the sample standard deviations,
            we don't know the population variances or if they are equal
        ans2:
          value: two means, known variances
          feedback: Try again! We do not know the variances
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
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the mean enrollments
            of the two-year colleges and the four-year colleges.
          feedback: Good job!
        ans2:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the population
            mean enrollments of the two-year colleges and the four-year colleges.
          feedback: Try again!
        ans3:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the variance of
            enrollments of two-year colleges and the four-year colleges.
          feedback: Try again!
        ans4:
          value: $\bar{X}_1 - \bar{X}_2$ is the difference between the standard deviation
            of enrollments of two-year colleges and the four-year colleges.
          feedback: Try again!
      part4:
        ans1:
          value: Student's t-distribution
          feedback: Good job!
        ans2:
          value: Normal distribution
          feedback: Try again!
        ans3:
          value: Chi-square distribution
          feedback: Try again!
        ans4:
          value: F-distribution
          feedback: Try again!
      alpha: 0.01
      part7:
        ans1:
          value: Reject the null hypothesis because the p-value is less than alpha
          feedback: Try again!
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than alpha
          feedback: Good Job
        ans3:
          value: Reject the null hypothesis because the p-value is greater than alpha
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            alpha
          feedback: Try again
---
# {{ params.vars.title }}
A student at a four-year college claims that mean enrollment at four–year colleges is higher than at two–year colleges in the United States. Two surveys are conducted. Of the {{ params.sample_size }} two–year colleges surveyed, the mean enrollment was {{ params.two_year_mean }} with a standard deviation of {{ params.two_year_sd }}. Of the 35 four-year colleges surveyed, the mean enrollment was {{ params.four_year_mean }} with a standard deviation of {{ params.four_year_sd }}.

For the following questions, let $\mu_1$ be the mean enrollment at two-year colleges and $\mu_2$ be the mean enrollment at four-year colleges.

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

What would your conclusion be at a $\alpha={{ params.alpha }}$ be?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)