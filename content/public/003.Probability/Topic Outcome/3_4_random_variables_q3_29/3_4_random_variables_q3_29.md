---
title: College smokers
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.12
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
- CY
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $E= $
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: College smokers
    params_part1_num1: 109
    params_part2_start_hour: 9
    params_part2_before_start_hour: 8
    params_part2_waiting_students: 28
    params_part2_ans1_value: 'No'
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: 'Yes'
    params_part2_ans2_feedback: Incorrect. These students are not a random sample
      from the university's student population.
    params_description_perc_smokers: 17
---
# {{ params_vars_title }}
At a university, ${{ params.description.perc_smokers }}$% of students smoke.

## Part 1

Calculate the expected number of smokers in a random sample of ${{ params_part1_num1 }}$ students from this university.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part1_ans }}

## Part 2

The university gym opens at {{ params.part2.start_hour }} am on Saturday mornings. One Saturday morning at {{ params.part2.before_start_hour }}:55 am there are ${{ params.part2.waiting_students }}$ students outside the gym waiting for it to open. Should you use the same approach from part (a) to calculate the expected number of smokers among these ${{ params.part2.waiting_students }}$ students?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

No, these ${{ params.part2.waiting_students }}$ students are not a random sample from the university's student population. For example, it might be argued that the proportion of smokers among students who go to the gym at ${{ params.part2.start_hour }}$ am on a Saturday morning would be lower than the proportion of smokers in the university as a whole.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)