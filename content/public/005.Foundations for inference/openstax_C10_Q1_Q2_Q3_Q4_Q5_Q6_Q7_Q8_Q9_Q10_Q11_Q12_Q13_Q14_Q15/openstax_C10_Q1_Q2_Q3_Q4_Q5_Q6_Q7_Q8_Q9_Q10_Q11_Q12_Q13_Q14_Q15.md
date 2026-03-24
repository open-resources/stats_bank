---
title: Hypothesis Testing Choices
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 10
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.15
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
    none-of-the-above: incorrect
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
    none-of-the-above: incorrect
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
    none-of-the-above: incorrect
myst:
  substitutions:
    params:
      vars:
        title: Hypothesis Testing Choices
      scenario1: In a random sample of 100 forests in the United States, 56 were coniferous
        or contained conifers. In a random sample of 80 forests in Mexico, 40 were
        coniferous or contained conifers. Is the proportion of conifers in the United
        States statistically more than the proportion of conifers in Mexico?
      part1:
        ans1:
          value: two means, known variances
          feedback: Try Again!
        ans2:
          value: two means, unknown variances
          feedback: Try Again!
        ans3:
          value: single mean
          feedback: Try Again!
        ans4:
          value: two proportions
          feedback: Good Job!
        ans5:
          value: single proportion
          feedback: Try Again!
        ans6:
          value: matched or paired samples
          feedback: Try Again!
      scenario2: A new laundry detergent is tested on consumers. Of interest is the
        proportion of consumers who prefer the new brand over the leading competitor.
        A study is done to test this.
      part2:
        ans1:
          value: two means, known variances
          feedback: Try Again!
        ans2:
          value: two means, unknown variances
          feedback: Try Again!
        ans3:
          value: single mean
          feedback: Try Again!
        ans4:
          value: two proportions
          feedback: Good Job!
        ans5:
          value: single proportion
          feedback: Try Again!
        ans6:
          value: matched or paired samples
          feedback: Try Again!
      scenario3: It is believed that 70% of men pass their drivers test in the first
        attempt, while 65% of women pass the test in the first attempt. Of interest
        is whether the proportions are in fact equal.
      part3:
        ans1:
          value: two means, known variances
          feedback: Try Again!
        ans2:
          value: two means, unknown variances
          feedback: Try Again!
        ans3:
          value: single mean
          feedback: Try Again!
        ans4:
          value: two proportions
          feedback: Good Job!
        ans5:
          value: single proportion
          feedback: Try Again!
        ans6:
          value: matched or paired samples
          feedback: Try Again!
---
# {{ params.vars.title }}
For each of the following scenarios, identify which type of hypothesis test would be most appropriate to use.

## Part 1

{{ params.scenario1 }}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Part 2

{{ params.scenario2 }}

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}
- {{ params.part2.ans5.value }}

## Part 3

{{ params.scenario3 }}

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}
- {{ params.part3.ans5.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)