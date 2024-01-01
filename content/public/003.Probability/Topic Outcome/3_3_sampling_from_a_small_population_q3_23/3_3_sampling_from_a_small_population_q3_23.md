---
title: Marbles in an urn
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.2
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
    allow-blank: true
    label: $P= $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $P= $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $P= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $P= $
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Marbles in an urn
    params_description_num1: 6
    params_description_num2: 5
    params_description_num3: 4
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Correct!
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Incorrect. The population that is being sampled from
      is identical in each draw.
---
# {{ params_vars_title }}
Imagine you have an urn containing ${{ params_description_num1 }}$ red, ${{ params_description_num2 }}$ blue, and ${{ params_description_num3 }}$ orange marbles in it.

## Part 1

What is the probability that the first marble you draw is blue?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part1_ans }}

## Part 2

Suppose you drew a blue marble in the first draw. If drawing with replacement, what is the probability of drawing a blue marble in the second draw?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part2_ans }}

## Part 3

Suppose you instead drew an orange marble in the first draw. If drawing with replacement, what is the probability of drawing a blue marble in the second draw?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

{{ correct_answers.part3_ans }}

## Part 4

If drawing with replacement, what is the probability of drawing two blue marbles in a row?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

${{ correct_answers.part3_ans }}\times{{ correct_answers.part3_ans }}={{ correct_answers.part4_ans }}$

## Part 5

When drawing with replacement, are the draws independent?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)