---
title: Minimum wage, Part I
topic: Foundations for inference
author: Camilla Ren
source: Open Intro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 5.1.1.10
- 5.1.1.16
- 5.1.1.17
- 5.1.1.18
- 5.1.1.20
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
  type: checkbox
  pl-customizations:
    weight: 1
    fixed-order: true
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: checkbox
  pl-customizations:
    weight: 1
    fixed-order: true
myst:
  substitutions:
    params:
      vars:
        title: Minimum wage, Part I
      description:
        num1: 926
        num2: 42
      part1:
        ans1:
          value: '$H_0: p < 0.5$, $H_a: p > 0.5$'
          feedback: Try again please!
        ans2:
          value: '$H_0: p = 0.5$, $H_a: p \neq 0.5$'
          feedback: Correct!
        ans3:
          value: '$H_0: p = 0.42$, $H_a: p \neq 0.42$'
          feedback: Try again please!
        ans4:
          value: '$H_0: p > 0.5$, $H_a: p < 0.5$'
          feedback: Try again please!
      part2:
        ans1:
          value: Independence
          feedback: Correct!
        ans2:
          value: Success-failure condition
          feedback: Correct!
      part3:
        ans1:
          value: p < 0.00001
          feedback: Correct!
        ans2:
          value: p > 0.05
          feedback: Try again please!
        ans3:
          value: p = 0
          feedback: Try again please!
        ans4:
          value: p = 0.42
          feedback: Try again please!
      part4:
        ans1:
          value: Reject the null hypothesis
          feedback: Correct!
        ans2:
          value: Fail to reject the null hypothesis
          feedback: Try again please!
        ans3:
          value: Not enough information to make a decision
          feedback: Try again please!
        ans4:
          value: Conduct another survey
          feedback: Try again please!
      part5:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
Do a majority of US adults believe raising the minimum wage will help the economy, or is there a majority who do not believe this?

A Rasmussen Reports survey of a random sample of ${{ params.description.num1 }}$ US adults found that ${{ params.description.num2 }}$% believe it will help the economy. Conduct an appropriate hypothesis test to help answer the research question. We will use a significance level of $\alpha = 0.05$.

## Part 1

Choose the appropriate hypotheses.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Which of the following condition(s) are satisfied for conducting this hypothesis test?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

What is the p-value?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Based on the calculated p-value, what decision should you make regarding the null hypothesis?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

Based on the results of the hypothesis test, can we conclude that a majority of US adults believe that raising the minimum wage will help the economy?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)