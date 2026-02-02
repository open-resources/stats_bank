---
title: Vegetarian college students
topic: Inference for categorical data
author: Alejandro Builes
source: 6.1
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.0
- 6.1.1.1
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
    params:
      vars:
        title: Vegetarian college students
      sample_size: 95
      sample_size2: 92
      p: 11
      p_hat: 15
      college_students: 134
      college_students2: 268
      part1:
        ans1:
          value: True. This statement satisfies the success-failure condition.
          feedback: Correct!
        ans2:
          value: False. The distribution is not normal since it does not satisfy the
            success-failure condition.
          feedback: Incorrect!
      part2:
        ans1:
          value: False. The distribution is not right skewed because the success-failure
            condition is met.
          feedback: Correct.
        ans2:
          value: True. The distribution is right skewed because the success-failure
            condition is not met.
          feedback: Incorrect!
      part3:
        ans1:
          value: True. The difference between the sample proportion and the population
            proportion is not significantly large.
          feedback: Incorrect.
        ans2:
          value: False. The difference between the sample proportion and the population
            proportion is significantly large.
          feedback: Correct!
      part4:
        ans1:
          value: True. The sample is unusual as the proportion is significantly different
            from the population proportion.
          feedback: Correct!
        ans2:
          value: False. The sample is not unusual as the proportion is not significantly
            different from the population proportion.
          feedback: Incorrect.
      part5:
        ans1:
          value: 'True'
          feedback: Incorrect.
        ans2:
          value: False. Doubling the sample size decreases the standard error by a
            factor of $\frac{1}{\sqrt{2}}$, not by one-half.
---
# {{ params.vars.title }}
Suppose that ${{params.p}}$% of college students are vegetarians. Determine if the following statements are true or false with the correct reasoning.

## Part 1

The distribution of the sample proportions of vegetarians in random samples of size ${{params.sample_size}}$ is approximately normal since $n \geq 30$.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

The distribution of the sample proportions of vegetarian college students in random samples of size ${{params.sample_size2}}$ is right skewed.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

A random sample of ${{params.college_students}}$ college students where ${{params.p_hat}}$% are vegetarians would be considered unusual.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

A random sample of ${{params.college_students2}}$ college students where ${{params.p_hat}}$% are vegetarians would be considered unusual.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Part 5

The standard error would be reduced by one-half if we increased the sample size from ${{params.college_students}}$ to ${{params.college_students2}}$.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)