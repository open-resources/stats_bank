---
title: Coin flips
topic: Probability
author: Sophie Varabioff
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.9
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
  type: number-input
  pl-customizations:
    label: $p = $
    weight: 1
    digits: 3
    comparison: sigfig
part2:
  type: number-input
  pl-customizations:
    label: $p = $
    weight: 1
    digits: 3
    comparison: sigfig
part3:
  type: number-input
  pl-customizations:
    label: $p = $
    weight: 1
    digits: 3
    comparison: sigfig
myst:
  substitutions:
    params_vars_title: Coin flips
    params_num1: 8
---
# {{ params_vars_title }}
If you flip a fair coin ${{ params_num1 }}$ times, what is the probability of

## Part 1

getting all tails? Please enter a numeric value between 0 and 1, keeping three significant figures (e.g. 0.00931).

### pl-answer-panel

$0.5^{ {{params_num1}} } \approx {{ correct_answers.part1_ans}} $

## Part 2

getting all heads? Please enter a numeric value between 0 and 1, keeping three significant figures (e.g. 0.00931).

### pl-answer-panel

$0.5^{ {{params_num1}} } \approx {{ correct_answers.part2_ans}} $

## Part 3

getting at least one tails? Please enter a numeric value between 0 and 1, keeping three significant figures (e.g. 0.00931).

### pl-answer-panel

P (at least one tails) $= 1 -$ P(no tails) $= 1 - (0.5^{ {{params_num1}} }) \approx 1 - {{ correct_answers.part2_ans}} \approx {{ correct_answers.part3_ans}} $

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)