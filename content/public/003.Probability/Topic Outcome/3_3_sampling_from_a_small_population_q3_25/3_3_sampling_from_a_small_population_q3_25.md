---
title: Chips in a bag
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
    digits: 3
    weight: 1
    allow-blank: true
    label: $P= $
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Chips in a bag
    params_description_num1: 9
    params_description_num2: 6
    params_description_num3: 1
    params_description_n1: 15
    params_description_n: 16
    params_description_blue1: 5
    params_part4_ans1_value: 'Yes'
    params_part4_ans1_feedback: Incorrect. Removing one chip meaningfully changes
      the probability of what might be drawn next.
    params_part4_ans2_value: 'No'
    params_part4_ans2_feedback: Correct!
---
# {{ params_vars_title }}
Imagine you have a bag containing ${{ params_description_num1 }}$ red, ${{ params_description_num2 }}$ blue, and ${{ params_description_num3 }}$ orange chips.

## Part 1

Suppose you draw a chip and it is blue. If drawing without replacement, what is the probability the next is also blue?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

${{ params_description_blue1 }} / {{ params_description_n1 }} \approx {{ correct_answers.part1_ans }}$

## Part 2

Suppose you draw a chip and it is orange, and then you draw a second chip without replacement. What is the probability this second chip is blue?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

${{ params_description_num2 }} / {{ params_description_n1 }} \approx {{ correct_answers.part2_ans }}$

## Part 3

If drawing without replacement, what is the probability of drawing two blue chips in a row?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\frac{{{ params_description_num2 }}}{{{ params_description_n }}} \times \frac{{{ params_description_blue1 }}}{{{ params_description_n1 }}} \approx {{ correct_answers.part3_ans }}$

## Part 4

When drawing without replacement, are the draws independent? Explain.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)