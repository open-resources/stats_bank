---
title: Quality control
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 5.1.1.1
- 5.1.1.2
- 5.1.1.4
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
part3:
  type: number-input
  pl-customizations:
    rtol: 0.0005
    weight: 1
    allow-blank: true
    label: $\hat{p} = $
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    rtol: 0.0005
    weight: 1
    allow-blank: true
    label: $value= $
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Quality control
    params_description_num1: 225
    params_description_num2: 31
    params_part1_ans1_value: The population of all computer chips ever produced by
      the factory.
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: The population of 225  computer chips sampled during
      a week of production.
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: All computer chips manufactured at the factory during
      the week of production.
    params_part1_ans3_feedback: Correct!
    params_part1_ans4_value: The population of 225 defective computer chips found
      in the sample.
    params_part1_ans4_feedback: Try again please!
    params_part2_ans1_value: The fraction of computer chips manufactured at the factory
      over the entire year that had defects.
    params_part2_ans1_feedback: Try again please!
    params_part2_ans2_value: The fraction of the 225 sampled chips that had defects.
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: The fraction of computer chips manufactured at the factory
      during the week of production that had defects.
    params_part2_ans3_feedback: Correct!
    params_part2_ans4_value: The number of computer chips manufactured at the factory
      during the week of production.
    params_part2_ans4_feedback: Try again please!
    params_part4_ans1_value: Mean
    params_part4_ans1_feedback: Try again please!
    params_part4_ans2_value: Median
    params_part4_ans2_feedback: Try again please!
    params_part4_ans3_value: Standard Error
    params_part4_ans3_feedback: Correct!
    params_part4_ans4_value: Standard Deviation
    params_part4_ans4_feedback: Try again please!
    params_part6_ans1_value: Yes, the engineer should be surprised.
    params_part6_ans1_feedback: Try again please!
    params_part6_ans2_value: No, the engineer should not be surprised.
    params_part6_ans2_feedback: Correct!
    params_part7_ans1_value: Yes, the value changes significantly.
    params_part7_ans1_feedback: Try again please!
    params_part7_ans2_value: No, the value does not change significantly.
    params_part7_ans2_feedback: Correct!
    params_answer_num1: 0.02
---
# {{ params_vars_title }}
As part of a quality control process for computer chips, an engineer at a factory randomly samples ${{ params_description_num1 }}$ chips during a week of production to test the current rate of chips with severe defects.

She finds that ${{ params_description_num2 }}$ of the chips are defective.

## Part 1

What population is under consideration in the data set?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

The sample is from all computer chips manufactured at the factory during the week of production.

We might be tempted to generalize the population to represent all weeks, but we should exercise caution here since the rate of defects may change over time.

## Part 2

What parameter is being estimated?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

The fraction of computer chips manufactured at the factory during the week of production that had defects.

## Part 3

What is the point estimate for the parameter? Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Estimate the parameter using the data: $\hat{p} = \frac{ {{params_description_num2}} }{ {{ params_description_num1}} } = {{ correct_answers.part3_ans }} $

## Part 4

What is the name of the statistic we use to measure the uncertainty of the point estimate?

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

### pl-answer-panel

Standard error (or SE)

## Part 5

Compute the value from part 4 for this context. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Compute the SE using $\hat{p} = {{ correct_answers.part3_ans }}$ in place of $p$:$SE \approx \sqrt{\frac{\hat{p}(1 - \hat{p})}{n}} = {{ correct_answers.part5_ans }}$

## Part 6

The historical rate of defects is 10%.

Should the engineer be surprised by the observed rate of defects during the current week?

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

### pl-answer-panel

The standard error is the standard deviation of $\hat{p}$.

If the value of 0.10 would be about one standard error away from the observed value, which would not represent a very uncommon deviation, then the engineer should not be surprised. Vice versa.

(Usually beyond about 2 standard errors is a good rule of thumb.)

## Part 7

Suppose the true population value was found to be 10%.

If we use this proportion to recompute the value in part 5 using $p = 0.1$ instead of $\hat{p}$, does the resulting value change much?

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}

### pl-answer-panel

Recomputed standard error using $p = 0.1$: $SE = \sqrt{\frac {0.1(1 - 0.1)} { {{ params_description_num1 }} }} = {{ params_answer_num1 }}$.

This value isn't very different, which is typical when the standard error is computed using relatively similar proportions (and even sometimes when those proportions are quite different!)

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)