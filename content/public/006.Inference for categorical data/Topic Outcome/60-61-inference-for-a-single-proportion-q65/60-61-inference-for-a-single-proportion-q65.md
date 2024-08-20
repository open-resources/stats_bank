---
title: Gender equality
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.3
- 6.1.1.5
- 6.1.1.6
- 6.1.1.7
- 6.1.1.8
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
  type: dropdown
  pl-customizations:
    weight: 1
part2:
  type: dropdown
  pl-customizations:
    weight: 1
part3:
  type: dropdown
  pl-customizations:
    weight: 1
part4:
  type: dropdown
  pl-customizations:
    weight: 1
part5:
  type: dropdown
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Gender equality
        sample_size: 1923
        proportion: 75.0
        margin_of_error: !!python/object/apply:numpy.core.multiarray.scalar
        - &id001 !!python/object/apply:numpy.dtype
          args:
          - f8
          - false
          - true
          state: !!python/tuple
          - 3
          - <
          - null
          - null
          - null
          - -1
          - -1
          - 0
        - !!binary |
          CtejcD0K/z8=
        lower_bound: !!python/object/apply:numpy.core.multiarray.scalar
        - *id001
        - !!binary |
          pHA9CtdDUkA=
        upper_bound: !!python/object/apply:numpy.core.multiarray.scalar
        - *id001
        - !!binary |
          XI/C9Sg8U0A=
        margin_of_error_part4: !!python/object/apply:numpy.core.multiarray.scalar
        - *id001
        - !!binary |
          YOXQItv57j8=
        selected_option1: If the sample size were increased from 1559 Americans to
          5000 Americans while keeping the confidence level and margin of error unchanged,
          the width of the confidence intervals would decrease. This would lead to
          a higher percentage of intervals that include the true population proportion
          in comparison to the initial scenario with 1559 Americans.
        selected_option2: The margin of error is independent of the variability in
          the responses from the sample population; it only depends on the sample
          size and confidence level.
      part1:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
      part2:
        ans1:
          value: 'False'
        ans2:
          value: 'True'
      part3:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
      part4:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
      part5:
        ans1:
          value: 'True'
        ans2:
          value: 'False'
---
# {{ params.vars.title }}
The General Social Survey asked a random sample of {{ params.vars.sample_size }} Americans the following question: "On the whole, do you think it should or should not be the government's responsibility to promote equality between men and women?" {{ params.vars.proportion }}% of the respondents said it "should be". At a 95% confidence level, this sample has {{ params.vars.margin_of_error }}% margin of error. Based on this information, determine if the following statements are true or false.

## Part 1

We are 95% confident that between {{ params.vars.lower_bound }}% and {{ params.vars.upper_bound }}% of Americans in this sample think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

We are 95% confident that between {{ params.vars.lower_bound }}% and {{ params.vars.upper_bound }}% of all Americans think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

{{ params.vars.selected_option1 }}

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

{{ params.vars.selected_option2 }}

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Part 5

Based on this confidence interval, there is sufficient evidence to conclude that a majority of Americans think it's the government's responsibility to promote equality between men and women.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)