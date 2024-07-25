---
title: Find the p-value, Part I
topic: Inference for numerical data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.4
- 7.1.1.5
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
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 3
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Find the p-value, Part I
    params_n: 14
    params_T: 1.59
    params_alpha: 0.05
    params_part2_ans1_value: do not reject $H_0$
    params_part2_ans1_feedback: Nice work!
    params_part2_ans2_value: reject $H_0$
    params_part2_ans2_feedback: Incorrect, try again!
---
# {{ params_vars_title }}
An independent random sample is selected from an approximately normal population with an unknown standard deviation.

$n = {{ params_n }}$, T = ${{ params_T }}$

## Part 1

Find the p-value for the given sample size and test statistic.

## Part 2

Determine if the null hypothesis would be rejected at $\alpha = {{ params_alpha }}$.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)