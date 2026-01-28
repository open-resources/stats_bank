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
    params:
      vars:
        title: National Health Plan, Part I
        sample_size: 542
        sample_proportion: 50
      part1:
        ans1:
          value: '$H_0: p = 0.5$, $H_A: p ≠ 0.5$'
          feedback: Try again please!
        ans2:
          value: '$H_0: p = 0.5$, $H_A: p = 0.5$'
          feedback: Try again please!
        ans3:
          value: '$H_0: p ≤ 0.5$, $H_A: p > 0.5$'
          feedback: Correct!
        ans4:
          value: '$H_0: p ≠ 0.5$, $H_A: p = 0.5$'
          feedback: Try again please!
      part2:
        ans1:
          value: Since this is a random sample, independence is satisfied. The success-failure
            condition is also satisfied.
          feedback: Correct!
        ans2:
          value: Since this is a random sample, independence is satisfied. The success-failure
            condition is not satisfied.
          feedback: Try again please!
      part6:
        ans1:
          value: Since the p-value is less than 0.05, we reject $H_0$. We have strong
            evidence that the support is different from 0.5, and since the data provide
            a point estimate above 0.5, we have strong evidence to support this claim
            by the TV pundit.
          feedback: Try again please!
        ans2:
          value: Since the p-value is greater than or equal to 0.05, we fail to reject
            $H_0$. We do not have strong evidence that the support is different from
            0.5, and since the data provide a point estimate above 0.5, we do not
            have strong evidence to support this claim by the TV pundit.
          feedback: Correct!
      part7:
        ans1:
          value: No. Since 50% of Independents support the plan, the confidence interval
            is unlikely to include 0.5, indicating an unbalanced opinion among Independents.
          feedback: Try again please!
        ans2:
          value: Maybe. It's difficult to determine without knowing the sample size
            and margin of error used in the poll.
          feedback: Try again please!
        ans3:
          value: Yes, you would expect the value to lie within a 95% confidence interval
            since the confidence interval and the hypothesis test should generally
            align.
          feedback: Correct!
        ans4:
          value: Yes. The percentage of Independents supporting the plan is sufficiently
            high to have a significant impact on the confidence interval.
          feedback: Try again please!
---
# {{ params.vars.title }}
A Kaiser Family Foundation poll for US adults in 2019 found that 79% of Democrats, {{ params.vars.sample_proportion }}% of Independents, and 24% of Republicans supported a generic "National Health Plan". There were 347 Democrats, 298 Republicans, and {{ params.vars.sample_size }} Independents surveyed. A political pundit on TV claims that a majority of Independents support a National Health Plan. Do these data provide strong evidence to support this type of statement?

## Part 1: (a)

Formulate the null and alternative hypothesis.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 1: (b)

Does the success-failure condition hold for the given sample size and proportion?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

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

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Part 2

Would you expect a confidence interval for the proportion of Independents who oppose the public option plan to include 0.5? Yes or No?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)