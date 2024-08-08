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
    params_vars_title: Grade distributions
    params_description_ra_cf: 0.8
    params_description_num1: 0.1
    params_description_num2: 0.1
    params_description_num3: 0.1
    params_description_num4: 0.1
    params_description_num5: 0
    params_description_num6: 0
    params_description_num7: 1
    params_description_num8: 0
    params_description_num9: 0
    params_description_num10: 0.1
    params_description_num11: 0.1
    params_description_num12: 0.1
    params_description_num13: 0
    params_description_num14: 0
    params_description_num15: 0.1
    params_description_num16: 0.2
    params_description_num17: 0.1
    params_description_num18: 0.2
    params_description_num19: -0.2
    params_description_num20: 0.1
    params_description_num21: 0.2
    params_description_num22: 0.1
    params_description_num23: 0.1
    params_description_num24: 0.5
    params_description_num25: 0
    params_description_num26: -0.2
    params_description_num27: 1.1
    params_description_num28: 0
    params_description_num29: 0
    params_part1_ans1_value: a
    params_part1_ans1_feedback: Invalid. Sum is greater than 1!
    params_part1_ans2_value: b
    params_part1_ans2_feedback: Valid. Probabilities are between 0 and 1, and they
      sum to 1
    params_part1_ans3_value: c
    params_part1_ans3_feedback: Invalid. Sum is less than 1
    params_part1_ans4_value: d
    params_part1_ans4_feedback: Invalid. There is a negative probability
    params_part1_ans5_value: e
    params_part1_ans5_feedback: Valid. Probabilities are between 0 and 1, and they
      sum to 1
    params_part1_ans6_value: f
    params_part1_ans6_feedback: Invalid. There is a negative probability
---
# {{ params_vars_title }}
Each row in the table below is a proposed grade distribution for a class. Identify each as a valid or invalid probability distribution.
|  |  A ------   |  B ------  |  C ------  |  D ------  |  F |
| --- | ------------ | ------------ | ------------ | ------------ | ------------ |
| (a) | ${{ params_description_num1 }}$   | ${{ params_description_num2 }}$   | ${{ params_description_num3 }}$   | ${{ params_description_num4 }}$   | ${{ params.description.ra_cf }}$
| (b) | ${{ params_description_num5 }}$     | ${{ params_description_num6 }}$     | ${{ params_description_num7 }}$     | ${{ params_description_num8 }}$     | ${{ params_description_num9 }}$
| (c) | ${{ params_description_num10 }}$   | ${{ params_description_num11 }}$   | ${{ params_description_num12 }}$   | ${{ params_description_num13 }}$     | ${{ params_description_num14 }}$
| (d) | ${{ params_description_num15 }}$   | ${{ params_description_num16 }}$   | ${{ params_description_num17 }}$   | ${{ params_description_num18 }}$   | ${{ params_description_num19 }}$
| (e) | ${{ params_description_num20 }}$   | ${{ params_description_num21 }}$   | ${{ params_description_num22 }}$   | ${{ params_description_num23 }}$   | ${{ params_description_num24 }}$
| (f) | ${{ params_description_num25 }}$     | ${{ params_description_num26 }}$  | ${{ params_description_num27 }}$   | ${{ params_description_num28 }}$     | ${{ params_description_num29 }}$

## Part 1

Select all valid probability distributions.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)