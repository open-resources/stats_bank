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
    params:
      vars:
        title: Car insurance savings
      description:
        std: 101
        moe_max: 20
        confidence_level: 0.96
---
# {{ params.vars.title }}
<div class="mathjax_ignore">
A market researcher wants to evaluate car insurance savings at a competing company. Based on past studies he is assuming that the standard deviation of savings is ${{ params.description.std }}. He wants to collect data such that he can get a margin of error of no more than ${{ params.description.moe_max }} at a {{ params.description.confidence_level }} confidence level.
</div>

## Part 1

How large of a sample should he collect?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)