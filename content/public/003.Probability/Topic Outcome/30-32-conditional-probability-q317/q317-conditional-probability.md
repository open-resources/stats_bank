---
title: Burger Preferences
topic: Probability
author: Sophie Varabioff
source: 3.17
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.2
- 3.1.1.4
- 3.1.1.5
- 3.1.1.10
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
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part5:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
myst:
  substitutions:
    params_vars_title: Burger Preferences
    params_num1: 8
    params_num2: 6
    params_num3: 14
    params_num4: 176
    params_num5: 181
    params_num6: 357
    params_num7: 6
    params_num8: 16
    params_num9: 22
    params_num10: 28
    params_num11: 28
    params_num12: 56
    params_num13: 4
    params_num14: 3
    params_num15: 7
    params_num16: 26
    params_num17: 20
    params_num18: 46
    params_num19: 16
    params_num20: 4
    params_num21: 20
    params_num22: 264
    params_num23: 258
    params_num24: 522
    params_part1_ans1_value: 'Yes'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'No'
    params_part1_ans2_feedback: Correct!
---
# {{ params_vars_title }}
A 2010 Survey asked {{ params_num24 }} Los Angeles residents, "What is the best hamburger place in Southern California? Five Guys Burgers? In-N-Out Burger? Fat Burger? Tommy's Hamburgers? Umami Burger? Or somewhere else?"

The distribution of responses by gender is shown below.

|                    | Male | Female | Total |
|--------------------|:------:|:--------:|:-------:|
| Five Guys          | {{ params_num1 }} | {{ params_num2 }} | {{ params_num3 }} |
| In-N-Out Burger    | {{ params_num4 }} | {{ params_num5 }} | {{ params_num6 }} |
| Fat Burger         | {{ params_num7 }} | {{ params_num8 }} | {{ params_num9 }} |
| Tommy's Hamburgers | {{ params_num10 }} | {{ params_num11 }} | {{ params_num12 }} |
| Umami Burger       | {{ params_num13 }} | {{ params_num14 }} | {{ params_num15 }} |
| Other              | {{ params_num16 }} | {{ params_num17 }} | {{ params_num18 }} |
| Not Sure           | {{ params_num19 }} | {{ params_num20 }} | {{ params_num21 }} |
| Total              | {{ params_num22 }} | {{ params_num23 }} | {{ params_num24 }} |

## Part 1

Are being female and liking Five Guys Burgers mutually exclusive?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

No. There are 6 females who like Five Guys Burgers.

## Part 2

What is the probability that a randomly chosen male likes In-N-Out the best? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

### pl-answer-panel

$p = {{ params_num4 }} / {{ params_num22 }} \approx {{ correct_answers.part2_ans_str }}$

## Part 3

What is the probability that a randomly chosen female likes In-N-Out the best? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

### pl-answer-panel

$p = {{ params_num5 }} / {{ params_num23 }} \approx {{ correct_answers.part3_ans_str }}$

## Part 4

What is the probability that a man and a woman who are dating both like In-N-Out the best? Note any assumption you make. Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

### pl-answer-panel

$p = {{ correct_answers.part2_ans_str }} \times {{ correct_answers.part3_ans_str }} \approx {{ correct_answers.part4_ans_str }}$ under the assumption of dating choices being independent of hamburger preference.

## Part 5

What is the probability that a randomly chosen person likes Umami best or that person is female? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

### pl-answer-panel

$p = \frac{ {{ params_num23 }} + {{ params_num15 }} - {{ params_num14 }} }{ {{ params_num24 }} } \approx {{ correct_answers.part5_ans_str }} $

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)