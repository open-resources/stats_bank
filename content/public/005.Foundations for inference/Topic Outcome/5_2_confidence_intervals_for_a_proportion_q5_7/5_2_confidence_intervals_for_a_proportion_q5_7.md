---
title: Chronic illness, Part I
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.8
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
myst:
  substitutions:
    params:
      vars:
        title: Chronic illness, Part I
      description:
        num1: 2004
        num2: 1.2
        num3: 41
      part1:
        ans1:
          value: '[36.6 %, 46.4 %]'
          feedback: 'Try again! Recall that the general formula is $point~estimate
            \pm z^{\star}$ × SE. First, identify the three different values. The point
            estimate is 41%,$z^{\star} = 1.96$ for a 95% confidence level, and SE
            = 1.2%.Then, plug the values into the formula: 41% $\pm 1.96$ × 1.2%'
        ans2:
          value: '[38.6 %, 46.4 %]'
          feedback: 'Try again! Recall that the general formula is $point~estimate
            \pm z^{\star}$ × SE. First, identify the three different values. The point
            estimate is 41%,$z^{\star} = 1.96$ for a 95% confidence level, and SE
            = 1.2%.Then, plug the values into the formula: 41% $\pm 1.96$ × 1.2%'
        ans3:
          value: '[36.6 %, 43.4 %]'
          feedback: 'Try again! Recall that the general formula is $point~estimate
            \pm z^{\star}$ × SE. First, identify the three different values. The point
            estimate is 41%,$z^{\star} = 1.96$ for a 95% confidence level, and SE
            = 1.2%.Then, plug the values into the formula: 41% $\pm 1.96$ × 1.2%'
        ans4:
          value: '[38.6 %, 43.4 %]'
          feedback: Correct!
      part2:
        ans1:
          value: There is a 95% probability that between a and b of U.S. adults live
            with one or more chronic conditions.
          feedback: Try again please!
        ans2:
          value: The Pew Research Foundation is 95% confident that their sample proportion
            is between a and b.
          feedback: Try again please!
        ans3:
          value: 95% of all samples taken will result in an estimate between a and
            b.
          feedback: Try again please!
        ans4:
          value: We can be 95% confident that the true population proportion of U.S.
            adults living with one or more chronic conditions falls between a and
            b.
          feedback: Correct!
---
# {{ params.vars.title }}
In ${{ params.description.num1 }}$, the Pew Research Foundation reported that "${{ params.description.num3 }}$% of U.S. adults report that they live with one or more chronic conditions".

However, this value was based on a sample, so it may not be a perfect estimate for the population parameter of interest on its own.

The study reported a standard error of about ${{ params.description.num2 }}$%, and a normal model may reasonably be used in this setting.

## Part 1

Choose the appropriate 95% confidence interval for the proportion of U.S. adults who live with one or more chronic conditions.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Interpret the confidence interval in the context of the study.

Note: a and b is the correct 95% confidence interval \[a, b\] computed in part (1).

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)