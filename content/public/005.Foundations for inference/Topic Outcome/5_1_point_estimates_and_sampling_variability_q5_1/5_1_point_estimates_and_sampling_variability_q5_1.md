---
title: Identify the parameter, Part I
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 5.1.1.0
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
myst:
  substitutions:
    params:
      vars:
        title: Identify the parameter, Part I
        question: In a sample of one hundred recent college graduates, it is found
          that $ 88 $ percent expect to get a job within one year of their graduation
          date.
        answer_panel_feedback: Proportion. Each student reports whether or not s/he
          expects to get a job, so this is a categorical variable and we use a proportion.
      part1:
        ans1:
          value: Proportion
          feedback: Great! You got it.
        ans2:
          value: Mean
          feedback: Try again please!
---
# {{ params.vars.title }}
Identify whether the parameter of interest is a mean or a proportion.
It may be helpful to examine whether individual responses are numerical or categorical.

## Part 1

{{params.vars.question}}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)