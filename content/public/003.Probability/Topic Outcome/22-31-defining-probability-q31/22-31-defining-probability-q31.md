---
title: True or false
topic: Probability
author: Sophie Varabioff
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.2
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
- SV
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: True or false
        question1: If a fair coin is tossed many times and the last eight tosses are
          all heads, then the chance that the next toss will be heads is somewhat
          less than 50%.
        question1_ans: False. These are independent trials.
      part1:
        ans1:
          value: 'True'
          feedback: False. These are independent trials.
        ans2:
          value: 'False'
          feedback: Correct!
---
# {{ params.vars.title }}

## Part 1

{{params.vars.question1}}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)