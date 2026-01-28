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
    params:
      vars:
        title: Website registration
      description:
        num1: 728
        num2: 61
      part1:
        ans1:
          value: Independence
          feedback: Correct!
        ans2:
          value: Success-failure condition
          feedback: Correct!
      part3:
        ans1:
          value: The 90% confidence interval is approximately (0.0669, 0.0957). We
            are 90% confident that the true proportion of all first-time visitors
            who would register under the new design is between 6.69% and 9.57%.
          feedback: Try again please!
        ans2:
          value: The 90% confidence interval is approximately (0.0629, 0.1007). We
            are 90% confident that the true proportion of all first-time visitors
            who would register under the new design is between 6.29% and 10.07%.
          feedback: Try again please!
        ans3:
          value: The 90% confidence interval is approximately (0.0629, 0.0957). We
            are 90% confident that the true proportion of all first-time visitors
            who would register under the new design is between 6.29% and 9.57%.
          feedback: Try again please!
        ans4:
          value: The 90% confidence interval is approximately (0.0669, 0.1007). We
            are 90% confident that the true proportion of all first-time visitors
            who would register under the new design is between 6.69% and 10.07%.
          feedback: Correct!
---
# {{ params.vars.title }}
A website is trying to increase registration for first-time visitors, exposing 1% of these visitors to a new site design.

Of ${{ params.description.num1 }}$ randomly sampled visitors over a month who saw the new design, ${{ params.description.num2 }}$ registered.

## Part 1

Check any conditions required for constructing a confidence interval.

### Answer Section

- {{ params.part1.ans1.value}}
- {{ params.part1.ans2.value}}

## Part 2

Compute the standard error. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

## Part 3

Which of the following best describes this confidence interval for the fraction of first-time visitors of the site who would register under the new design (assuming stable behaviors by new visitors over time)?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)