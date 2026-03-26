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
      scenario1: The league mean batting average is 0.280 with a known standard deviation
        of 0.06. The Rattlers and the Vikings belong to the league. The mean batting
        average for a sample of eight Rattlers is 0.210, and the mean batting average
        for a sample of eight Vikings is 0.260. There are 24 players on the Rattlers
        and 19 players on the Vikings. Are the batting averages of the Rattlers and
        Vikings statistically different?
      part1:
        ans1:
          value: two means, known variances
          feedback: Good Job!
        ans2:
          value: two means, unknown variances
          feedback: Try Again!
        ans3:
          value: single mean
          feedback: Try Again!
        ans4:
          value: two proportions
          feedback: Try Again!
        ans5:
          value: single proportion
          feedback: Try Again!
        ans6:
          value: matched or paired samples
          feedback: Try Again!
      scenario2: It is believed that the average grade on an English essay in a particular
        school system for women is higher than for men. A random sample of 31 women
        had a mean score of 82 with a standard deviation of three, and a random sample
        of 25 men had a mean score of 76 with a standard deviation of four.
      part2:
        ans1:
          value: two means, known variances
          feedback: Try Again!
        ans2:
          value: two means, unknown variances
          feedback: Good Job!
        ans3:
          value: single mean
          feedback: Try Again!
        ans4:
          value: two proportions
          feedback: Try Again!
        ans5:
          value: single proportion
          feedback: Try Again!
        ans6:
          value: matched or paired samples
          feedback: Try Again!
      scenario3: A new laundry detergent is tested on consumers. Of interest is the
        proportion of consumers who prefer the new brand over the leading competitor.
        A study is done to test this.
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