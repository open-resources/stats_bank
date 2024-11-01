---
title: Swing voters
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
- 3.1.1.2
- 3.1.1.3
- 3.1.1.4
- 3.1.1.5
- 3.1.1.9
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
  type: number-input
  pl-customizations:
    rtol: 0.0001
    weight: 1
    allow-blank: true
    label: $p= $
    suffix: '%'
part4:
  type: number-input
  pl-customizations:
    rtol: 0.0001
    weight: 1
    allow-blank: true
    label: $p= $
    suffix: '%'
part5:
  type: number-input
  pl-customizations:
    rtol: 0.0001
    weight: 1
    allow-blank: true
    label: $p= $
    suffix: '%'
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Swing voters
      description:
        num1: 2217
        num2: 0.42
        num3: 0.27
        num4: 0.16
        num5: 0.26
        num6: 0.1134
        num22: 42.0
        num33: 27.0
        num44: 16.0
        num55: 26.0
        num66: 11.34
      part1:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct! There are voters who are both independent and swing voters.
      part2:
        ans1:
          value: $A$ = 26.0%, $B$ = 16.0%, $C$ = 11.0%
          feedback: Correct!
        ans2:
          value: $A$ = 26.0%, $B$ = 11.0%, $C$ = 16.0%
          feedback: Try again please!
        ans3:
          value: $A$ = 16.0%, $B$ = 26.0%, $C$ = 11.0%
          feedback: Try again please!
        ans4:
          value: $A$ = 16.0%, $B$ = 11.0%, $C$ = 26.0%
          feedback: Try again please!
        ans5:
          value: $A$ = 11.0%, $B$ = 26.0%, $C$ = 16.0%
          feedback: Try again please!
        ans6:
          value: $A$ = 11.0%, $B$ = 16.0%, $C$ = 26.0%
          feedback: Try again please!
      part6:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
A Pew Research survey asked {{ params.description.num1 }} randomly sampled registered voters their political affiliation (Republican, Democrat, or Independent) and whether or not they identify as swing voters. {{ params.description.num22 }}$\%$ of respondents identified as Independent, {{ params.description.num33 }}$\%$ identified as swing voters, and {{ params.description.num44 }}$\%$ identified as both.

## Part 1

Are being Independent and being a swing voter disjoint, i.e. mutually exclusive?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

Select the values that make the Venn diagram below correctly summarize the variables and their associated probabilities.

<pl-drawing width="320" height="200" hide-answer-panel="false">
    <pl-drawing-initial>
        <pl-text x1="50" y1="10" label="Independent" latex="False"></pl-text>
        <pl-circle x1="100" y1="100" radius="70" color="#95A5A6" stroke-width="3" opacity="0.5"></pl-circle>
        <pl-text x1="150" y1="170" label="Swing" latex="False"></pl-text>
        <pl-circle x1="180" y1="100" radius="60" color="#D0D3D4" opacity="0.5"></pl-circle>
        <pl-text x1="80" y1="90" label="A"></pl-text>
        <pl-text x1="140" y1="90" label="B"></pl-text>
        <pl-text x1="180" y1="90" label="C"></pl-text>
    </pl-drawing-initial>
</pl-drawing>

### Answer Section

File upload box will be shown here.

## Part 3

What percent of voters are Independent but not swing voters?

### Answer Section

Please enter a numeric value in percentage.

## Part 4

What percent of voters are Independent or swing voters?

### Answer Section

Please enter a numeric value in percentage.

## Part 5

What percent of voters are neither Independent nor swing voters?

### Answer Section

Please enter a numeric value in percentage.

## Part 6

Is the event that someone is a swing voter independent of the event that someone is a political Independent?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)