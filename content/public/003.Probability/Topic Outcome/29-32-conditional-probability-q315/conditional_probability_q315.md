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
    params:
      vars:
        title: Global Warming
      num1: 0.11
      num2: 0.19
      num3: 0.02
      num4: 0.32
      num5: 0.07
      num6: 0.07
      num7: 0.01
      num8: 0.15
      num9: 0.25
      num10: 0.06
      num11: 0.02
      num12: 0.33
      num13: 0.18
      num14: 0.01
      num15: 0.01
      num16: 0.2
      num17: 0.61
      num18: 0.33
      num19: 0.06
      num20: 1.0
      n20: 1310
      part1:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
      part5:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
A Pew Research poll asked {{ params.n20 }} Americans “From what you’ve read and heard, is there solid evidence that the average temperature on earth has been getting warmer over the past few decades, or not?”.
The table below shows the distribution of responses by party and ideology, where the counts have been replaced with relative frequencies.

<!-- |                         | Earth is warming | Not warming | Don't know refuse | Total |
|-------------------------|------------------|-------------|-------------------|-------|
| Conservative Republican | 0.11             | 0.20        | 0.02              | 0.33  |
| Mod/Lib Republican      | 0.06             | 0.06        | 0.01              | 0.13  |
| Mod/Cons Democrat       | 0.25             | 0.07        | 0.02              | 0.34  |
| Liberal Democrat        | 0.18             | 0.01        | 0.01              | 0.20  |
| Total                   | 0.60             | 0.34        | 0.06              | 1.00  | -->

| | Earth is warming | Not warming | Don't know refuse | Total |
|-------------------------|:----------------:|:-----------:|:-----------------:|:------:|
| Conservative Republican | {{ params.num1 }} | {{ params.num2 }} | {{ params.num3 }} | {{ params.num4 }} |
| Mod/Lib Republican | {{ params.num5 }} | {{ params.num6 }} | {{ params.num7 }} | {{ params.num8 }} |
| Mod/Cons Democrat | {{ params.num9 }} | {{ params.num10 }} | {{ params.num11 }} | {{ params.num12 }} |
| Liberal Democrat | {{ params.num13 }} | {{ params.num14 }} | {{ params.num15 }} | {{ params.num16 }} |
| Total | {{ params.num17 }} | {{ params.num18 }} | {{ params.num19 }} | {{ params.num20 }} |

## Part 1

Are believing that the earth is warming and being a liberal Democrat mutually exclusive?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

What is the probability that a randomly chosen respondent believes the earth is warming or is a liberal Democrat?

## Part 3

What is the probability that a randomly chosen respondent believes the earth is warming given that he is a liberal Democrat?

## Part 4

What is the probability that a randomly chosen respondent believes the earth is warming given that he is a conservative Republican?

## Part 5

Does it appear that whether or not a respondent believes the earth is warming is independent of their party and ideology?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Part 6

What is the probability that a randomly chosen respondent is a moderate/liberal Republican given that he does not believe that the earth is warming?

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)