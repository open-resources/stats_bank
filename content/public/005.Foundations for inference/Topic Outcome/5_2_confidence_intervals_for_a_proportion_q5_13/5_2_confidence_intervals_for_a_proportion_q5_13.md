---
title: Website registration
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 5.1.1.2
- 5.1.1.6
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
  type: checkbox
  pl-customizations:
    weight: 1
    fixed-order: true
part2:
  type: number-input
  pl-customizations:
    rtol: 1.0e-05
    weight: 1
    allow-blank: true
    label: $SE= $
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Website registration
    params_description_num1: 767
    params_description_num2: 69
    params_part1_ans1_value: Independence
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: Success-failure condition
    params_part1_ans2_feedback: Correct!
    params_part3_ans1_value: The 90% confidence interval is approximately (0.073,
      0.102). We are 90% confident that the true proportion of all first-time visitors
      who would register under the new design is between 7.3% and 10.2%.
    params_part3_ans1_feedback: Try again please!
    params_part3_ans2_value: The 90% confidence interval is approximately (0.069,
      0.107). We are 90% confident that the true proportion of all first-time visitors
      who would register under the new design is between 6.9% and 10.7%.
    params_part3_ans2_feedback: Try again please!
    params_part3_ans3_value: The 90% confidence interval is approximately (0.069,
      0.102). We are 90% confident that the true proportion of all first-time visitors
      who would register under the new design is between 6.9% and 10.2%.
    params_part3_ans3_feedback: Try again please!
    params_part3_ans4_value: The 90% confidence interval is approximately (0.073,
      0.107). We are 90% confident that the true proportion of all first-time visitors
      who would register under the new design is between 7.3% and 10.7%.
    params_part3_ans4_feedback: Correct!
---
# {{ params_vars_title }}
A website is trying to increase registration for first-time visitors, exposing 1% of these visitors to a new site design.

Of ${{ params_description_num1 }}$ randomly sampled visitors over a month who saw the new design, ${{ params_description_num2 }}$ registered.

## Part 1

Check any conditions required for constructing a confidence interval.

### Answer Section

- {{ params_part1_ans1_value}}
- {{ params_part1_ans2_value}}

### pl-answer-panel

The visitors are from a simple random sample, so independence is satisfied.

The success-failure condition is also satisfied, with both ${{ params_description_num2 }}$ and ${{ params_description_num1 }}$ - ${{ params_description_num2 }}$ above 10.

Therefore, we can use a normal distribution to model $\hat{p}$ and construct a confidence interval.

## Part 2

Compute the standard error. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

The sample proportion is $\hat{p} = \frac{ {{params_description_num2}} }{ {{params_description_num1}} }$.

The standard error is $SE = \sqrt{\frac{p(1 - p)}{n}}\approx \sqrt{\frac{\hat{p}(1 - \hat{p})}{n}}$

## Part 3

Which of the following best describes this confidence interval for the fraction of first-time visitors of the site who would register under the new design (assuming stable behaviors by new visitors over time)?

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

### pl-answer-panel

For a 90% confidence interval, use $z^{\star} = 1.6449$.

The confidence interval is $\hat{p}  \pm 1.6449 \times {{ params.answer.num2 }}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)