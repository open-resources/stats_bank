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
    params:
      vars:
        title: Quality control
      description:
        num1: 198
        num2: 22
      part1:
        ans1:
          value: The population of all computer chips ever produced by the factory.
          feedback: Try again please!
        ans2:
          value: The population of 198  computer chips sampled during a week of production.
          feedback: Try again please!
        ans3:
          value: All computer chips manufactured at the factory during the week of
            production.
          feedback: Correct!
        ans4:
          value: The population of 198 defective computer chips found in the sample.
          feedback: Try again please!
      part2:
        ans1:
          value: The fraction of computer chips manufactured at the factory over the
            entire year that had defects.
          feedback: Try again please!
        ans2:
          value: The fraction of the 198 sampled chips that had defects.
          feedback: Try again please!
        ans3:
          value: The fraction of computer chips manufactured at the factory during
            the week of production that had defects.
          feedback: Correct!
        ans4:
          value: The number of computer chips manufactured at the factory during the
            week of production.
          feedback: Try again please!
      part4:
        ans1:
          value: Mean
          feedback: Try again please!
        ans2:
          value: Median
          feedback: Try again please!
        ans3:
          value: Standard Error
          feedback: Correct!
        ans4:
          value: Standard Deviation
          feedback: Try again please!
      part6:
        ans1:
          value: Yes, the engineer should be surprised.
          feedback: Try again please!
        ans2:
          value: No, the engineer should not be surprised.
          feedback: Correct!
      part7:
        ans1:
          value: Yes, the value changes significantly.
          feedback: Try again please!
        ans2:
          value: No, the value does not change significantly.
          feedback: Correct!
      answer:
        num1: 0.02132
---
# {{ params.vars.title }}
As part of a quality control process for computer chips, an engineer at a factory randomly samples ${{ params.description.num1 }}$ chips during a week of production to test the current rate of chips with severe defects.

She finds that ${{ params.description.num2 }}$ of the chips are defective.

## Part 1

What population is under consideration in the data set?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

What parameter is being estimated?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

What is the point estimate for the parameter? Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

## Part 4

What is the name of the statistic we use to measure the uncertainty of the point estimate?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

Compute the value from part 4 for this context. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

## Part 6

The historical rate of defects is 10%.

Should the engineer be surprised by the observed rate of defects during the current week?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Part 7

Suppose the true population value was found to be 10%.

If we use this proportion to recompute the value in part 5 using $p = 0.1$ instead of $\hat{p}$, does the resulting value change much?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)