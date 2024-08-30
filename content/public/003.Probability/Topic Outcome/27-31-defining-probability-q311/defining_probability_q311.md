---
title: Educational Attainment of Couples
topic: Probability
author: Sophie Varabioff
source: 3.11
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.2
- 3.1.1.4
- 3.1.1.5
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
  type: number-input
  pl-customizations:
    rtol: 0.01
    label: $p = $
    allow-blank: true
    weight: 1
    comparison: decdig
    digits: 2
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
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Educational Attainment of Couples
      male_9_less: '0.16'
      male_9_to_12: '0.10'
      male_HS: '0.14'
      male_some_college: '0.17'
      male_associates: '0.11'
      male_bachelors: '0.13'
      male_graduate_or_professional: '0.18'
      female_9_less: '0.18'
      female_9_to_12: '0.12'
      female_HS: '0.22'
      female_some_college: '0.13'
      female_associates: '0.19'
      female_bachelors: '0.03'
      female_graduate_or_professional: '0.12'
      part4:
        ans1:
          value: 'Yes'
          feedback: Not quite. Assumptions required in part 3 include assuming that
            the education level of the husband and wife are independent and that the
            decision to get married is unrelated to education level. The husband/wife
            independence assumption is probably not reasonable, because people often
            marry another person with a comparable level of education. We will leave
            it to you to think about whether the second assumption is reasonable.
        ans2:
          value: 'No'
          feedback: Great! You got it. Assumptions required in part 3 include assuming
            that the education level of the husband and wife are independent and that
            the decision to get married is unrelated to education level. The husband/wife
            independence assumption is probably not reasonable, because people often
            marry another person with a comparable level of education. We will leave
            it to you to think about whether the second assumption is reasonable.
---
# {{ params.vars.title }}
The table below shows the distribution of education level attained by US residents by gender based on data collected in the 2010 American Community Survey.

<!-- |                                 | Male | Female |
|---------------------------------|------|--------|
| Less than 9th grade             | 0.07 | 0.13   |
| 9th to 12th grade, no diploma   | 0.10 | 0.09   |
| HS graduate (or equivalent)     | 0.30 | 0.20   |
| Some college, no degree         | 0.22 | 0.24   |
| Associate’s degree              | 0.06 | 0.08   |
| Bachelor’s degree               | 0.16 | 0.17   |
| Graduate or professional degree | 0.09 | 0.09   |
| Total                           | 1.00 | 1.00   | -->

|                                 | Male | Female |
|---------------------------------|------|--------|
| Less than 9th grade             | {{ params.male_9_less }} | {{ params.female_9_less }}   |
| 9th to 12th grade, no diploma   | {{ params.male_9_to_12 }} | {{ params.female_9_to_12 }}   |
| HS graduate (or equivalent)     | {{ params.male_HS }} | {{ params.female_HS }}   |
| Some college, no degree         | {{ params.male_some_college }} | {{ params.female_some_college }}   |
| Associate’s degree              | {{ params.male_associates }} | {{ params.female_associates }}   |
| Bachelor’s degree               | {{ params.male_bachelors }} | {{ params.female_bachelors }}   |
| Graduate or professional degree | {{ params.male_graduate_or_professional }} | {{ params.female_graduate_or_professional }}   |
| Total                           | 1.00 | 1.00   |

<!-- The table below shows the distribution of education level attained by US residents by gender based on data collected in the ${{ params.description.num1 }}$ American Community Survey. centertabularl p{7cm} c c } &                                       & $\multicolumn{2}{c}{\textit{Gender}}$
 3-4&                                                   & Male  & Female
 2-4& Less than 9th grade                               & ${{ params.description.num2 }}$  & ${{ params.description.num3 }}$
 & 9th to 12th grade, no diploma                     & ${{ params.description.num4 }}$  & ${{ params.description.num5 }}$
 $\textit{Highest}$    & HS graduate (or equivalent)   & ${{ params.description.num6 }}$  & ${{ params.description.num7 }}$
 $\textit{education}$  & Some college, no degree       & ${{ params.description.num8 }}$  & ${{ params.description.num9 }}$
 $\textit{attained}$   & Associate's degree            & ${{ params.description.num10 }}$  & ${{ params.description.num11 }}$
 & Bachelor's degree                                 & ${{ params.description.num12 }}$  & ${{ params.description.num13 }}$
 & Graduate or professional degree                   & ${{ params.description.num14 }}$  & ${{ params.description.num15 }}$
 2-4& Total                                             & ${{ params.description.num16 }}$  & ${{ params.description.num17 }}$ tabularcenter -->

## Part 1

What is the probability that a randomly chosen man has at least a Bachelor’s degree?

### Answer Section

Please enter a numeric value between 0 and 1.

## Part 2

What is the probability that a randomly chosen woman has at least a Bachelor’s degree?

### Answer Section

Please enter a numeric value between 0 and 1.

## Part 3

What is the probability that a man and a woman getting married both have at least a Bachelor’s degree?
Note any assumptions you must make to answer this question.

### Answer Section

Please enter a numeric value between 0 and 1.

## Part 4

If you made an assumption in part 3, do you think it was reasonable?

### Answer Section

- {{ params.part4.ans1}}
- {{ params.part4.ans2}}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)