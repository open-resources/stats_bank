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
    params:
      vars:
        title: Waiting at an ER, Part I
      ci_lower: 133
      ci_higher: 154
      part1:
        num1: 95
        num2: 63
        ans1:
          value: 'True'
          feedback: Try again please!
        ans2:
          value: 'False'
          feedback: Correct!
      part2:
        num1: 95
        ans1:
          value: 'True'
          feedback: Correct!
        ans2:
          value: 'False'
          feedback: Try again please!
      part3:
        num1: 95
        ans1:
          value: 'True'
          feedback: Try again please!
        ans2:
          value: 'False'
          feedback: Correct!
      part4:
        num1: 97
        num2: 95
        ans1:
          value: 'True'
          feedback: Try again please!
        ans2:
          value: 'False'
          feedback: Correct!
      part5:
        num1: 9.5
        num2: 142.5
        ans1:
          value: 'True'
          feedback: Try again please!
        ans2:
          value: 'False'
          feedback: Correct!
      part6:
        num1: 95
        ans1:
          value: 'True'
          feedback: Try again please!
        ans2:
          value: 'False'
          feedback: Correct!
      description:
        num1: 63
        num2: 95
        num3: 133
        num4: 154
---
# {{ params.vars.title }}
A hospital administrator hoping to improve wait times decides to estimate the average emergency room waiting time at her hospital. She collects a simple random sample of ${{ params.description.num1 }}$ patients and determines the time (in minutes) between when they checked in to the ER until they were first seen by a doctor. A ${{ params.description.num2 }}$% confidence interval based on this sample is (${{ params.ci_lower }}$ minutes, ${{ params.ci_higher }}$ minutes), which is based on the normal model for the mean. Determine whether the following statements are true or false, and explain your reasoning.

## Part 1

We are ${{ params.part1.num1 }}$% confident that the average waiting time of these ${{ params.part1.num2 }}$ emergency room patients is between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

We are ${{ params.part2.num1 }}$% confident that the average waiting time of all patients at this hospital's emergency room is between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

${{ params.part3.num1 }}$% of random samples have a sample mean between ${{ params.ci_lower }}$ and ${{ params.ci_higher }}$ minutes.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

A ${{ params.part4.num1 }}$% confidence interval would be narrower than the ${{ params.part4.num2 }}$% confidence interval since we need to be more sure of our estimate.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Part 5

The margin of error is ${{ params.part5.num1 }}$ and the sample mean is ${{ params.part5.num2 }}$.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Part 6

In order to decrease the margin of error of a ${{ params.part6.num1 }}$% confidence interval to half of what it is now, we would need to double the sample size. (Hint: the margin of error for a mean scales in the same way with sample size as the margin of error for a proportion.)

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)