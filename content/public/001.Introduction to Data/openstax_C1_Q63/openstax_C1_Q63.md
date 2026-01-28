---
title: San Jose Park Use
topic: Introduction to Data
author: Gavin Kendal-Freedman
source: 1.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 1.1.1.0
difficulty:
- easy
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
myst:
  substitutions:
    params:
      vars:
        title: San Jose Park Use
        every: 7
      part1:
        measurement: Number of times per week
        ans1:
          value: qualitative
          feedback: Try again please!
        ans2:
          value: quantitative discrete
          feedback: Great! You got it.
        ans3:
          value: quantitative continuous
          feedback: Not quite, it is quantitative, but the a count of something is
            not a continuous measurement. Try again!
---
# {{ params.vars.title }}
A study was done to determine the occupation, age, number of times per week, and the duration (amount of time) of resident use of a local park in San Jose. The first house in the neighborhood around the park was selected randomly and then every {{ params.vars.every }}$^{th}$ house in the neighborhood around the park was interviewed.

## Part 1

"{{ params.part1.measurement }}" is what type of data?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)