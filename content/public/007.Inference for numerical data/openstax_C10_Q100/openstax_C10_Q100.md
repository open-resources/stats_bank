---
title: Physical Science Degrees
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
        title: Physical Science Degrees
      white_degrees: 4885
      white_physical: 563
      black_degrees: 392
      black_physical: 38
      part1:
        ans1:
          value: two means, unknown variances
          feedback: Try again! This is not a test for means
        ans2:
          value: two means, known variances
          feedback: Try again! This is not a test for means
        ans3:
          value: single mean
          feedback: Try again! We have more than one sample present
        ans4:
          value: two proportions
          feedback: Good job! We are testing 2 proportions
        ans5:
          value: single proportion
          feedback: Try again! There are more than one proportion being tested
        ans6:
          value: matched or paired samples
          feedback: Try again!
      part2:
        ans1:
          value: '$H_0: P_W = P_B$ and $H_A: P_W \ne P_B$'
          feedback: Good job!
        ans2:
          value: '$H_0: P_W \ne P_B$ and $H_A: P_W = P_B$'
          feedback: Try again!
        ans3:
          value: '$H_0: P_W = P_B$ and $H_A: P_W \le P_B$'
          feedback: Try again!
        ans4:
          value: '$H_0: P_W = P_B$ and $H_A: P_W \gt P_B$'
          feedback: Try again!
        ans5:
          value: '$H_0: P_W = P_B$ and $H_A: P_W \ge P_B$'
          feedback: Try again!
        ans6:
          value: '$H_0: P_W = P_B$ and $H_A: P_W \lt P_B$'
          feedback: Try again!
      part3:
        ans1:
          value: The random variable is the difference in the proportions of White
            and Black people with conferred degrees in a given year, aged 21 to 24.
          feedback: Good job!
        ans2:
          value: The random variable is the difference in the proportions of White
            and Black people with conferred degrees in a given year.
          feedback: Try again!
        ans3:
          value: The random variable is the difference in the number of White and
            Black people with conferred degrees in a given year, aged 21 to 24.
          feedback: Try again!
        ans4:
          value: The random variable is the difference in the number of White and
            Black people with conferred degrees in a given year.
          feedback: Try again!
      part4:
        ans1:
          value: Normal for two proportions
          feedback: Good job!
        ans2:
          value: Normal for two means
          feedback: Try again!
        ans3:
          value: Student's t-distribution
          feedback: Try again!
        ans4:
          value: Chi-square distribution
          feedback: Try again!
        ans5:
          value: F-distribution
          feedback: Try again!
      alpha: 0.1
      part7:
        ans1:
          value: Reject the null hypothesis because the p-value is less than 0.1
          feedback: Try again!
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than 0.1
          feedback: Good Job
        ans3:
          value: Reject the null hypothesis because the p-value is greater than 0.1
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            0.1
          feedback: Try again
---
# {{ params.vars.title }}
We are interested in whether the proportions of conferred physical science degrees for people aged 21 to 24 are the same for White and Black people in the United States. The number of conferred degrees for White people in a given year is {{ params.white_degrees }}. {{ params.white_physical }} were aged 21 to 24. The estimate for Black people is {{ params.black_degrees }}. {{ params.black_physical }} were aged 21 to 24. We will let people with conferred physical science degrees be our population.

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

What does the random variable represent?

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