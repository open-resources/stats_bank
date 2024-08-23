---
title: Identify hypotheses, Part I
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 5.1.1.23
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
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Identify hypotheses, Part I
      part1:
        num1: 192
        ans1:
          value: '$ H_0: p < 0.5 $ A minority of students'' grades improved.'
          feedback: Try again please!
        ans2:
          value: '$H_0: p > 0.5$ A majority of students'' grades improved.'
          feedback: Try again please!
        ans3:
          value: '$H_0: p \neq 0.5$ Either a majority or minority of students'' grades
            improved.'
          feedback: Try again please!
        ans4:
          value: '$H_0: p = 0.5$ Neither a majority nor minority of students'' grades
            improved.'
          feedback: Correct!
      part2:
        num1: 24
        ans1:
          value: '$H_A: p = 0.5$ Neither a majority nor minority of students'' grades
            improved.'
          feedback: Try again please!
        ans2:
          value: '$H_A: p > 0.5$ A majority of students'' grades improved.'
          feedback: Try again please!
        ans3:
          value: '$H_A: p < 0.5$ A minority of students'' grades improved.'
          feedback: Try again please!
        ans4:
          value: '$H_A: p \neq 0.5$ Either a majority or a minority of students''
            grades improved.'
          feedback: Correct!
      part3:
        ans1:
          value: '$H_0: \mu \neq 24$ The average amount of company time each employee
            spends not working is different during March Madness.'
          feedback: Try again please!
        ans2:
          value: '$H_0: \mu > 24$ The average amount of company time each employee
            spends not working is more during March Madness.'
          feedback: Try again please!
        ans3:
          value: '$H_0: \mu < 24$ The average amount of company time each employee
            spends not working is less during March Madness.'
          feedback: Try again please!
        ans4:
          value: '$H_0: \mu = 24$ The average amount of company time each employee
            spends not working is the same during March Madness.'
          feedback: Correct!
      part4:
        ans1:
          value: '$H_A: \mu = 24$ The average amount of company time each employee
            spends not working is the same during March Madness.'
          feedback: Try again please!
        ans2:
          value: '$H_A: \mu > 24$ The average amount of company time each employee
            spends not working is more during March Madness.'
          feedback: Try again please!
        ans3:
          value: '$H_A: \mu < 24$ The average amount of company time each employee
            spends not working is less during March Madness.'
          feedback: Try again please!
        ans4:
          value: '$H_A: \mu \neq 24$ The average amount of company time each employee
            spends not working is different during March Madness.'
          feedback: Correct!
---
# {{ params.vars.title }}
Choose the appropriate null or alternative hypotheses for each of the following situations.

## Part 1

A tutoring company would like to understand if most students tend to improve their grades (or not) after they use their services.

They sample ${{ params.part1.num1 }}$ of the students who used their service in the past year and ask them if their grades have improved or declined from the previous year.

What would be the appropriate null hypothesis for this situation?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

A tutoring company would like to understand if most students tend to improve their grades (or not) after they use their services.

They sample ${{ params.part1.num1 }}$ of the students who used their service in the past year and ask them if their grades have improved or declined from the previous year.

What would be the appropriate alternative hypothesis for this situation?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

Employers at a firm are worried about the effect of March Madness, a basketball championship held each spring in the US, on employee productivity.

They estimate that on a regular business day employees spend on average ${{ params.part2.num1 }}$ minutes of company time checking personal email, making personal phone calls, etc.

They also collect data on how much company time employees spend on such non-business activities during March Madness.

They want to determine if these data provide convincing evidence that employee productivity changed during March Madness.

What would be the appropriate null hypothesis for this situation?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Employers at a firm are worried about the effect of March Madness, a basketball championship held each spring in the US, on employee productivity.

They estimate that on a regular business day employees spend on average ${{ params.part2.num1 }}$ minutes of company time checking personal email, making personal phone calls, etc.

They also collect data on how much company time employees spend on such non-business activities during March Madness.

They want to determine if these data provide convincing evidence that employee productivity changed during March Madness.

What would be the appropriate alternative hypothesis for this situation?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)