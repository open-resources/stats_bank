---
title: Husbands and wives, Part II
topic: Introduction to linear regression
author: Larita Kipkeu
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 8.1.1.12
- 8.1.1.14
- 8.1.1.21
- 8.1.1.23
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
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: true
    label: ${slope}= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: true
    label: ${intercept}= $
part5:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: ${correlation}= $
part7:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: ${Wife_{height}}= $
part8:
  type: multiple-choice
  pl-customizations:
    weight: 1
part9:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Husbands and wives, Part II
    params_table: |-
      <table style="width:550px">
      <tr>
      <th></th>
      <th>Estimate</th>
      <th>std Error</th>
      <th>t value</th>
      <th>Pr(>|t|)</th>
      </tr><tr>
      <th>(intercept)</th>
      <td>$45.7542$</td>
      <td>$5.4388$</td>
      <td>$10.2$</td>
      <td>$0.0$</td>
      </tr><tr>
      <th>height_husband</th>
      <td>$0.2462$</td>
      <td>$0.048$</td>
      <td>$4.8$</td>
      <td>$0.0$</td>
      </tr>
      </table>
    params_sample: 145
    params_slope: 0.2462
    params_intercept: 45.7542
    params_intercept_std_error: 5.4388
    params_slope_std_error: 0.048
    params_husband_height1: 64
    params_correlation: 0.135
    params_husband_height2: 73
    params_part1_ans1_value: '$H_0: \beta_1 = 0; H_A: \beta_1 \ne 0$'
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: '$H_0: \beta_1 = 0;  H_A: \beta_1 > 0$'
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: '$H_0: \beta_1 < 0;  H_A: \beta_1 > 0$'
    params_part1_ans3_feedback: Try again please!
    params_part2_ans1_value: The data provide convincing evidence that wives' and
      husbands' heights are positively correlated. The p-value, as reported in the
      table, is smaller than 0.05, so we reject $H_0$.
    params_part2_ans2_value: The data does not provide convincing evidence that wives'
      and husbands' heights are positively correlated. The p-value, as reported in
      the table, is significant, so we fail to reject $H_0$.
    params_part2_ans3_value: There is no sufficient information to make a conclusion.
    params_part2_ans3_feedback: Try again please!
    params_Part2_ans1_feedback: Correct!
    params_Part2_ans2_feedback: Try again please!
    params_part5_ans1_value: 'Slope: For each additional inch in husband''s height,
      the average wife''s height is expected to be an additional (slope value) inches
      on average.'
    params_part5_ans1_feedback: Correct!
    params_part5_ans2_value: 'Slope: For each additional inch in wife''s height, the
      average husbands''s height is expected to be an additional (slope value) inches
      on average.'
    params_part5_ans2_feedback: Try again please!
    params_part5_ans3_value: 'Intercept: Men who are 0 inches tall are expected to
      have wives who are on average, (intercept value) inches tall.'
    params_part5_ans3_feedback: Correct!
    params_part5_ans4_value: 'Intercept: Men who are (intercept value) inches tall
      are expected to have wives who are on average, 0 inches tall.'
    params_part5_ans4_feedback: Try Again!
    params_part5_ans5_value: The intercept here is meaningless, and it serves only
      to adjust the height of the line.
    params_part5_ans5_feedback: Correct!
    params_part8_ans1_value: The prediction based on this regression model is very
      reliable from the given R value.
    params_part8_ans1_feedback: Incorrect!
    params_part8_ans2_value: Since $R^2$ is low, the prediction based on this regression
      model is not very reliable.
    params_part8_ans2_feedback: Correct!
    params_part9_ans1_value: 'No'
    params_part9_ans1_feedback: Incorrect! The husbands' height height within our
      data range.
    params_part9_ans2_value: 'Yes'
    params_part9_ans2_feedback: Correct! The husbands' height height within our data
      range.
---
# {{ params_vars_title }}
The scatter plot below summarizes husbands' and wives' heights in a random sample of ${{ params_sample}}$ married couples in Britain, where both partners' ages are below $65$ years. The summary output of the least squares fit for predicting a wife's height from the husband's height is also provided in the table.
<pl-figure file-name="figure 1.png" type="dynamic" width="450px"></pl-figure>

{{{ params_table }}}

## Part 1

Select the hypotheses.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}

### pl-answer-panel

$H_0$: $\beta_1 = 0$. $H_A$: $\beta_1 \neq 0$.

## Part 2

Is there strong evidence that taller men marry taller women?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}

### pl-answer-panel

The p-value, as reported in the table, is incredibly small
and is smaller than 0.05, so we reject $H_0$.
The data provide convincing evidence that wives' and husbands'
heights are positively correlated

## Part 3

What slope value is multiplied by the wife's height when predicting the wife's height from the husband's height?

hint: Write the equation of the regression line first.

### Answer Section

### pl-answer-panel

## Part 4

What intercept value is used when predicting a wife's height from a husband's height?

hint: Write the equation of the regression line first.

### Answer Section

### pl-answer-panel

## Part 5

Interpret the slope and intercept in the context of the application and select the correct options.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}
- {{ params_part5_ans3_value }}
- {{ params_part5_ans4_value }}
- {{ params_part5_ans5_value }}

### pl-answer-panel

Slope: For each additional inch in husband's height, the average
wife's height is expected to be an additional ${{ params_slope }}$ inches on
average. Intercept: Men who are $0$ inches tall are expected to have wives who are, on average, ${{ params_intercept}}$ inches tall. The intercept here is meaningless, and it serves only to adjust the height of the line

## Part 6

Given that $R^2 = {{params_correlation}}$, what is the correlation of heights in this data set?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

The slope is positive, so $r$ must also be positive.
$r = \sqrt{{params_correlation}}$

## Part 7

You meet a married man from Britain who is ${{ params.husband_height1 }}$ inches. What would you predict his wife's height to be?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

predicted_wife_height = intercept + slope * husband_height

## Part 8

How reliable is this prediction?

### Answer Section

- {{ params_part8_ans1_value }}
- {{ params_part8_ans2_value }}

### pl-answer-panel

Since $R^2$ is low, the prediction based on this
regression model is not very reliable

## Part 9

You meet another married man from Britain who is ${{ params.husband_height2}}$ inches. Would it be wise to use the same linear model to predict his wife's height?

### Answer Section

- {{ params_part9_ans1_value }}
- {{ params_part9_ans2_value }}

### pl-answer-panel

if ${{params.husband_height2}}$ >70 or ${{params.husband_height2}}$ \< 50
No, we should avoid extrapolating
else: yes, data value is within range

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)