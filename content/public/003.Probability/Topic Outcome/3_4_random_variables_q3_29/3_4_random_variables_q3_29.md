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
    params:
      vars:
        title: College smokers
      part1:
        num1: 104
      part2:
        start_hour: 11
        before_start_hour: 10
        waiting_students: 27
        ans1:
          value: 'No'
          feedback: Correct!
        ans2:
          value: 'Yes'
          feedback: Incorrect. These students are not a random sample from the university's
            student population.
      description:
        perc_smokers: 17
---
# {{ params.vars.title }}
At a university, ${{ params.description.perc_smokers }}$% of students smoke.

## Part 1

Calculate the expected number of smokers in a random sample of ${{ params.part1.num1 }}$ students from this university.

### Answer Section

Please enter a numeric value in.

## Part 2

The university gym opens at {{ params.part2.start_hour }} am on Saturday mornings. One Saturday morning at {{ params.part2.before_start_hour }}:55 am there are ${{ params.part2.waiting_students }}$ students outside the gym waiting for it to open. Should you use the same approach from part (a) to calculate the expected number of smokers among these ${{ params.part2.waiting_students }}$ students?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)