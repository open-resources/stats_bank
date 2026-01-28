---
title: Hearts win
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.4
- 3.1.1.14
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
- CY
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\mu= $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\sigma= $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\mu= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\sigma= $
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Hearts win
      part3:
        num1: 5
      part4:
        num1: 5
      part5:
        num1: 5
        ans1:
          value: 'No'
          feedback: Incorrect! The expected net profit is positive, so on average
            you expect to earn money.
        ans2:
          value: 'Yes'
          feedback: Correct! The expected net profit is positive, so on average you
            expect to earn money.
      description:
        num1: 2
        num2: 2
        num3: 54
        num4: 2
        num5: 25
---
# {{ params.vars.title }}
<div class="mathjax_ignore">
In a new card game, you start with a well-shuffled full deck and draw {{ params.description.num1 }} cards without replacement. If you draw {{ params.description.num2 }} hearts, you win ${{ params.description.num3 }}. If you draw {{ params.description.num4 }} black cards, you win ${{ params.description.num5 }}. For any other draws, you win nothing.
</div>

## Part 1

Create a probability model for the amount you win at this game, and find the expected winnings.

### Answer Section

Please enter a numeric value in.

## Part 2

Also compute the standard deviation of this distribution.

### Answer Section

Please enter a numeric value in.

## Part 3

If the game costs ${{ params.part3.num1 }} to play, what would be the expected value of the net profit (or loss)?

### Answer Section

Please enter a numeric value in.

## Part 4

If the game costs ${{ params.part4.num1 }} to play, what would be the standard deviation of the net profit (or loss)? (hint: profit = winnings - cost)

### Answer Section

Please enter a numeric value in.

## Part 5

If the game costs ${{ params.part5.num1 }} to play, should you play this game?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)