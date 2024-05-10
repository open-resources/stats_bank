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
    params_vars_title: Student outfits
    params_description_num1: 18
    params_description_num2: 5
    params_description_jeans1: 4
    params_description_num3: 3
    params_description_num4: 9
    params_description_num6: 1
    params_description_num5: 3
    params_description_total: 18
    params_description_total1: 17
    params_description_total2: 16
    params_description_prob: 0.0041
---
# {{ params_vars_title }}
In a classroom with ${{ params_description_num1 }}$ students, ${{ params_description_num2 }}$ students are wearing jeans, ${{ params_description_num3 }}$ are wearing shorts, ${{ params_description_num4 }}$ are wearing skirts, and the rest are wearing leggings.

## Part 1

If we randomly select ${{ params_description_num5 }}$ students without replacement, what is the probability that one of the selected students is wearing leggings and the other two are wearing jeans? Round to 4 decimal places. Note that these are mutually exclusive clothing options.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$P(^1$leggings, $^2$jeans, $^3$jeans$) = \frac{ {{ params_description_num6 }} }{ {{ params_description_num1 }} } \times \frac{ {{ params_description_num2 }} }{ {{ params_description_total1 }} } \times \frac{ {{ params_description_jeans1 }} }{ {{ params_description_total2 }} } = {{ params_description_prob }}$.
However, the person with leggings could have come 2nd or 3rd, and these each
have this same probability, so ${{ params_description_num5 }} \times {{ params_description_prob }} = {{ correct_answers.part1_ans }}$

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)