---
title: Browsing on the mobile device
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.4
- 6.1.1.5
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
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $Z =$
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: true
    label: 'p-value = '
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: 'Lower bound of 95% CI = '
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: 'Upper bound of 95% CI = '
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Browsing on the mobile device.
        chinese_proportion: 0.38
        sample_size: 1620
        sample_proportion: 39.0
        Z: 0.8292201830963418
        p_value: 0.4069798261993589
        lower_bound: 0.36624824061097633
        upper_bound: 0.4137517593890237
      part1:
        ans1:
          value: '$H_0: p = 0.39$, $H_A: p ≠ 0.38$'
          feedback: Try again please!
        ans2:
          value: '$H_0: p = 0.39$, $H_A: p = 0.38$'
          feedback: Try again please!
        ans3:
          value: '$H_0: p = 0.38$, $H_A: p ≠ 0.38$'
          feedback: Correct!
        ans4:
          value: '$H_0: p ≠ 0.38$, $H_A: p = 0.38$'
          feedback: Try again please!
      part4:
        ans1:
          value: As the p-value is less than 0.05, we reject $H_0$, then the data
            provide strong evidence that the proportion of Americans who only use
            their cell phones to access the internet is different than the Chinese
            proportion of 38%, and the data indicate that the proportion is lower
            in the US.
          feedback: Try again please!
        ans2:
          value: As the p-value is greater than or equal to 0.05, we fail to reject
            $H_0$, then the data does not provide strong evidence to show that the
            proportion of Americans who only use their cell phones to access the internet
            is different than the Chinese proportion of 38%.
          feedback: Correct!
      part7:
        ans1:
          value: We are 95% confident that approximately [Lower bound] to [Upper bound]
            of all Americans primarily use their cell phones to browse the internet.
          feedback: Correct!
        ans2:
          value: We are 90% confident that [Lower bound] to [Upper bound] of all Americans
            primarily use their cell phones to browse the internet, but this range
            could also be 10% to 30%.
          feedback: Try again please!
        ans3:
          value: We are 99% confident that [Lower bound] to [Upper bound] of all Americans
            always use their cell phones to browse the internet, with no variability.
          feedback: Try again please!
---
# {{ params.vars.title }}
A survey of {{ params.vars.sample_size }} American adults indicates that {{ params.vars.sample_proportion }}% of cell phone owners browse the internet exclusively on their phone rather than a computer or other device. According to an online article, a report from a mobile research company indicates that 38% of Chinese mobile web users only access the internet through their cell phones. Conduct a hypothesis test to determine if these data provide strong evidence that the proportion of Americans who only use their cell phones to access the internet is different than the Chinese proportion of 38%.

## Part 1: (a)

Formulate the null and alternative hypothesis.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 1: (b)

Calculate the test statistic (Z) for the hypothesis test using the provided information.

### Answer Section

Please enter in a numeric value.

## Part 1: (c)

Determine the p-value from the calculated test statistic.

### Answer Section

Please enter in a numeric value.

## Part 1: (d)

Based on the p-value and a significance level of 0.05, state whether you will reject or fail to reject the null hypothesis and explain the conclusion.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Part 2: (a)

Calculate the lower bound of a 95% confidence interval for the proportion of Americans who access the internet on their cell phones.

### Answer Section

Please enter in a numeric value in.

## Part 2: (b)

Calculate the upper bound a 95% confidence interval for the proportion of Americans who access the internet on their cell phones.

### Answer Section

Please enter in a numeric value in.

## Part 2: (c)

Interpret the interval in this context.

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)