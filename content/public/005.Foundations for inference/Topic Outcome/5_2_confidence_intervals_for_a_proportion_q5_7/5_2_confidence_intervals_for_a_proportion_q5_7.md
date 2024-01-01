---
title: Chronic illness, Part I
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.8
- 5.1.1.13
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Chronic illness, Part I
    params_description_num1: 2018
    params_description_num2: 1.1
    params_description_num3: 38
    params_part1_ans1_value: '[33.8 %, 43.2 %]'
    params_part1_ans1_feedback: 'Try again! Recall that the general formula is $point~estimate
      \pm z^{\star}$ × SE. First, identify the three different values. The point estimate
      is 38%,$z^{\star} = 1.96$ for a 95% confidence level, and SE = 1.1%.Then, plug
      the values into the formula: 38% $\pm 1.96$ × 1.1%'
    params_part1_ans2_value: '[35.8 %, 43.2 %]'
    params_part1_ans2_feedback: 'Try again! Recall that the general formula is $point~estimate
      \pm z^{\star}$ × SE. First, identify the three different values. The point estimate
      is 38%,$z^{\star} = 1.96$ for a 95% confidence level, and SE = 1.1%.Then, plug
      the values into the formula: 38% $\pm 1.96$ × 1.1%'
    params_part1_ans3_value: '[33.8 %, 40.2 %]'
    params_part1_ans3_feedback: 'Try again! Recall that the general formula is $point~estimate
      \pm z^{\star}$ × SE. First, identify the three different values. The point estimate
      is 38%,$z^{\star} = 1.96$ for a 95% confidence level, and SE = 1.1%.Then, plug
      the values into the formula: 38% $\pm 1.96$ × 1.1%'
    params_part1_ans4_value: '[35.8 %, 40.2 %]'
    params_part1_ans4_feedback: Correct!
    params_part2_ans1_value: There is a 95% probability that between a and b of U.S.
      adults live with one or more chronic conditions.
    params_part2_ans1_feedback: Try again please!
    params_part2_ans2_value: The Pew Research Foundation is 95% confident that their
      sample proportion is between a and b.
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: 95% of all samples taken will result in an estimate between
      a and b.
    params_part2_ans3_feedback: Try again please!
    params_part2_ans4_value: We can be 95% confident that the true population proportion
      of U.S. adults living with one or more chronic conditions falls between a and
      b.
    params_part2_ans4_feedback: Correct!
---
# {{ params_vars_title }}
In ${{ params_description_num1 }}$, the Pew Research Foundation reported that "${{ params_description_num3 }}$% of U.S. adults report that they live with one or more chronic conditions".

However, this value was based on a sample, so it may not be a perfect estimate for the population parameter of interest on its own.

The study reported a standard error of about ${{ params_description_num2 }}$%, and a normal model may reasonably be used in this setting.

## Part 1

Choose the appropriate 95% confidence interval for the proportion of U.S. adults who live with one or more chronic conditions.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

## Part 2

Interpret the confidence interval in the context of the study.

Note: a and b is the correct 95% confidence interval \[a, b\] computed in part (1).

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

We are 95% confident that the proportion of US adults who live with one or more chronic conditions is between a% and b%.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)