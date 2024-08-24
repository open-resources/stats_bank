---
title: Relaxing after work
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.3
- 5.1.1.12
- 5.1.1.13
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Relaxing after work
      part2:
        num1: 1238
        moe_comparison: larger
        ans1:
          value: The confidence level of the new interval is the same as the previous
            interval.
          feedback: Try again please! Recall that the width of the confidence interval
            increases as the confidence level increases.
        ans2:
          value: The confidence level of the new interval must be lower than that
            of the previous interval.
          feedback: Try again please! Recall that the width of the confidence interval
            increases as the confidence level increases.
        ans3:
          value: The confidence level of the new interval must be higher than that
            of the previous interval.
          feedback: Correct!
        ans4:
          value: The confidence level cannot be determined from the information given.
          feedback: Try again please! Recall that the width of the confidence interval
            increases as the confidence level increases.
      part3:
        num1: 663
        num2: 95
        ans1:
          value: The new margin of error will be larger, as a smaller sample size
            always leads to a larger margin of error.
          feedback: Correct!
        ans2:
          value: The new margin of error will be the same, regardless of changes in
            the sample size.
          feedback: Try again please! Recall that as the sample size increases, the
            standard error decreases, which will decrease the margin of error.
        ans3:
          value: The new margin of error will be smaller, as a smaller sample size
            leads to a smaller margin of error.
          feedback: Try again please! Recall that as the sample size increases, the
            standard error decreases, which will decrease the margin of error.
        ans4:
          value: The new margin of error cannot be determined without knowing the
            actual values of the confidence intervals.
          feedback: Try again please! Recall that as the sample size increases, the
            standard error decreases, which will decrease the margin of error.
      description:
        num1: 1238
        num2: 95
        num3: 1.37
        num4: 2.0
      part1:
        ans1:
          value: The mean number of hours spent relaxing is exactly 1.65 hours.
          feedback: Try again please!
        ans2:
          value: The mean number of hours spent relaxing is not accurately estimated
            with this data.
          feedback: Try again please!
        ans3:
          value: We are 95% confident that the average time spent relaxing by Americans
            falls between 1.37 and 2.0 hours.
          feedback: Correct!
        ans4:
          value: This interval represents the minimum and maximum number of hours
            Americans spend relaxing.
          feedback: Try again please!
---
# {{ params.vars.title }}
The General Social Survey asked the question: "After an average work day, about how many hours do you have to relax or pursue activities that you enjoy?" to a random sample of ${{ params.description.num1 }}$ Americans.

A ${{ params.description.num2 }}$% confidence interval for the mean number of hours spent relaxing or pursuing activities they enjoy was (${{ params.description.num3 }}$, ${{ params.description.num4 }}$).

## Part 1

Interpret this interval in context of the data.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Suppose another set of researchers reported a confidence interval with a {{ params.part2.moe_comparison }} margin of error based on the same sample of ${{ params.part2.num1 }}$ Americans. How does their confidence level compare to the confidence level of the interval stated above?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

Suppose next year a new survey asking the same question is conducted, and this time the sample size is ${{ params.part3.num1 }}$. Assuming that the population characteristics, with respect to how much time people spend relaxing after work, have not changed much within a year. How will the margin of error of the ${{ params.part3.num2 }}$% confidence interval constructed based on data from the new survey compare to the margin of error of the interval stated above?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)