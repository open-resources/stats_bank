---
title: Working backwards, Part I
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
  type: number-input
  pl-customizations:
    rtol: 1.0e-05
    weight: 1
    allow-blank: true
    label: $\hat{p}= $
part2:
  type: number-input
  pl-customizations:
    rtol: 1.0e-05
    weight: 1
    allow-blank: true
    label: $\hat{p}= $
myst:
  substitutions:
    params_vars_title: Working backwards, Part I
    params_description_num1: 0.5
    params_description_num2: 0.5
    params_description_num3: 91
    params_description_num4: 0.05
---
# {{ params_vars_title }}
You are given the following hypotheses:

$H_0$: p = ${{ params_description_num1 }}$

$H_A$: p $\neq {{ params_description_num2 }}$

We know the sample size is ${{ params_description_num3 }}$. For what sample proportion would the p-value be equal to ${{ params_description_num4 }}$? Assume that all conditions  necessary for inference are satisfied.

## Part 1

Use positive test statistic. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

If the p-value is ${{ params_description_num4 }}$, this means the test statistic would be either $Z = -1.96 or 1.96$.

We'll show the calculations for $Z = 1.96$.

Standard error: $SE = \sqrt{({{ params_description_num1 }}\* (1 - {{ params_description_num1 }}) )/ {{ params_description_num3 }}}$

Finally, set up the test statistic formula and solve
for $\hat{p}$:
$1.96 = \frac{\hat{p} - 0.3}{0.048} \to \hat{p} = {{ correct_answers.part1_ans }}$

## Part 2

Use negative test statistic. Please provide your answer to three decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Alternatively, if $Z = -1.96$ was used: $\hat{p} = {{ correct_answers.part2_ans }}$

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)