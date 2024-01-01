---
title: Relaxing after work
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.3
- 5.1.1.12
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
myst:
  substitutions:
    params_vars_title: Relaxing after work
    params_part2_num1: 1190
    params_part2_moe_comparison: larger
    params_part2_ans1_value: The confidence level of the new interval is the same
      as the previous interval.
    params_part2_ans1_feedback: Try again please! Recall that the width of the confidence
      interval increases as the confidence level increases.
    params_part2_ans2_value: The confidence level of the new interval must be lower
      than that of the previous interval.
    params_part2_ans2_feedback: Try again please! Recall that the width of the confidence
      interval increases as the confidence level increases.
    params_part2_ans3_value: The confidence level of the new interval must be higher
      than that of the previous interval.
    params_part2_ans3_feedback: Correct!
    params_part2_ans4_value: The confidence level cannot be determined from the information
      given.
    params_part2_ans4_feedback: Try again please! Recall that the width of the confidence
      interval increases as the confidence level increases.
    params_part3_num1: 2617
    params_part3_num2: 95
    params_part3_ans1_value: The new margin of error will be larger, as a larger sample
      size always leads to a larger margin of error.
    params_part3_ans1_feedback: Try again please! Recall that as the sample size increases,
      the standard error decreases, which will decrease the margin of error.
    params_part3_ans2_value: The new margin of error will be the same, regardless
      of changes in the sample size.
    params_part3_ans2_feedback: Try again please! Recall that as the sample size increases,
      the standard error decreases, which will decrease the margin of error.
    params_part3_ans3_value: The new margin of error will be smaller, as a larger
      sample size leads to a smaller margin of error.
    params_part3_ans3_feedback: Correct!
    params_part3_ans4_value: The new margin of error cannot be determined without
      knowing the actual values of the confidence intervals.
    params_part3_ans4_feedback: Try again please! Recall that as the sample size increases,
      the standard error decreases, which will decrease the margin of error.
    params_description_num1: 1190
    params_description_num2: 95
    params_description_num3: 1.36
    params_description_num4: 1.87
    params_part1_ans1_value: The mean number of hours spent relaxing is exactly 1.65
      hours.
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: The mean number of hours spent relaxing is not accurately
      estimated with this data.
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: We are 95% confident that the average time spent relaxing
      by Americans falls between 1.36 and 1.87 hours.
    params_part1_ans3_feedback: Correct!
    params_part1_ans4_value: This interval represents the minimum and maximum number
      of hours Americans spend relaxing.
    params_part1_ans4_feedback: Try again please!
---
# {{ params_vars_title }}
The General Social Survey asked the question: "After an average work day, about how many hours do you have to relax or pursue activities that you enjoy?" to a random sample of ${{ params_description_num1 }}$ Americans.

A ${{ params_description_num2 }}$% confidence interval for the mean number of hours spent relaxing or pursuing activities they enjoy was (${{ params_description_num3 }}$, ${{ params_description_num4 }}$).

## Part 1

Interpret this interval in context of the data.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

We are ${{ params_part3_num2 }}$% confident that Americans spend an average of ${{ params_description_num3 }}$ to ${{ params_description_num4 }}$ hours per day relaxing or pursuing activities they enjoy

## Part 2

Suppose another set of researchers reported a confidence interval with a {{ params.part2.moe_comparison }} margin of error based on the same sample of ${{ params_part2_num1 }}$ Americans. How does their confidence level compare to the confidence level of the interval stated above?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

Their confidence level must be higher as the width of the confidence interval increases as the confidence level increases

## Part 3

Suppose next year a new survey asking the same question is conducted, and this time the sample size is ${{ params_part3_num1 }}$. Assuming that the population characteristics, with respect to how much time people spend relaxing after work, have not changed much within a year. How will the margin of error of the ${{ params_part3_num2 }}$% confidence interval constructed based on data from the new survey compare to the margin of error of the interval stated above?

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

### pl-answer-panel

The new margin of error will be smaller, since as the sample size increases, the standard error decreases,which will decrease the margin of error

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)