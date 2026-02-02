---
title: Four games, one winner
topic: Probability
author: Sophie Varabioff
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.1
- 3.1.1.11
- 3.1.1.15
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
        title: Four games, one winner
      description1: If the proportion of heads is larger than 0.2, you win $1.
      description2: If the proportion of heads is larger than 0.6, you win $1.
      planswer1: 10 tosses. Fewer tosses mean more variability in the sample fraction
        of heads, meaning there's a better chance of getting at least 0.2 heads.
      planswer2: 100 tosses. More flips means the observed proportion of heads would
        often be closer to the average, 0.50, and therefore also above 0.6.
      num1: 10
      num2: 100
      num3: 1
      part1:
        num1: 0.2
        ans1:
          value: '10'
          feedback: You got it!
        ans2:
          value: '100'
          feedback: Not quite!
      part2:
        num1: 0.6
        ans1:
          value: '10'
          feedback: Not quite!
        ans2:
          value: '100'
          feedback: You got it!
      part3:
        num1: 0.2
        num2: 0.8
        ans1:
          value: '10'
          feedback: Not quite!
        ans2:
          value: '100'
          feedback: You got it!
      part4:
        num1: 0.3
        ans1:
          value: '10'
          feedback: You got it!
        ans2:
          value: '100'
          feedback: Not quite!
---
# {{ params.vars.title }}
Below are four versions of the same game. Your archnemesis gets to pick the version of the game, and then you get to choose how many times to flip a coin: ${{ params.num1 }}$ times or ${{ params.num2 }}$ times. Identify how many coin flips you should choose for each version of the game. It costs ${{ params.num3 }} to play each game.

## Part 1

{{ params.description1 }}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

{{ params.description2 }}

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}

## Part 3

If the proportion of heads is between ${{ params.part3.num1 }}$ and ${{ params.part3.num2 }}$, you win ${{ params.num3 }}.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

If the proportion of heads is smaller than ${{ params.part4.num1 }}$, you win ${{ params.num3 }}.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)