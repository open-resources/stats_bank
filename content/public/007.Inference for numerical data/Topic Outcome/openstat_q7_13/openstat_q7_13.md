---
title: Car insurance savings
topic: Inference for numerical data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.14
- 7.1.1.15
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
    atol: 0.0001
    rtol: 1.0e-07
    weight: 1
    allow-blank: true
    label: $n= $
myst:
  substitutions:
    params_vars_title: Car insurance savings
    params_description_std: 101
    params_description_moe_max: 13
    params_description_confidence_level: 0.99
---
# {{ params_vars_title }}
<div class="mathjax_ignore">
A market researcher wants to evaluate car insurance savings at a competing company. Based on past studies he is assuming that the standard deviation of savings is ${{ params_description_std }}. He wants to collect data such that he can get a margin of error of no more than ${{ params.description.moe_max }} at a {{ params.description.confidence_level }} confidence level.
</div>

## Part 1

How large of a sample should he collect?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

If the sample is large, then the margin of error will be about
$1.96 \times ${{ params_description_std }}$ / \sqrt{n}$. We want this value to be less than ${{ params.description.moe_max }}$, which
leads to $n \geq 384.16$, meaning we need a sample size of at least 385 (round
up for sample size calculations!)

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)