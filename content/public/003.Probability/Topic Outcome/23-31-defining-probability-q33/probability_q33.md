---
title: Four games, one winner
topic: Probability
author: Sophie Varabioff
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.1
- 3.1.1.11
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
- SV
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
    params_vars_title: Four games, one winner
    params_description1: If the proportion of heads is larger than 0.3, you win $1.
    params_description2: If the proportion of heads is larger than 0.8, you win $1.
    params_planswer1: 10 tosses. Fewer tosses mean more variability in the sample
      fraction of heads, meaning there's a better chance of getting at least 0.3 heads.
    params_planswer2: 100 tosses. More flips means the observed proportion of heads
      would often be closer to the average, 0.50, and therefore also above 0.8.
    params_num1: 10
    params_num2: 100
    params_num3: 1
    params_part1_num1: 0.3
    params_part1_ans1_value: '10'
    params_part1_ans1_feedback: You got it!
    params_part1_ans2_value: '100'
    params_part1_ans2_feedback: Not quite!
    params_part2_num1: 0.8
    params_part2_ans1_value: '10'
    params_part2_ans1_feedback: Not quite!
    params_part2_ans2_value: '100'
    params_part2_ans2_feedback: You got it!
    params_part3_num1: 0.3
    params_part3_num2: 0.7
    params_part3_ans1_value: '10'
    params_part3_ans1_feedback: Not quite!
    params_part3_ans2_value: '100'
    params_part3_ans2_feedback: You got it!
    params_part4_num1: 0.2
    params_part4_ans1_value: '10'
    params_part4_ans1_feedback: You got it!
    params_part4_ans2_value: '100'
    params_part4_ans2_feedback: Not quite!
---
# {{ params_vars_title }}
Below are four versions of the same game. Your archnemesis gets to pick the version of the game, and then you get to choose how many times to flip a coin: ${{ params_num1 }}$ times or ${{ params_num2 }}$ times. Identify how many coin flips you should choose for each version of the game. It costs ${{ params_num3 }} to play each game.

## Part 1

{{ params_description1 }}

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

{{ params_planswer1 }}

## Part 2

{{ params_description2 }}

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

{{ params_planswer2 }}

## Part 3

If the proportion of heads is between ${{ params_part3_num1 }}$ and ${{ params_part3_num2 }}$, you win ${{ params_num3 }}.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

### pl-answer-panel

${{ params_num2 }}$ tosses. With more flips, the observed proportion of heads would often be closer to the average, 0.50.

## Part 4

If the proportion of heads is smaller than ${{ params_part4_num1 }}$, you win ${{ params_num3 }}.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

### pl-answer-panel

${{ params_num1 }}$ tosses. Fewer flips would increase variability in the fraction of tosses that are heads.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)