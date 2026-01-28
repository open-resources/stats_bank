---
title: Grade distributions
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.4
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
  type: checkbox
  pl-customizations:
    weight: 1
    fixed-order: true
myst:
  substitutions:
    params:
      vars:
        title: Grade distributions
      description:
        ra_cf: 0.1
        num1: 0.2
        num2: 0.2
        num3: 0.2
        num4: 0.5
        num5: 0
        num6: 0
        num7: 1
        num8: 0
        num9: 0
        num10: 0.2
        num11: 0.2
        num12: 0.2
        num13: 0
        num14: 0
        num15: 0.2
        num16: 0.2
        num17: 0.5
        num18: 0.1
        num19: -0.5
        num20: 0.2
        num21: 0.1
        num22: 0.1
        num23: 0.1
        num24: 0.5
        num25: 0
        num26: -0.5
        num27: 1.1
        num28: 0
        num29: 0
      part1:
        ans1:
          value: a
          feedback: Invalid. Sum is greater than 1!
        ans2:
          value: b
          feedback: Valid. Probabilities are between 0 and 1, and they sum to 1
        ans3:
          value: c
          feedback: Invalid. Sum is less than 1
        ans4:
          value: d
          feedback: Invalid. There is a negative probability
        ans5:
          value: e
          feedback: Valid. Probabilities are between 0 and 1, and they sum to 1
        ans6:
          value: f
          feedback: Invalid. There is a negative probability
---
# {{ params.vars.title }}
Each row in the table below is a proposed grade distribution for a class. Identify each as a valid or invalid probability distribution.
| | A ------ | B ------ | C ------ | D ------ | F |
| --- | ------------ | ------------ | ------------ | ------------ | ------------ |
| (a) | ${{ params.description.num1 }}$ | ${{ params.description.num2 }}$ | ${{ params.description.num3 }}$ | ${{ params.description.num4 }}$ | ${{ params.description.ra_cf }}$
| (b) | ${{ params.description.num5 }}$ | ${{ params.description.num6 }}$ | ${{ params.description.num7 }}$ | ${{ params.description.num8 }}$ | ${{ params.description.num9 }}$
| (c) | ${{ params.description.num10 }}$ | ${{ params.description.num11 }}$ | ${{ params.description.num12 }}$ | ${{ params.description.num13 }}$ | ${{ params.description.num14 }}$
| (d) | ${{ params.description.num15 }}$ | ${{ params.description.num16 }}$ | ${{ params.description.num17 }}$ | ${{ params.description.num18 }}$ | ${{ params.description.num19 }}$
| (e) | ${{ params.description.num20 }}$ | ${{ params.description.num21 }}$ | ${{ params.description.num22 }}$ | ${{ params.description.num23 }}$ | ${{ params.description.num24 }}$
| (f) | ${{ params.description.num25 }}$ | ${{ params.description.num26 }}$ | ${{ params.description.num27 }}$ | ${{ params.description.num28 }}$ | ${{ params.description.num29 }}$

## Part 1

Select all valid probability distributions.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)