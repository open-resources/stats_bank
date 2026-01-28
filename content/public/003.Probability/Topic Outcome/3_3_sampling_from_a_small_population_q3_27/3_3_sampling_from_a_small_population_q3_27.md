---
title: Student outfits
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.4
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
- CY
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: true
    label: $P= $
myst:
  substitutions:
    params:
      vars:
        title: Student outfits
      description:
        num1: 23
        num2: 11
        jeans1: 10
        num3: 5
        num4: 4
        num6: 3
        num5: 3
        total: 23
        total1: 22
        total2: 21
        prob: 0.0311
---
# {{ params.vars.title }}
In a classroom with ${{ params.description.num1 }}$ students, ${{ params.description.num2 }}$ students are wearing jeans, ${{ params.description.num3 }}$ are wearing shorts, ${{ params.description.num4 }}$ are wearing skirts, and the rest are wearing leggings.

## Part 1

If we randomly select ${{ params.description.num5 }}$ students without replacement, what is the probability that one of the selected students is wearing leggings and the other two are wearing jeans? Round to 4 decimal places. Note that these are mutually exclusive clothing options.

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)