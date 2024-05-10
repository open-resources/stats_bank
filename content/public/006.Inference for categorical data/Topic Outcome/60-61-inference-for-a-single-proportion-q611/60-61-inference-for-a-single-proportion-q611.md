---
title: National Health Plan, Part I
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.5
- 6.1.1.7
- 6.1.1.8
- 6.1.1.18
- 6.1.1.20
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
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $SE=$
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: true
    label: $Z=$
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: true
    label: p-value=
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
    params_vars_title: National Health Plan, Part I
    params_vars_sample_size: 613
    params_vars_sample_proportion: 59
    params_part1_ans1_value: '$H_0: p = 0.59$, $H_A: p ≠ 0.5$'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: '$H_0: p = 0.59$, $H_A: p = 0.5$'
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: '$H_0: p ≤ 0.5$, $H_A: p > 0.5$'
    params_part1_ans3_feedback: Correct!
    params_part1_ans4_value: '$H_0: p ≠ 0.5$, $H_A: p = 0.5$'
    params_part1_ans4_feedback: Try again please!
    params_part2_ans1_value: Since this is a random sample, independence is satisfied.
      The success-failure condition is also satisfied.
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: Since this is a random sample, independence is satisfied.
      The success-failure condition is not satisfied.
    params_part2_ans2_feedback: Try again please!
    params_part6_ans1_value: Since the p-value is less than 0.05, we reject $H_0$.
      We have strong evidence that the support is different from 0.5, and since the
      data provide a point estimate above 0.5, we have strong evidence to support
      this claim by the TV pundit.
    params_part6_ans1_feedback: Correct!
    params_part6_ans2_value: Since the p-value is greater than or equal to 0.05, we
      fail to reject $H_0$. We do not have strong evidence that the support is different
      from 0.5, and since the data provide a point estimate above 0.5, we do not have
      strong evidence to support this claim by the TV pundit.
    params_part6_ans2_feedback: Try again please!
    params_part7_ans1_value: Yes. Since 59% of Independents support the plan, the
      confidence interval is likely to include 0.5 as well, showing a balanced opinion
      among Independents.
    params_part7_ans1_feedback: Try again please!
    params_part7_ans2_value: Maybe. It's difficult to determine without knowing the
      sample size and margin of error used in the poll.
    params_part7_ans2_feedback: Try again please!
    params_part7_ans3_value: No. Generally, we expect a hypothesis test and a confidence
      interval to align, so we would expect the confidence interval to show a range
      of plausible values entirely above 0.5. However, if the confidence level is
      misaligned (e.g., a 99% confidence level and a α = 0.05 significance level),
      then this is no longer generally true.
    params_part7_ans3_feedback: Correct!
    params_part7_ans4_value: No. The percentage of Independents supporting the plan
      is too low to have any impact on the confidence interval.
    params_part7_ans4_feedback: Try again please!
---
# {{ params_vars_title }}
A Kaiser Family Foundation poll for US adults in 2019 found that 79% of Democrats, {{ params.vars.sample_proportion }}% of Independents, and 24% of Republicans supported a generic "National Health Plan". There were 347 Democrats, 298 Republicans, and {{ params.vars.sample_size }} Independents surveyed. A political pundit on TV claims that a majority of Independents support a National Health Plan. Do these data provide strong evidence to support this type of statement?

## Part 1: (a)

Formulate the null and alternative hypothesis.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Part 1: (b)

Does the success-failure condition hold for the given sample size and proportion?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}

## Part 1: (c)

Compute the standard error for the one-proportion hypothesis test.

### Answer Section

Please enter in a numeric value.

## Part 1: (d)

Calculate the test statistic.

### Answer Section

Please enter in a numeric value.

## Part 1: (e)

Determine the p-value from the calculated test statistic.

### Answer Section

Please enter in a numeric value.

## Part 1: (f)

Based on the p-value and a significance level of 0.05, state whether you will reject or fail to reject the null hypothesis and explain the conclusion.

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

## Part 2

Would you expect a confidence interval for the proportion of Independents who oppose the public option plan to include 0.5? Yes or No?

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}
- {{ params_part7_ans3_value }}
- {{ params_part7_ans4_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)