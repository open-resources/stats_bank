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
    params:
      vars:
        title: Joint and Conditional Probabilities
      num1: 0.3
      num2: 0.6
      num3: 0.1
      part1:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
      part5:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
$P(A) = {{ params.num1 }}$
$P(B) = {{ params.num2 }}$

## Part 1

Can you compute $P(A \cap B)$ if you only know $P(A)$ and $P(B)$?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A \cap B)$?

### Answer Section

Please enter a numeric value between 0 and 1.

### Answer Section

Please enter a value between 0 and 1.

## Part 3

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A \cup B)$?

### Answer Section

Please enter a value between 0 and 1.

## Part 4

Assuming that events $A$ and $B$ arise from independent random processes, what is $P(A|B)$?

### Answer Section

Please enter a value between 0 and 1.

## Part 5

If we are given that $P(A \cap B) = {{ params.num3 }}$, are the random variables giving rise to events $A$ and $B$ independent?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Part 6

If we are given that $P(A \cap B)$ = ${{ params.num3 }}$, what is $P(A|B)$?

### Answer Section

Please enter a value between 0 and 1.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)