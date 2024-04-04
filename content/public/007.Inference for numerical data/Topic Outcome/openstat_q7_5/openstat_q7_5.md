---
title: Working backwards, Part I
topic: Inference for numerical data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.0
- 7.1.1.1
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
    digits: 1
    weight: 1
    allow-blank: true
    label: $\bar{x}= $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    weight: 1
    allow-blank: true
    label: $s= $
myst:
  substitutions:
    params_vars_title: Working backwards, Part I
    params_description_confidence_level: 90
    params_description_lower: 20.43
    params_description_upper: 22.809
    params_description_sample_size: 34
    params_description_mean: 21.619500000000002
    params_description_moe: 1.1895000000000007
    params_description_t_crit: 1.6923603090303438
    params_description_s: 4.098369148643351
---
# {{ params_vars_title }}
A ${{ params.description.confidence_level }}$% confidence interval for a population mean, $\mu$, is given as (${{ params_description_lower }}$, ${{ params_description_upper }}$). This confidence interval is based on a simple random sample of ${{ params_description_sample_size }}$ observations. Assume that all conditions necessary for inference are satisfied. Use the $t$-distribution in any calculations.

## Part 1

Calculate the sample mean.

### Answer Section

Please enter a numeric value in.

## Part 2

Calculate the sample standard deviation.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

The mean is the midpoint: $\bar{x} = {{ params_description_mean}}$. Identify the margin of error:
$ME =  {{ params_description_moe}}$, then use $t^{\star}\_{35} = {{params.description.t_crit}}$ and $s = {{ params_description_s}}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)