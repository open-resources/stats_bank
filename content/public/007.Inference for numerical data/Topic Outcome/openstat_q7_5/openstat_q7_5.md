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
    params:
      vars:
        title: Working backwards, Part I
      description:
        confidence_level: 96
        lower: 17.239
        upper: 18.965
        sample_size: 36
        mean: 18.102
        moe: 0.8629999999999995
        t_crit: 2.13315662523993
        s: 2.42738856525249
---
# {{ params.vars.title }}
A ${{ params.description.confidence_level }}$% confidence interval for a population mean, $\mu$, is given as (${{ params.description.lower }}$, ${{ params.description.upper }}$). This confidence interval is based on a simple random sample of ${{ params.description.sample_size }}$ observations. Assume that all conditions necessary for inference are satisfied. Use the $t$-distribution in any calculations.

## Part 1

Calculate the sample mean.

### Answer Section

Please enter a numeric value in.

## Part 2

Calculate the sample standard deviation.

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)