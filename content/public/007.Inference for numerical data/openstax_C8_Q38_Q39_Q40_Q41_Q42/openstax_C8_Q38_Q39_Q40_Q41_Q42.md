---
title: Emergency Room Wait Times
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 8.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.0
- 7.1.1.4
- 7.1.1.5
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
- GKF
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\bar{x}=$
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $s_x=$
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n=$
part4:
  type: matching
  pl-customizations:
    weight: 1
    blank: true
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{CI}=$
    allow-partial-credit: true
part7:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{Margin of Error}=$
part8:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Emergency Room Wait Times
      confidence_level: 90
      sample_size: 67
      mean: 1.5
      stdev: 1.3
      part4:
        option0:
          value: The true mean wait time for patients in an emergency room.
        option1:
          value: The number of hours a patient waits to be examined after being called
            back.
        statement1:
          value: $X$
          matches: The number of hours a patient waits in the emergency room before
            being called back to be examined.
        statement2:
          value: $\bar{X}$
          matches: The mean wait time of 67 patients in the emergency room.
      part5:
        ans1:
          value: Student t with n-1 degrees of freedom
          feedback: Good job!
        ans2:
          value: 'Student t with n degrees of freedom '
          feedback: Try again please!
        ans3:
          value: $\operatorname{N}\left(0, 1\right)$
          feedback: Try again please!
        ans4:
          value: $\operatorname{N}\left(1.5, 1.3\right)$
          feedback: Try again please!
      part8:
        ans1:
          value: We are 90% confident that the true mean wait time is between (lower_bound)
            and (upper_bound) hours.
          feedback: Good job!
        ans2:
          value: It indicates the exact value of the population parameter.
          feedback: Try again please!
        ans3:
          value: Confidence interval shows the range of values that the sample mean
            can take.
          feedback: Try again please!
        ans4:
          value: It represents the probability that the sample mean falls within the
            specified range.
          feedback: Try again please!
---
# {{ params.vars.title }}
A hospital is trying to cut down on emergency room wait times. It is interested in the amount of time patients must wait before being called back to be examined. An investigation committee randomly surveyed {{ params.sample_size }} patients. The sample mean was {{ params.mean }} hours with a sample standard deviation of {{ params.stdev }} hours.

## Part 1

Identify $\bar{x}$.

### Answer Section

Please enter a numeric value in.

## Part 2

Identify $s_x$.

### Answer Section

Please enter a numeric value in.

## Part 3

Identify the sample size.

### Answer Section

Please enter a numeric value in.

## Part 4

Match the random variables $X$ and $\bar{X}$ to their definitions.

### Answer Section

## Part 5

What distribution does the appropriate test statistic follow?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}

## Part 6

Calculate a {{ params.confidence_level }}% confidence interval.

### Answer Section

## Part 7

Calculate the margin of error for the confidence interval calculated in part 7.

### Answer Section

Please enter a numeric value in.

## Part 8

Explain in complete sentences what the confidence interval means.

### Answer Section

- {{ params.part8.ans1.value }}
- {{ params.part8.ans2.value }}
- {{ params.part8.ans3.value }}
- {{ params.part8.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)