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
    params_vars_title: Minimum wage, Part I
    params_description_num1: 974
    params_description_num2: 40
    params_part1_ans1_value: '$H_0: p < 0.5$, $H_a: p > 0.5$'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: '$H_0: p = 0.5$, $H_a: p \neq 0.5$'
    params_part1_ans2_feedback: Correct!
    params_part1_ans3_value: '$H_0: p = 0.4$, $H_a: p \neq 0.4$'
    params_part1_ans3_feedback: Try again please!
    params_part1_ans4_value: '$H_0: p > 0.5$, $H_a: p < 0.5$'
    params_part1_ans4_feedback: Try again please!
    params_part2_ans1_value: Independence
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: Success-failure condition
    params_part2_ans2_feedback: Correct!
    params_part3_ans1_value: p < 0.00001
    params_part3_ans1_feedback: Correct!
    params_part3_ans2_value: p > 0.05
    params_part3_ans2_feedback: Try again please!
    params_part3_ans3_value: p = 0
    params_part3_ans3_feedback: Try again please!
    params_part3_ans4_value: p = 0.4
    params_part3_ans4_feedback: Try again please!
    params_part4_ans1_value: Reject the null hypothesis
    params_part4_ans1_feedback: Correct!
    params_part4_ans2_value: Fail to reject the null hypothesis
    params_part4_ans2_feedback: Try again please!
    params_part4_ans3_value: Not enough information to make a decision
    params_part4_ans3_feedback: Try again please!
    params_part4_ans4_value: Conduct another survey
    params_part4_ans4_feedback: Try again please!
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Try again please!
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Correct!
---
# {{ params_vars_title }}
Do a majority of US adults believe raising the minimum wage will help the economy, or is there a majority who do not believe this?

A Rasmussen Reports survey of a random sample of ${{ params_description_num1 }}$ US adults found that ${{ params_description_num2 }}$% believe it will help the economy. Conduct an appropriate hypothesis test to help answer the research question. We will use a significance level of $\alpha = 0.05$.

## Part 1

Choose the appropriate hypotheses.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

Set up hypotheses. $H_0$: $p = 0.5$, $H_A$: $p \neq 0.5$.

## Part 2

Which of the following condition(s) are satisfied for conducting this hypothesis test?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

### pl-answer-panel

Check conditions: simple random sample gets us independence, and the success-failure conditions is satisfied since $0.5 \times {{ params_description_num1 }} $ for each group is at least 10.

## Part 3

What is the p-value?

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

### pl-answer-panel

Next, we calculate: $SE = \sqrt{0.5 (1 - 0.5) / {{ params_description_num1 }} } $. $Z = \frac{ {{ params_description_num2 }}/100 - 0.5}{SE}$, which has a one-tail area, the p-value is twice this one-tail area.

## Part 4

Based on the calculated p-value, what decision should you make regarding the null hypothesis?

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

### pl-answer-panel

Make a conclusion: Because the p-value is less than $\alpha = 0.05$, we reject the null hypothesis and conclude that the fraction of US adults who believe raising the minimum wage will help the economy is not 50%.

## Part 5

Based on the results of the hypothesis test, can we conclude that a majority of US adults believe that raising the minimum wage will help the economy?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

### pl-answer-panel

Because the observed value is less than 50% and we have rejected the null hypothesis, we can conclude that this belief is held by fewer than 50% of US adults.

(For reference, the survey also explores support for changing the minimum wage, which is a different
question than if it will help the economy.)

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)