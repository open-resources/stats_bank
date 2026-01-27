---
title: Working backwards, Part I
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.2
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
- CR
assets: null
part1:
  type: number-input
  pl-customizations:
    rtol: 1.0e-05
    weight: 1
    allow-blank: true
    label: $\hat{p}= $
part2:
  type: number-input
  pl-customizations:
    rtol: 1.0e-05
    weight: 1
    allow-blank: true
    label: $\hat{p}= $
myst:
  substitutions:
    params:
      vars:
        title: Working backwards, Part I
      description:
        num1: 0.3
        num2: 0.3
        num3: 94
        num4: 0.05
---
# {{ params.vars.title }}
You are given the following hypotheses:

$H_0$: p = ${{ params.description.num1 }}$

$H_A$: p $\neq {{ params.description.num2 }}$

We know the sample size is ${{ params.description.num3 }}$. For what sample proportion would the p-value be equal to ${{ params.description.num4 }}$? Assume that all conditions necessary for inference are satisfied.

## Part 1

Use positive test statistic. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

## Part 2

Use negative test statistic. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)