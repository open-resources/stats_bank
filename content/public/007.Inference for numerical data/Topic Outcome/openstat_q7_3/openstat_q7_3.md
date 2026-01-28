---
title: Find the p-value, Part I
topic: Inference for numerical data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.4
- 7.1.1.5
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
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 3
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Find the p-value, Part I
      n: 9
      T: 2.29
      alpha: 0.01
      part2:
        ans1:
          value: do not reject $H_0$
          feedback: Nice work!
        ans2:
          value: reject $H_0$
          feedback: Incorrect, try again!
---
# {{ params.vars.title }}
An independent random sample is selected from an approximately normal population with an unknown standard deviation.

$n = {{ params.n }}$, T = ${{ params.T }}$

## Part 1

Find the p-value for the given sample size and test statistic.

## Part 2

Determine if the null hypothesis would be rejected at $\alpha = {{ params.alpha }}$.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)