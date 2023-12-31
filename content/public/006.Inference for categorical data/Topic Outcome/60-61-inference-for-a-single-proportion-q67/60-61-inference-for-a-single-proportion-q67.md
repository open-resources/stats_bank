---
title: Fireworks on July 4th
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.0
- 6.1.1.6
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
- AB
assets: null
part1:
  type: number-input
  pl-customizations:
    rtol: 0.1
    weight: 1
    allow-blank: false
    label: $ME= $
    suffix: $\%$
myst:
  substitutions:
    params_vars_title: Fireworks on July 4th
    params_vars_margin_of_error: 0.04113
    params_vars_margin_of_error_percent: 4.113
    params_vars_proportion: 46.0
    params_vars_p: 0.46
    params_vars_n: 564
    params_vars_z: 1.96
---
# {{ params_vars_title }}
A local news outlet reported that {{ params_vars_proportion }}% of {{ params_vars_n }} randomly sampled Kansas residents planned to set off fireworks on July 4th.

## Part 1

Determine the margin of error for the {{ params_vars_proportion }}% point estimate using a 95% confidence level.

### Answer Section

Please enter in a numeric value in %.

### pl-answer-panel

With a random sample, independence is satisfied. The success-failure condition is also satisfied.

$ME = z^{\star} \sqrt{ \frac{\hat{p} (1-\hat{p})} {n} } = 1.96 \sqrt{ \frac{ {{ params_vars_p }} \times  (1-\ {{ params_vars_p }} ) }{ {{ params_vars_n }} } } = {{ params.vars.margin_of_error }} \approx {{ params.vars.margin_of_error_percent }} $%

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)