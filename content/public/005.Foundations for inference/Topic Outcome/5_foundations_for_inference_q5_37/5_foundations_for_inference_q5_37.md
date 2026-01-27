---
title: Gender pay gap in medicine
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.2
- 5.1.1.10
- 5.1.1.15
- 5.1.1.16
- 5.1.1.20
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
  type: checkbox
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
        title: Gender pay gap in medicine
      part2:
        num1: 20
        num2: 22
        num3: 22
        ans1:
          value: Independence
          feedback: Correct!
        ans2:
          value: Success-failure condition
          feedback: Correct!
      description:
        num1: 22
      part1:
        ans1:
          value: 'Null hypothesis: $p > 0.5$. Alternative hypothesis: $p < 0.5$.'
          feedback: Try again please!
        ans2:
          value: 'Null hypothesis: $p < 0.5$. Alternative hypothesis: $p > 0.5$.'
          feedback: Try again please!
        ans3:
          value: 'Null hypothesis: $p \neq 0.5$. Alternative hypothesis: $p = 0.5$.'
          feedback: Try again please!
        ans4:
          value: 'Null hypothesis: $p = 0.5$. Alternative hypothesis: $p \neq 0.5$.'
          feedback: Correct!
      part3:
        ans1:
          value: '0.5'
          feedback: Try again please!
        ans2:
          value: '0.0001'
          feedback: Try again please!
        ans3:
          value: '0'
          feedback: Try again please!
        ans4:
          value: '0.909'
          feedback: Correct!
      part4:
        ans1:
          value: '0.909'
          feedback: Try again please!
        ans2:
          value: '0.107'
          feedback: Try again please!
        ans3:
          value: '0.0001'
          feedback: Try again please!
        ans4:
          value: '3.82'
          feedback: Correct!
      part5:
        ans1:
          value: Fail to reject $H_0$, as the p-value is greater than α.
          feedback: Try again please!
        ans2:
          value: Reject $H_0$, as the p-value is greater than α.
          feedback: Try again please!
        ans3:
          value: Fail to reject $H_0$, as the p-value is smaller than α.
          feedback: Try again please!
        ans4:
          value: Reject $H_0$, as the p-value is smaller than α.
          feedback: Correct!
---
# {{ params.vars.title }}
A study examined the average pay for men and women entering the workforce as doctors for ${{ params.description.num1 }}$ different positions. Use α$=0.05$ for the following questions.

## Part 1

If each gender was equally paid, then we would expect about half of those positions to have men paid more than women and women would be paid more than men in the other half of positions. Choose appropriate hypotheses to test this scenario.

### Answer Section

- {{ params.part1.ans1.value}}
- {{ params.part1.ans2.value}}
- {{ params.part1.ans3.value}}
- {{ params.part1.ans4.value}}

## Part 2

Men were, on average, paid more in ${{ params.part2.num1 }}$ of those ${{ params.part2.num2 }}$ positions. Supposing these ${{ params.part2.num3 }}$ positions represent a simple random sample, complete a hypothesis test using your hypotheses from part 1. Check any conditions required for hypothesis testing.

### Answer Section

- {{ params.part2.ans1.value}}
- {{ params.part2.ans2.value}}

## Part 3

What is the value of the sample proportion ($\hat{p}$) calculated from the data provided?

### Answer Section

- {{ params.part3.ans1.value}}
- {{ params.part3.ans2.value}}
- {{ params.part3.ans3.value}}
- {{ params.part3.ans4.value}}

## Part 4

What is the calculated test statistic ($Z$) for the hypothesis test?

### Answer Section

- {{ params.part4.ans1.value}}
- {{ params.part4.ans2.value}}
- {{ params.part4.ans3.value}}
- {{ params.part4.ans4.value}}

## Part 5

Based on the p-value and significance level (α), what is the appropriate decision regarding the null hypothesis ($H_0$)?

### Answer Section

- {{ params.part5.ans1.value}}
- {{ params.part5.ans2.value}}
- {{ params.part5.ans3.value}}
- {{ params.part5.ans4.value}}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)