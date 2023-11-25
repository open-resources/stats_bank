---
title: Global Warming
topic: Probability
author: Sophie Varabioff
source: 3.15
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.1
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
  type: dropdown
  pl-customizations:
    blank: true
    weight: 1
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
part5:
  type: dropdown
  pl-customizations:
    blank: true
    weight: 1
part6:
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
myst:
  substitutions:
    params_vars_title: Global Warming
    params_num1: 0.1
    params_num2: 0.19
    params_num3: 0.01
    params_num4: 0.3
    params_num5: 0.05
    params_num6: 0.05
    params_num7: 0.01
    params_num8: 0.11
    params_num9: 0.26
    params_num10: 0.07
    params_num11: 0.03
    params_num12: 0.36
    params_num13: 0.2
    params_num14: 0.01
    params_num15: 0.01
    params_num16: 0.22
    params_num17: 0.61
    params_num18: 0.32
    params_num19: 0.06
    params_num20: 1.0
    params_n20: 1253
    params_part1_ans1_value: 'Yes'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: 'No'
    params_part1_ans2_feedback: Correct!
    params_part5_ans1_value: 'Yes'
    params_part5_ans1_feedback: Try again please!
    params_part5_ans2_value: 'No'
    params_part5_ans2_feedback: Correct!
---
# {{ params_vars_title }}
A Pew Research poll asked {{ params_n20 }} Americans “From what you’ve read and heard, is there solid evidence that the average temperature on earth has been getting warmer over the past few decades, or not?”.
The table below shows the distribution of responses by party and ideology, where the counts have been replaced with relative frequencies.

<!-- |                         | Earth is warming | Not warming | Don't know refuse | Total |
|-------------------------|------------------|-------------|-------------------|-------|
| Conservative Republican | 0.11             | 0.20        | 0.02              | 0.33  |
| Mod/Lib Republican      | 0.06             | 0.06        | 0.01              | 0.13  |
| Mod/Cons Democrat       | 0.25             | 0.07        | 0.02              | 0.34  |
| Liberal Democrat        | 0.18             | 0.01        | 0.01              | 0.20  |
| Total                   | 0.60             | 0.34        | 0.06              | 1.00  | -->

|                         | Earth is warming | Not warming | Don't know refuse | Total |
|-------------------------|:----------------:|:-----------:|:-----------------:|:------:|
| Conservative Republican | {{ params_num1 }} | {{ params_num2 }} | {{ params_num3 }} | {{ params_num4 }} |
| Mod/Lib Republican      | {{ params_num5 }} | {{ params_num6 }} | {{ params_num7 }} | {{ params_num8 }} |
| Mod/Cons Democrat       | {{ params_num9 }} | {{ params_num10 }} | {{ params_num11 }} | {{ params_num12 }} |
| Liberal Democrat        | {{ params_num13 }} | {{ params_num14 }} | {{ params_num15 }} | {{ params_num16 }} |
| Total                   | {{ params_num17 }} | {{ params_num18 }} | {{ params_num19 }} | {{ params_num20 }} |

## Part 1

Are believing that the earth is warming and being a liberal Democrat mutually exclusive?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}

### pl-answer-panel

No, ${{ params_num13 }}$ of respondents fall into this combination.

## Part 2

What is the probability that a randomly chosen respondent believes the earth is warming or is a liberal Democrat?

### pl-answer-panel

$p = {{ params_num17 }} + {{ params_num16 }} - {{ params_num13 }} = {{ correct_answers.part2_ans }}$

## Part 3

What is the probability that a randomly chosen respondent believes the earth is warming given that he is a liberal Democrat?

### pl-answer-panel

$p = {{ params_num13 }} / {{ params_num16 }} = {{ correct_answers.part3_ans }}$

## Part 4

What is the probability that a randomly chosen respondent believes the earth is warming given that he is a conservative Republican?

### pl-answer-panel

$p = {{ params_num1 }} / {{ params_num4 }} = {{ correct_answers.part4_ans }}$

## Part 5

Does it appear that whether or not a respondent believes the earth is warming is independent of their party and ideology?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

### pl-answer-panel

No, because otherwise the probabilities in parts 3 and 4 would be the same.

## Part 6

What is the probability that a randomly chosen respondent is a moderate/liberal Republican given that he does not believe that the earth is warming?

### pl-answer-panel

$p = {{ params_num6 }} / {{ params_num18 }} = {{ correct_answers.part6_ans }}$

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)