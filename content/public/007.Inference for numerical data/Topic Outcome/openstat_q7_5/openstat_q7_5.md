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
        confidence_level: 93
        lower: 17.092
        upper: 23.897
        sample_size: 33
        mean: 20.4945
        moe: 3.4025
        t_crit: 1.8746074910937924
        s: 10.426649043977228
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