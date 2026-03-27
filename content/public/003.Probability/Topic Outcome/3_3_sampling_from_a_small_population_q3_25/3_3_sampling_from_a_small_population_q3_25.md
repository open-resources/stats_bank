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
    params:
      vars:
        title: Chips in a bag
      description:
        num1: 3
        num2: 2
        num3: 2
        n1: 6
        n: 7
        blue1: 1
      part4:
        ans1:
          value: 'Yes'
          feedback: Incorrect. Removing one chip meaningfully changes the probability
            of what might be drawn next.
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
Imagine you have a bag containing ${{ params.description.num1 }}$ red, ${{ params.description.num2 }}$ blue, and ${{ params.description.num3 }}$ orange chips.

## Part 1

Suppose you draw a chip and it is blue. If drawing without replacement, what is the probability the next is also blue?

### Answer Section

Please enter a numeric value in.

## Part 2

Suppose you draw a chip and it is orange, and then you draw a second chip without replacement. What is the probability this second chip is blue?

### Answer Section

Please enter a numeric value in.

## Part 3

If drawing without replacement, what is the probability of drawing two blue chips in a row?

### Answer Section

Please enter a numeric value in.

## Part 4

When drawing without replacement, are the draws independent? Explain.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)