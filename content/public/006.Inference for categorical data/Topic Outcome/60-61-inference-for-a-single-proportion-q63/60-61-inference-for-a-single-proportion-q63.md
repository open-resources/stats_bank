---
title: Orange tabbies
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
- 6.1.1.1
- 6.1.1.2
- 6.1.1.3
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
  type: dropdown
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    rtol: 0.001
    weight: 1
    allow-blank: false
part3:
  type: dropdown
  pl-customizations:
    weight: 1
part4:
  type: dropdown
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Orange tabbies
        sample_size1: 30
        times: 64
        sample_size3: 127
        sample_size4: 194
      part1:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
      part3:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
      part4:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
---
# {{ params.vars.title }}
Suppose that 90% of orange tabby cats are male. Determine if the following statements are true or false.

## Part 1

The distribution of sample proportions of random samples of size {{ params.vars.sample_size1 }} is left skewed.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

Using a sample size that is {{ params.vars.times }} times as large will cause the standard error to be how many multiples of itself large?

### Answer Section

Please enter in a numeric value.

## Part 3

The distribution of sample proportions of random samples of size {{ params.vars.sample_size3 }} is approximately normal.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

The distribution of sample proportions of random samples of size {{ params.vars.sample_size4 }} is approximately normal.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)