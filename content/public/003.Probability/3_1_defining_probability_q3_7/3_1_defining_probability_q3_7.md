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
    params_vars_title: Swing voters
    params_description_num1: 2160
    params_description_num2: 0.41
    params_description_num3: 0.27
    params_description_num4: 0.13
    params_description_num5: 0.28
    params_description_num6: 0.1107
    params_description_num22: 41.0
    params_description_num33: 27.0
    params_description_num44: 13.0
    params_description_num55: 28.0
    params_description_num66: 11.07
    params_part1_ans1_value: 'Yes'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'No'
    params_part1_ans2_feedback: Correct! There are voters who are both independent
      and swing voters.
    params_part2_ans1_value: $A$ = 28.0%, $B$ = 13.0%, $C$ = 14.0%
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: $A$ = 28.0%, $B$ = 14.0%, $C$ = 13.0%
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: $A$ = 13.0%, $B$ = 28.0%, $C$ = 14.0%
    params_part2_ans3_feedback: Try again please!
    params_part2_ans4_value: $A$ = 13.0%, $B$ = 14.0%, $C$ = 28.0%
    params_part2_ans4_feedback: Try again please!
    params_part2_ans5_value: $A$ = 14.0%, $B$ = 28.0%, $C$ = 13.0%
    params_part2_ans5_feedback: Try again please!
    params_part2_ans6_value: $A$ = 14.0%, $B$ = 13.0%, $C$ = 28.0%
    params_part2_ans6_feedback: Try again please!
    params_part6_ans1_value: 'Yes'
    params_part6_ans1_feedback: Try again please!
    params_part6_ans2_value: 'No'
    params_part6_ans2_feedback: Correct!
---
# {{ params_vars_title }}
A Pew Research survey asked {{ params_description_num1 }} randomly sampled registered voters their political affiliation (Republican, Democrat, or Independent) and whether or not they identify as swing voters. {{ params_description_num22 }}$\%$ of respondents identified as Independent, {{ params_description_num33 }}$\%$ identified as swing voters, and {{ params_description_num44 }}$\%$ identified as both.

## Part 1

Are being Independent and being a swing voter disjoint, i.e. mutually exclusive?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

No, there are voters who are both independent and swing voters.

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

### pl-answer-panel

A Venn diagram is shown for variables "Independent" and "Swing", where the two circles representing the variable are partially overlapping. The region of the "Independent" circle not overlapping the other circle is labeled with "24". The region of the "Swing" circle not overlapping the other circle is labeled with "12". The region where the two circles overlap is labeled with "11".

## Part 3

What percent of voters are Independent but not swing voters?

### Answer Section

Please enter a numeric value in percentage.

### pl-answer-panel

Each Independent voter is either a swing voter or not. Since ${{ params_description_num22 }}%$ of voters are Independents and ${{ params_description_num44 }}%$  are both Independent and swing voters, the other ${{ params_description_num55 }}%$ must not be swing voters.

## Part 4

What percent of voters are Independent or swing voters?

### Answer Section

Please enter a numeric value in percentage.

### pl-answer-panel

Using the general addition rule, P(Independent or swing) $=$ P(Independent) $+$ P(Swing) $-$ P(Independent and swing) $={{ correct_answers.part4_ans }}$

## Part 5

What percent of voters are neither Independent nor swing voters?

### Answer Section

Please enter a numeric value in percentage.

### pl-answer-panel

{{ correct_answers.part5_ans }}

## Part 6

Is the event that someone is a swing voter independent of the event that someone is a political Independent?

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

### pl-answer-panel

Part 6: P(Independent) $\times$ P(swing) = ${{ params_description_num2 }}\times{{ params_description_num3 }} = {{ params_description_num6 }}$, which does not equal P(Independent and swing) = {{ params_description_num4 }}, so the events are dependent

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)