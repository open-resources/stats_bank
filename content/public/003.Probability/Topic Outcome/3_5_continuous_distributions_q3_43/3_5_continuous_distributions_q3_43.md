---
title: Cost of breakfast
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
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
    rtol: 0.0001
    weight: 1
    allow-blank: true
    label: $E= \$$
part2:
  type: number-input
  pl-customizations:
    rtol: 0.02
    weight: 1
    allow-blank: true
    label: $SD= \$$
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: $E= \$$
part4:
  type: number-input
  pl-customizations:
    rtol: 0.02
    weight: 1
    allow-blank: true
    label: $SD= \$$
myst:
  substitutions:
    params:
      vars:
        title: Cost of breakfast
      description:
        num1: '1.34'
        std: '0.24'
        num2: '2.38'
        num3: '0.10'
---
# {{ params.vars.title }}
<div class="mathjax_ignore">
Sally gets a cup of coffee and a muffin every day for breakfast from one of the many coffee shops in her neighborhood. She picks a coffee shop each morning at random and independently of previous days. The average price of a cup of coffee is ${{ params.description.num1 }} with a standard deviation of ${{ params.description.std }}, the average price of a muffin is ${{ params.description.num2 }} with a standard deviation of ${{ params.description.num3 }} and the two prices are independent of each other. (Round the following to 2 decimal places)
</div>

## Part 1

What is the mean she spends on breakfast daily?

### Answer Section

Please enter a numeric value in.

## Part 2

What is the standard deviation of the amount she spends on breakfast daily?

### Answer Section

Please enter a numeric value in.

## Part 3

What is the mean of the amount she spends on breakfast weekly (7~days)?

### Answer Section

Please enter a numeric value in.

## Part 3

What is the standard deviation of the amount she spends on breakfast weekly (7~days)?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)