---
title: National Health Plan, Part II
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
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
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: $n =$
myst:
  substitutions:
    params:
      vars:
        title: National Health Plan, Part II
        p_hat: 0.7
        p_hat_percent: 70.0
        margin_of_error_percent: 1.0
        z_score: 1.6449
        confidence: 90
        n: 5682
---
# {{ params.vars.title }}
A Kaiser Family Foundation poll for US adults in 2019 reported varying levels of support for a generic "National Health Plan" among different political affiliations. For Independents, it was found that approximately {{ params.vars.p_hat_percent }}% supported the plan.

There were various sample sizes for each group, but for this problem, we are focusing on the responses from the Independents.

## Part 1

If we wanted to estimate this number to within {{ params.vars.margin_of_error_percent }}% with {{ params.vars.confidence }}% confidence, what would be an appropriate sample size?

### Answer Section

Please enter in a numeric value.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)