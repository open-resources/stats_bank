---
title: Cyberbullying rates
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.7
- 5.1.1.13
difficulty:
- undefined
randomization:
- 2
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
myst:
  substitutions:
    params_vars_title: Cyberbullying rates
    params_part2_num1: 73
    params_part2_ans1_value: Yes, the claim is supported since 73% is greater than
      the lower limit of the confidence interval.
    params_part2_ans1_feedback: Try again please!
    params_part2_ans2_value: Yes, the claim is supported because the upper limit of
      the confidence interval is 68%, which is close to 73%.
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: No, the claim is not supported since 73% falls outside
      the confidence interval.
    params_part2_ans3_feedback: Correct! The value of 73% lies outside of the interval,
      so we have convincing evidence that the researcher's conjecture is wrong.
    params_part2_ans4_value: No, the claim is not supported because the confidence
      interval is too narrow.
    params_part2_ans4_feedback: Try again please!
    params_part3_num1: 90
    params_part3_ans1_value: Yes, the claim would be supported, as a 90% confidence
      interval would be wider than a 95% confidence interval.
    params_part3_ans1_feedback: Try again please!
    params_part3_ans2_value: Yes, the claim would be supported, as a 90% confidence
      interval is less strict than a 95% confidence interval.
    params_part3_ans2_feedback: Try again please!
    params_part3_ans3_value: No, the claim would not be supported, as a 90% confidence
      interval would be narrower than a 95% confidence interval.
    params_part3_ans3_feedback: Correct! A 90% confidence interval will be narrower
      than a 95% confidence interval. Even without calculating the interval, we can
      tell that 73% would not fall in the interval, and we would reject the researcher's
      conjecture based on a 90% confidence level as well.
    params_part3_ans4_value: It cannot be determined without calculating the 90% confidence
      interval.
    params_part3_ans4_feedback: Try again please!
    params_description_num1: 55
    params_description_num2: 68
    params_description_num3: 95
    params_part1_ans1_value: No, the claim is not supported because the upper limit
      of the interval is above 60%, which is not a majority.
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: Yes, the claim is supported, but only because the interval
      is above 55%, not necessarily indicating a majority.
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: Yes, the claim is supported since the entire interval
      lies above 50%, indicating a majority.
    params_part1_ans3_feedback: Correct! This claim is reasonable since the entire
      interval lies above 50%.
    params_part1_ans4_value: No, the claim is not supported because the interval is
      wide, implying a high level of uncertainty.
    params_part1_ans4_feedback: Try again please!
---
# {{ params_vars_title }}
Teens were surveyed about cyberbullying, and ${{ params_description_num1 }}$% to ${{ params_description_num2 }}$% reported experiencing cyberbullying (${{ params_description_num3 }}$% confidence interval).

Answer the following questions based on this interval.

## Part 1

A newspaper claims that a majority of teens have experienced cyberbullying.

Is this claim supported by the confidence interval? Choose an appropriate reason.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

## Part 2

A researcher conjectured that ${{ params_part2_num1 }}$% of teens have experienced cyberbullying.

Is this claim supported by the confidence interval? Choose an appropriate reason.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

## Part 3

Without actually calculating the interval, determine if the claim of the researcher from part 2 would be supported based on a ${{ params_part3_num1 }}$% confidence interval?

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

### pl-answer-panel

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)