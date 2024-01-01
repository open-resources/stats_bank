---
title: Waiting at an ER, Part I
topic: Foundations for inference
author: Camilla Ren
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.7
- 5.1.1.8
- 5.1.1.11
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
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Waiting at an ER, Part I
    params_ci_lower: 140
    params_ci_higher: 149
    params_part1_num1: 95
    params_part1_num2: 60
    params_part1_ans1_value: 'True'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'False'
    params_part1_ans2_feedback: Correct!
    params_part2_num1: 95
    params_part2_ans1_value: 'True'
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: 'False'
    params_part2_ans2_feedback: Try again please!
    params_part3_num1: 95
    params_part3_ans1_value: 'True'
    params_part3_ans1_feedback: Try again please!
    params_part3_ans2_value: 'False'
    params_part3_ans2_feedback: Correct!
    params_part4_num1: 106
    params_part4_num2: 95
    params_part4_ans1_value: 'True'
    params_part4_ans1_feedback: Try again please!
    params_part4_ans2_value: 'False'
    params_part4_ans2_feedback: Correct!
    params_part5_num1: 4.5
    params_part5_num2: 143.5
    params_part5_ans1_value: 'True'
    params_part5_ans1_feedback: Try again please!
    params_part5_ans2_value: 'False'
    params_part5_ans2_feedback: Correct!
    params_part6_num1: 95
    params_part6_ans1_value: 'True'
    params_part6_ans1_feedback: Try again please!
    params_part6_ans2_value: 'False'
    params_part6_ans2_feedback: Correct!
    params_description_num1: 60
    params_description_num2: 95
    params_description_num3: 140
    params_description_num4: 149
---
# {{ params_vars_title }}
A hospital administrator hoping to improve wait times decides to estimate the average emergency room waiting time at her hospital. She collects a simple random sample of ${{ params_description_num1 }}$ patients and determines the time (in minutes) between when they checked in to the ER until they were first seen by a doctor. A ${{ params_description_num2 }}$% confidence interval based on this sample is (${{ params.ci_lower }}$ minutes, ${{ params.ci_higher }}$ minutes), which is based on the normal model for the mean. Determine whether the following statements are true or false, and explain your reasoning.

## Part 1

We are ${{ params_part1_num1 }}$% confident that the average waiting time of these ${{ params_part1_num2 }}$ emergency room patients is between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

False. The point estimate is always in the confidence interval,
and this is a non-sensical use of a confidence interval with a point estimate
(because the point estimate is, by design, listed within the confidence interval)

## Part 2

We are ${{ params_part2_num1 }}$% confident that the average waiting time of all patients at this hospital's emergency room is between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

True

## Part 3

${{ params_part3_num1 }}$% of random samples have a sample mean between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

### pl-answer-panel

False. The confidence interval is not about a sample mean

## Part 4

A ${{ params_part4_num1 }}$% confidence interval would be narrower than the ${{ params_part4_num2 }}$% confidence interval since we need to be more sure of our estimate.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

### pl-answer-panel

False. To be more confident that we capture the parameter, we need a wider
interval. Think about needing a bigger net to be more sure of catching a fish in
a murky lake

## Part 5

The margin of error is ${{ params_part5_num1 }}$ and the sample mean is ${{ params_part5_num2 }}$.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

### pl-answer-panel

True. Optional explanation: This is true since the normal model was used to
model the sample mean. The margin of error is half the width of the interval,
and the sample mean is the midpoint of the interval

## Part 6

In order to decrease the margin of error of a ${{ params_part6_num1 }}$% confidence interval to half of what it is now, we would need to double the sample size. (Hint: the margin of error for a mean scales in the same way with sample size as the margin of error for a proportion.)

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

### pl-answer-panel

False. In the calculation of the standard error, we divide the standard
deviation by the square root of the sample size. To cut the SE (or margin of
error) in half, we would need to sample $2^2 = 4$ times the number of people in
the initial sample

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)