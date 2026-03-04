---
title: Tax Returns
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 7.1
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
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 2
    blank: true
part2:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N,B,E,Unif,Geom,Poisson,Chi2,t,F
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Tax Returns
      mean: 11.31
      stdev: 2.56
      sample_size: 48
      confidence_level: 90
      part1:
        statement1:
          value: $X$
          matches: The length of time for an individual to complete IRS form 1040,
            in hours.
        statement2:
          value: $\bar{X}$
          matches: The mean length of time for a sample of 48 taxpayers to complete
            IRS form 1040, in hours.
        option1:
          value: The mean length of time for a sample of 47 taxpayers to complete
            IRS form 1040, in hours.
        option2:
          value: The mean length of time for all taxpayers to complete IRS form 1040,
            in hours.
        option3:
          value: The length of time for a sample of 48 taxpayers to complete IRS form
            1040, in hours.
        option4:
          value: The length of time for an individual to complete IRS form 1040, in
            minutes.
        option5:
          value: The mean length of time for a sample of 48 taxpayers to complete
            IRS form 1040, in minutes.
        option6:
          value: The mean length of time for a sample of 47 taxpayers to complete
            IRS form 1040, in minutes.
      direction: more
      value: 16.43
      part3:
        ans1:
          value: Yes, I would be surprised because the p-value is less than 0.05.
          feedback: Correct! It would be surprising to get a sample mean that far
            from the population mean.
        ans2:
          value: No, I would not be surprised because the p-value is greater than
            0.05.
          feedback: Incorrect. It would be surprising to get a sample mean that far
            from the population mean.
        ans3:
          value: Yes, I would be surprised because the p-value is greater than 0.05.
          feedback: This is incorrect. If the p-value is greater than 0.05, we would
            fail to reject the null hypothesis and conclude that it would not be surprising
            to get a sample mean that far from the population mean.
        ans4:
          value: No, I would not be surprised because the p-value is less than 0.05.
          feedback: This is incorrect. If the p-value is less than 0.05, we would
            reject the null hypothesis and conclude that it would be surprising to
            get a sample mean that far from the population mean.
      part4:
        ans1:
          value: Yes, I would be surprised because the probability is less than 0.05.
          feedback: Correct! It would be surprising to get an individual value that
            far from the population mean.
        ans2:
          value: No, I would not be surprised because the probability is greater than
            0.05.
          feedback: Incorrect. It would be surprising to get an individual value that
            far from the population mean.
        ans3:
          value: Yes, I would be surprised because the probability is greater than
            0.05.
          feedback: This is incorrect. If the probability is greater than 0.05, we
            would fail to reject the null hypothesis and conclude that it would not
            be surprising to get an individual value that far from the population
            mean.
        ans4:
          value: No, I would not be surprised because the probability is less than
            0.05.
          feedback: This is incorrect. If the probability is less than 0.05, we would
            reject the null hypothesis and conclude that it would be surprising to
            get an individual value that far from the population mean.
---
# {{ params.vars.title }}
According to the Internal Revenue Service, the average length of time for an individual to complete (keep records for, learn, prepare, copy, assemble, and send) IRS Form 1040 (Individual income tax return) is {{ params.mean }} hours (without any attached schedules). The distribution is unknown. Let us assume that the standard deviation is {{ params.stdev }} hours. Suppose we randomly sample {{ params.sample_size }} taxpayers.

## Part 1

Define the variables $X$ and $\bar{X}$.

### Answer Section

## Part 2

Define the distribution of $\bar{X}$ symbolically. Your answer must be expressed in terms of ratios rather than decimals (e.g. $1/2$, not $0.5$).

### Answer Section

## Part 3

Would you be surprised if the {{ params.sample_size }} taxpayers finished their Form 1040s in an average of {{ params.direction }} than {{ params.value }} hours? Explain why or why not in complete sentences.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Would you be surprised if one taxpayer finished their Form 1040 in {{ params.direction }} than {{ params.value }} hours? In a complete sentence, explain why.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)