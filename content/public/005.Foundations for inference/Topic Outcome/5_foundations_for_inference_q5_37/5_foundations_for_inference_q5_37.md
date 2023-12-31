---
title: Gender pay gap in medicine
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.2
- 5.1.1.10
- 5.1.1.15
- 5.1.1.16
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
myst:
  substitutions:
    params_vars_title: Gender pay gap in medicine
    params_part2_num1: 19
    params_part2_num2: 20
    params_part2_num3: 20
    params_part2_ans1_value: Independence
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: Success-failure condition
    params_part2_ans2_feedback: Correct!
    params_description_num1: 20
    params_part1_ans1_value: 'Null hypothesis: $p > 0.5$. Alternative hypothesis:
      $p < 0.5$.'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'Null hypothesis: $p < 0.5$. Alternative hypothesis:
      $p > 0.5$.'
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: 'Null hypothesis: $p \neq 0.5$. Alternative hypothesis:
      $p = 0.5$.'
    params_part1_ans3_feedback: Try again please!
    params_part1_ans4_value: 'Null hypothesis: $p = 0.5$. Alternative hypothesis:
      $p \neq 0.5$.'
    params_part1_ans4_feedback: Correct!
    params_part3_ans1_value: '0.5'
    params_part3_ans1_feedback: Try again please!
    params_part3_ans2_value: '0.0001'
    params_part3_ans2_feedback: Try again please!
    params_part3_ans3_value: '0'
    params_part3_ans3_feedback: Try again please!
    params_part3_ans4_value: '0.95'
    params_part3_ans4_feedback: Correct!
    params_part4_ans1_value: '0.95'
    params_part4_ans1_feedback: Try again please!
    params_part4_ans2_value: '0.112'
    params_part4_ans2_feedback: Try again please!
    params_part4_ans3_value: '0.0001'
    params_part4_ans3_feedback: Try again please!
    params_part4_ans4_value: '4.02'
    params_part4_ans4_feedback: Correct!
    params_part5_ans1_value: Fail to reject $H_0$, as the p-value is greater than
      α.
    params_part5_ans1_feedback: Try again please!
    params_part5_ans2_value: Reject $H_0$, as the p-value is greater than α.
    params_part5_ans2_feedback: Try again please!
    params_part5_ans3_value: Fail to reject $H_0$, as the p-value is smaller than
      α.
    params_part5_ans3_feedback: Try again please!
    params_part5_ans4_value: Reject $H_0$, as the p-value is smaller than α.
    params_part5_ans4_feedback: Correct!
---
# {{ params_vars_title }}
A study examined the average pay for men and women entering the workforce as doctors for ${{ params_description_num1 }}$ different positions. Use α$=0.05$ for the following questions.

## Part 1

If each gender was equally paid, then we would expect about half of those positions to have men paid more than women and women would be paid more than men in the other half of positions. Choose appropriate hypotheses to test this scenario.

### Answer Section

- {{ params_part1_ans1_value}}
- {{ params_part1_ans2_value}}
- {{ params_part1_ans3_value}}
- {{ params_part1_ans4_value}}

### pl-answer-panel

In effect, we're checking whether men are paid more than women (or vice-versa), and we'd expect these outcomes with either chance under the null hypothesis:

$H_0: p = 0.5$

$H_A: p \neq 0.5$

We'll use $p$ to represent the fraction of cases where men are paid more than women

## Part 2

Men were, on average, paid more in ${{ params_part2_num1 }}$ of those ${{ params_part2_num2 }}$ positions. Supposing these ${{ params_part2_num3 }}$ positions represent a simple random sample, complete a hypothesis test using your hypotheses from part 1. Check any conditions required for hypothesis testing.

### Answer Section

- {{ params_part2_ans1_value}}
- {{ params_part2_ans2_value}}

### pl-answer-panel

There isn't a good way to check independence here since the jobs are not a simple random sample. However, independence doesn't seem unreasonable, since the individuals in each job are different from each other.

The success-failure condition is met since we check it using the null proportion: $p_0 n = (1 - p_0) n $ is greater than 10.

## Part 3

What is the value of the sample proportion ($\hat{p}$) calculated from the data provided?

### Answer Section

- {{ params_part3_ans1_value}}
- {{ params_part3_ans2_value}}
- {{ params_part3_ans3_value}}
- {{ params_part3_ans4_value}}

### pl-answer-panel

$\hat{p} = {{ params_part2_num1 }} / {{ params_part2_num2 }}$

## Part 4

What is the calculated test statistic ($Z$) for the hypothesis test?

### Answer Section

- {{ params_part4_ans1_value}}
- {{ params_part4_ans2_value}}
- {{ params_part4_ans3_value}}
- {{ params_part4_ans4_value}}

### pl-answer-panel

$SE = \sqrt{\frac{0.5 \times (1 - 0.5)}{{{ params_part2_num2 }}}}$

$Z = \frac{\hat{p}  - 0.5}{SE}$

## Part 5

Based on the p-value and significance level (α), what is the appropriate decision regarding the null hypothesis ($H_0$)?

### Answer Section

- {{ params_part5_ans1_value}}
- {{ params_part5_ans2_value}}
- {{ params_part5_ans3_value}}
- {{ params_part5_ans4_value}}

### pl-answer-panel

Because the p-value is smaller than $0.05$, we reject the notion that all these gender pay disparities are due to chance. Because we observe that men are paid more in a higher proportion of cases and we have rejected $H_0$, we can conclude that men are being paid higher amounts in ways not explainable by chance alone.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)