---
title: Burger Preferences
topic: Probability
author: Sophie Varabioff
source: 3.17
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.2
- 3.1.1.4
- 3.1.1.5
- 3.1.1.10
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
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
part5:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: false
    show-correct-answer: true
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Burger Preferences
      num1: 6
      num2: 5
      num3: 11
      num4: 173
      num5: 177
      num6: 350
      num7: 9
      num8: 14
      num9: 23
      num10: 26
      num11: 26
      num12: 52
      num13: 5
      num14: 2
      num15: 7
      num16: 25
      num17: 22
      num18: 47
      num19: 18
      num20: 4
      num21: 22
      num22: 262
      num23: 250
      num24: 512
      part1:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
A 2010 Survey asked {{ params.num24 }} Los Angeles residents, "What is the best hamburger place in Southern California? Five Guys Burgers? In-N-Out Burger? Fat Burger? Tommy's Hamburgers? Umami Burger? Or somewhere else?"

The distribution of responses by gender is shown below.

|                    | Male | Female | Total |
|--------------------|:------:|:--------:|:-------:|
| Five Guys          | {{ params.num1 }} | {{ params.num2 }} | {{ params.num3 }} |
| In-N-Out Burger    | {{ params.num4 }} | {{ params.num5 }} | {{ params.num6 }} |
| Fat Burger         | {{ params.num7 }} | {{ params.num8 }} | {{ params.num9 }} |
| Tommy's Hamburgers | {{ params.num10 }} | {{ params.num11 }} | {{ params.num12 }} |
| Umami Burger       | {{ params.num13 }} | {{ params.num14 }} | {{ params.num15 }} |
| Other              | {{ params.num16 }} | {{ params.num17 }} | {{ params.num18 }} |
| Not Sure           | {{ params.num19 }} | {{ params.num20 }} | {{ params.num21 }} |
| Total              | {{ params.num22 }} | {{ params.num23 }} | {{ params.num24 }} |

## Part 1

Are being female and liking Five Guys Burgers mutually exclusive?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

What is the probability that a randomly chosen male likes In-N-Out the best? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

## Part 3

What is the probability that a randomly chosen female likes In-N-Out the best? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

## Part 4

What is the probability that a man and a woman who are dating both like In-N-Out the best? Note any assumption you make. Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

## Part 5

What is the probability that a randomly chosen person likes Umami best or that person is female? Please enter a numeric value between 0 and 1, keeping two significant figures (e.g. 0.57).

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)