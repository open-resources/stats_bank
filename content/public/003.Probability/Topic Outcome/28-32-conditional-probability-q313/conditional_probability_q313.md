---
title: Joint and Conditional Probabilities
topic: Probability
author: Sophie Varabioff
source: 3.13
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.4
- 3.1.1.5
- 3.1.1.9
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
- SV
assets: null
part1:
  type: dropdown
  pl-customizations:
    blank: true
    weight: 1
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part5:
  type: dropdown
  pl-customizations:
    blank: true
    weight: 1
part6:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
myst:
  substitutions:
    params_vars_title: Joint and Conditional Probabilities
    params_num1: 0.4
    params_num2: 0.7
    params_num3: 0.1
    params_part1_ans1_value: 'Yes'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'No'
    params_part1_ans2_feedback: Correct!
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Try again please!
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Correct!
---
# {{ params_vars_title }}
$P(A) = {{ params_num1 }}$
$P(B) = {{ params_num2 }}$

## Part 1

Can you compute $P(A \cap B)$ if you only know $P(A)$ and $P(B)$?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

No, but we could if A and B are independent.

## Part 2

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A \cap B)$?

### Answer Section

Please enter a numeric value between 0 and 1.

### Answer Section

Please enter a value between 0 and 1.

### pl-answer-panel

P2 $=$ {{ correct_answers.part2_ans }}

## Part 3

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A \cup B)$?

### Answer Section

Please enter a value between 0 and 1.

### pl-answer-panel

P3 $=$ {{ correct_answers.part3_ans }}

## Part 4

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A|B)$?

### Answer Section

Please enter a value between 0 and 1.

### pl-answer-panel

P4 $=$ {{ correct_answers.part4_ans }}

## Part 5

If we are given that $P(A \cap B) = {{ params_num3 }}$, are the random variables giving rise to events $A$ and $B$ independent?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

### pl-answer-panel

No, because ${{ params_num3 }}$ $\ne$ {{ correct_answers.part2_ans }}, where {{ correct_answers.part2_ans }} was the value computed under independence from part 2.

## Part 6

If we are given that $P(A \cap B)$ = ${{ params_num3 }}$, what is $P(A|B)$?

### Answer Section

Please enter a value between 0 and 1.

### pl-answer-panel

P6 $=$ {{ correct_answers.part6_ans }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)