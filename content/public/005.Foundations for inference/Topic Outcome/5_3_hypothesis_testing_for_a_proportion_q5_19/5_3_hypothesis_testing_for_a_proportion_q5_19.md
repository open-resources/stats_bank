---
title: Cyberbullying rates
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.7
- 5.1.1.13
difficulty:
- undefined
randomization:
- 2
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
        title: Cyberbullying rates
      part2:
        num1: 72
        ans1:
          value: Yes, the claim is supported since 72% is greater than the lower limit
            of the confidence interval.
          feedback: Try again please!
        ans2:
          value: Yes, the claim is supported because the upper limit of the confidence
            interval is 67%, which is close to 72%.
          feedback: Try again please!
        ans3:
          value: No, the claim is not supported since 72% falls outside the confidence
            interval.
          feedback: Correct! The value of 72% lies outside of the interval, so we
            have convincing evidence that the researcher's conjecture is wrong.
        ans4:
          value: No, the claim is not supported because the confidence interval is
            too narrow.
          feedback: Try again please!
      part3:
        num1: 90
        ans1:
          value: Yes, the claim would be supported, as a 90% confidence interval would
            be wider than a 95% confidence interval.
          feedback: Try again please!
        ans2:
          value: Yes, the claim would be supported, as a 90% confidence interval is
            less strict than a 95% confidence interval.
          feedback: Try again please!
        ans3:
          value: No, the claim would not be supported, as a 90% confidence interval
            would be narrower than a 95% confidence interval.
          feedback: Correct! A 90% confidence interval will be narrower than a 95%
            confidence interval. Even without calculating the interval, we can tell
            that 72% would not fall in the interval, and we would reject the researcher's
            conjecture based on a 90% confidence level as well.
        ans4:
          value: It cannot be determined without calculating the 90% confidence interval.
          feedback: Try again please!
      description:
        num1: 56
        num2: 67
        num3: 95
      part1:
        ans1:
          value: No, the claim is not supported because the upper limit of the interval
            is above 60%, which is not a majority.
          feedback: Try again please!
        ans2:
          value: Yes, the claim is supported, but only because the interval is above
            56%, not necessarily indicating a majority.
          feedback: Try again please!
        ans3:
          value: Yes, the claim is supported since the entire interval lies above
            50%, indicating a majority.
          feedback: Correct! This claim is reasonable since the entire interval lies
            above 50%.
        ans4:
          value: No, the claim is not supported because the interval is wide, implying
            a high level of uncertainty.
          feedback: Try again please!
---
# {{ params.vars.title }}
Teens were surveyed about cyberbullying, and ${{ params.description.num1 }}$% to ${{ params.description.num2 }}$% reported experiencing cyberbullying (${{ params.description.num3 }}$% confidence interval).

Answer the following questions based on this interval.

## Part 1

A newspaper claims that a majority of teens have experienced cyberbullying.

Is this claim supported by the confidence interval? Choose an appropriate reason.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

A researcher conjectured that ${{ params.part2.num1 }}$% of teens have experienced cyberbullying.

Is this claim supported by the confidence interval? Choose an appropriate reason.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

Without actually calculating the interval, determine if the claim of the researcher from part 2 would be supported based on a ${{ params.part3.num1 }}$% confidence interval?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)