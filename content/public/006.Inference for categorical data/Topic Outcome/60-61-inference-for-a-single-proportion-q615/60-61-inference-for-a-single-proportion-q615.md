---
title: National Health Plan, Part II
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.6
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
- AB
assets: null
part1:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: $n =$
myst:
  substitutions:
    params_vars_title: National Health Plan, Part II
    params_vars_p_hat: 0.7
    params_vars_p_hat_percent: 70.0
    params_vars_margin_of_error_percent: 1.0
    params_vars_z_score: 2.3263
    params_vars_confidence: 98
    params_vars_n: 11365
---
# {{ params_vars_title }}
A Kaiser Family Foundation poll for US adults in 2019 reported varying levels of support for a generic "National Health Plan" among different political affiliations. For Independents, it was found that approximately {{ params.vars.p_hat_percent }}% supported the plan.

There were various sample sizes for each group, but for this problem, we are focusing on the responses from the Independents.

## Part 1

If we wanted to estimate this number to within {{ params.vars.margin_of_error_percent }}% with {{ params_vars_confidence }}% confidence, what would be an appropriate sample size?

### Answer Section

Please enter in a numeric value.

### pl-answer-panel

is the smallest appropriate sample size. Because a sample proportion $(\hat{p} = {{ params.vars.p_hat }})$ is available, we use this value for the sample size calculations. The margin of error for a ${{ params_vars_confidence }}$% confidence interval is ${{ params.vars.z_score }} \times SE = {{ params.vars.z_score }} \times \sqrt{\frac{p(1-p)}{n}}$.

Using $\hat{p}$ in place of $p$, this becomes ${{ params.vars.z_score }} \times \sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$. We want this margin of error to be less than $0.01$. Thus,

${{ params.vars.z_score }} \times \sqrt{\frac{ {{ params.vars.p_hat }} \times (1 - {{ params.vars.p_hat }} )}{n}} \leq 0.01 \Leftrightarrow {{ params.vars.z_score }}^2 \times \frac{ {{ params.vars.p_hat }} \times (1 - {{ params.vars.p_hat }} )}{0.01^2} \leq n$.

From this, we get that $n$ must be at least ${{ params_vars_n }}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)