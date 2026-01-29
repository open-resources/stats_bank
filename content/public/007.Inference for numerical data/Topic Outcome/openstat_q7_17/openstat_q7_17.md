---
title: Paired or not? Part I
topic: Inference for numerical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.6
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
- AB
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
myst:
  substitutions:
    params:
      vars:
        title: Paired or not? Part I
      selected_scenario_part1: Evaluate sleep quality improvements by comparing scores
        before and after using a new type of mattress for the same subjects.
      part1:
        ans1:
          value: Paired.
          feedback: Correct!
        ans2:
          value: Not paired.
          feedback: Incorrect!
      selected_scenario_part2: Compare pre-test (beginning of semester) and post-test
        (end of semester) scores of students.
      part2:
        ans1:
          value: Paired.
          feedback: Correct!
        ans2:
          value: Not paired.
          feedback: Incorrect!
      selected_scenario_part3: Evaluate the improvement in programming skills by comparing
        test scores before and after a coding bootcamp.
      part3:
        ans1:
          value: Paired.
          feedback: Correct!
        ans2:
          value: Not paired.
          feedback: Incorrect!
      selected_scenario_part4: Assess gender-related salary gap by comparing salaries
        of randomly sampled men and women.
      part4:
        ans1:
          value: Paired.
          feedback: Incorrect!
        ans2:
          value: Not paired.
          feedback: Correct!
---
# {{ params.vars.title }}
In each of the following scenarios, determine if the data are paired.

## Part 1

{{ params.selected_scenario_part1 }}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

{{ params.selected_scenario_part2 }}

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

{{ params.selected_scenario_part3 }}

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

{{ params.selected_scenario_part4 }}

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)