---
title: Hearts win
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.4
- 3.1.1.14
- 3.1.1.15
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
    label: $\mu= $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\sigma= $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\mu= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\sigma= $
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Hearts win
    params_part3_num1: 3
    params_part4_num1: 3
    params_part5_num1: 3
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Incorrect! The expected net profit is negative, so
      on average you expect to lose money.
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Correct! The expected net profit is negative, so on
      average you expect to lose money.
    params_description_num1: 4
    params_description_num2: 4
    params_description_num3: 45
    params_description_num4: 4
    params_description_num5: 23
---
# {{ params_vars_title }}
<div class="mathjax_ignore">
In a new card game, you start with a well-shuffled full deck and draw {{ params_description_num1 }} cards without replacement. If you draw {{ params_description_num2 }} hearts, you win ${{ params_description_num3 }}. If you draw {{ params_description_num4 }} black cards, you win ${{ params_description_num5 }}. For any other draws, you win nothing.
</div>

## Part 1

Create a probability model for the amount you win at this game, and find the expected winnings.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

E(X) = {{ correct_answers.part1_ans }}

## Part 2

Also compute the standard deviation of this distribution.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

SD(X) = {{ correct_answers.part2_ans }}

## Part 3

If the game costs ${{ params_part3_num1 }} to play, what would be the expected value of the net profit (or loss)?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

E(X) = {{ correct_answers.part3_ans }}

## Part 4

If the game costs ${{ params_part4_num1 }} to play, what would be the standard deviation of the net profit (or loss)? (hint: profit = winnings - cost)

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

SD(X) = {{ correct_answers.part4_ans }}

## Part 5

If the game costs ${{ params_part5_num1 }} to play, should you play this game?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)