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
    params_vars_title: Educational Attainment of Couples
    params_male_9_less: '0.14'
    params_male_9_to_12: '0.24'
    params_male_HS: '0.10'
    params_male_some_college: '0.19'
    params_male_associates: '0.14'
    params_male_bachelors: '0.11'
    params_male_graduate_or_professional: '0.08'
    params_female_9_less: '0.05'
    params_female_9_to_12: '0.08'
    params_female_HS: '0.15'
    params_female_some_college: '0.28'
    params_female_associates: '0.14'
    params_female_bachelors: '0.08'
    params_female_graduate_or_professional: '0.22'
    params_part4_ans1_value: 'Yes'
    params_part4_ans1_feedback: Not quite. Assumptions required in part 3 include
      assuming that the education level of the husband and wife are independent and
      that the decision to get married is unrelated to education level. The husband/wife
      independence assumption is probably not reasonable, because people often marry
      another person with a comparable level of education. We will leave it to you
      to think about whether the second assumption is reasonable.
    params_part4_ans2_value: 'No'
    params_part4_ans2_feedback: Great! You got it. Assumptions required in part 3
      include assuming that the education level of the husband and wife are independent
      and that the decision to get married is unrelated to education level. The husband/wife
      independence assumption is probably not reasonable, because people often marry
      another person with a comparable level of education. We will leave it to you
      to think about whether the second assumption is reasonable.
---
# {{ params_vars_title }}
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

### pl-answer-panel

P = ${{ params.male_bachelors }} + ${{ params.male_graduate_or_professional }}$ = {{ correct_answers.part1_ans }}$

## Part 2

What is the probability that a randomly chosen woman has at least a Bachelor’s degree?

### Answer Section

Please enter a numeric value between 0 and 1.

### pl-answer-panel

P = ${{ params.female_bachelors }} + ${{ params.female_graduate_or_professional }}$ = {{ correct_answers.part2_ans }}$

## Part 3

What is the probability that a man and a woman getting married both have at least a Bachelor’s degree?
Note any assumptions you must make to answer this question.

### Answer Section

Please enter a numeric value between 0 and 1.

### pl-answer-panel

Assuming that the education level of the husband and wife are independent: $P = {{ correct_answers.part1_ans }} \times {{ correct_answers.part2_ans }} = {{ correct_answers.part3_ans }}$. You might also notice there is actually a second assumption: that the decision to get married is unrelated to education level.

## Part 4

If you made an assumption in part 3, do you think it was reasonable?

### Answer Section

- {{ params.part4.ans1}}
- {{ params.part4.ans2}}

### pl-answer-panel

The husband/wife independence assumption is probably not reasonable, because people often marry another person with a comparable level of education. We will leave it to you to think about whether the second assumption noted in part 3 is reasonable.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)