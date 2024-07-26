---
title: GPA and major
topic: Inference for numerical data
author: Larita Kipkeu
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.8
- 7.1.1.17
- 7.1.1.19
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
- LK
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $p_{value}= $
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $size= $
myst:
  substitutions:
    params_vars_title: GPA and major
    params_df_factor: 2
    params_df_residual: 191
    params_meansq_factor: 0.02
    params_meansq_residual: 0.0926
    params_f_value: 0.216
    params_table: |-
      <table style="width:550px">
      <tr>
      <th></th>
      <th>Df</th>
      <th>Sum Sq</th>
      <th>Mean Sq</th>
      <th>F value</th>
      <th>Pr(>F)</th>
      </tr><tr>
      <th>major</th>
      <td>$2$</td>
      <td>$0.04$</td>
      <td>$0.02$</td>
      <td>$0.216$</td>
      <td>$-$</td>
      </tr><tr>
      <th>Residuals</th>
      <td>$191$</td>
      <td>$17.69$</td>
      <td>$0.0926$</td>
      <td>$\quad$</td>
      <td>$\quad$</td>
      </tr>
      </table>
    params_part2_ans1_value: Since p-value $<$ 0.05, we reject $H_0$. The data provides
      convincing evidence of a difference between the average GPAs across three groups
      of majors.
    params_part2_ans1_feedback: Try again! Check your calculations for p-value.
    params_part2_ans2_value: Since p-value $>$ 0.05, fail to reject $H_0$. The data
      do not provide convincing evidence of a difference between the average GPAs
      across three groups of majors.
    params_part2_ans2_feedback: Correct! You can observe this from the p-value you
      calculated in part 1.
    params_part2_ans3_value: The data is insufficient to get the hypothesis test significance.
    params_part2_ans3_feedback: Try calculating the p value since you have sufficient
      data to do this again!
---
# {{ params_vars_title }}
Undergraduate students taking an introductory statistics course at Duke University surveyed their GPA and major. The side-by-side box plots show the distribution of GPA among three groups of majors. Also provided is the ANOVA output.

<pl-figure file-name="figure 1.png" type="dynamic" width="450px"></pl-figure>

{{{ params_table }}}

## Part 1

What is the p value of the hypothesis test?

### Answer Section

### pl-answer-panel

## Part 2

Using $H_0$: Average GPA is the same for all majors. $H_A$: At least one pair of means are different, what is the conclusion of the hypothesis test?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}

### pl-answer-panel

Since p-value $>$ 0.05, fail to reject $H_0$. The data do not provide convincing evidence of a difference between the average GPAs across three groups of majors

## Part 3

How many students answered these questions on the survey, i.e. what is the sample size?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)