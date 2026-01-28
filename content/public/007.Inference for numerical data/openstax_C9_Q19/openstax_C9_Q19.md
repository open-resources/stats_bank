---
title: Statistical Power
topic: Inference for numerical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.14
difficulty:
- easy
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
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: false
    label: $\text{Power} = $
myst:
  substitutions:
    params:
      vars:
        title: Statistical Power
      alpha: 0.035
      beta: 0.194
---
# {{ params.vars.title }}

## Part 1

A microbiologist is testing a water sample for E-coli. Suppose the null hypothesis, $H_0$, is: the sample does not contain E-coli. The probability that the sample does not contain E-coli, but the microbiologist thinks it does is ${{ params.alpha }}$. The probability that the sample does contain E-coli, but the microbiologist thinks it does not is ${{ params.beta }}$. What is the power of this test?

### Answer Section

Please enter in a numeric value.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)