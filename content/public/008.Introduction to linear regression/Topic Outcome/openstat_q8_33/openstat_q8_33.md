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
    params:
      vars:
        title: Husbands and wives, Part II
      table: |-
        <table style="width:550px">
        <tr>
        <th></th>
        <th>Estimate</th>
        <th>std Error</th>
        <th>t value</th>
        <th>Pr(>|t|)</th>
        </tr><tr>
        <th>(intercept)</th>
        <td>$42.5146$</td>
        <td>$5.2328$</td>
        <td>$10.1$</td>
        <td>$0.0$</td>
        </tr><tr>
        <th>height_husband</th>
        <td>$0.2943$</td>
        <td>$0.044$</td>
        <td>$4.25$</td>
        <td>$0.0$</td>
        </tr>
        </table>
      sample: 162
      slope: 0.2943
      intercept: 42.5146
      intercept_std_error: 5.2328
      slope_std_error: 0.044
      husband_height1: 65
      correlation: 0.098
      husband_height2: 61
      part1:
        ans1:
          value: '$H_0: \beta_1 = 0; H_A: \beta_1 \ne 0$'
          feedback: Correct!
        ans2:
          value: '$H_0: \beta_1 = 0;  H_A: \beta_1 > 0$'
          feedback: Try again please!
        ans3:
          value: '$H_0: \beta_1 < 0;  H_A: \beta_1 > 0$'
          feedback: Try again please!
      part2:
        ans1:
          value: The data provide convincing evidence that wives' and husbands' heights
            are positively correlated. The p-value, as reported in the table, is smaller
            than 0.05, so we reject $H_0$.
        ans2:
          value: The data does not provide convincing evidence that wives' and husbands'
            heights are positively correlated. The p-value, as reported in the table,
            is significant, so we fail to reject $H_0$.
        ans3:
          value: There is no sufficient information to make a conclusion.
          feedback: Try again please!
      Part2:
        ans1:
          feedback: Correct!
        ans2:
          feedback: Try again please!
      part5:
        ans1:
          value: 'Slope: For each additional inch in husband''s height, the average
            wife''s height is expected to be an additional (slope value) inches on
            average.'
          feedback: Correct!
        ans2:
          value: 'Slope: For each additional inch in wife''s height, the average husbands''s
            height is expected to be an additional (slope value) inches on average.'
          feedback: Try again please!
        ans3:
          value: 'Intercept: Men who are 0 inches tall are expected to have wives
            who are on average, (intercept value) inches tall.'
          feedback: Correct!
        ans4:
          value: 'Intercept: Men who are (intercept value) inches tall are expected
            to have wives who are on average, 0 inches tall.'
          feedback: Try Again!
        ans5:
          value: The intercept here is meaningless, and it serves only to adjust the
            height of the line.
          feedback: Correct!
      part8:
        ans1:
          value: The prediction based on this regression model is very reliable from
            the given R value.
          feedback: Incorrect!
        ans2:
          value: Since $R^2$ is low, the prediction based on this regression model
            is not very reliable.
          feedback: Correct!
      part9:
        ans1:
          value: 'No'
          feedback: Incorrect! The husbands' height height within our data range.
        ans2:
          value: 'Yes'
          feedback: Correct! The husbands' height height within our data range.
---
# {{ params.vars.title }}
The scatter plot below summarizes husbands' and wives' heights in a random sample of ${{ params.sample}}$ married couples in Britain, where both partners' ages are below $65$ years. The summary output of the least squares fit for predicting a wife's height from the husband's height is also provided in the table.
<pl-figure file-name="figure 1.png" type="dynamic" width="450px"></pl-figure>

{{{ params.table }}}

## Part 1

Select the hypotheses.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}

## Part 2

Is there strong evidence that taller men marry taller women?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}

## Part 3

What slope value is multiplied by the wife's height when predicting the wife's height from the husband's height?

hint: Write the equation of the regression line first.

### Answer Section

## Part 4

What intercept value is used when predicting a wife's height from a husband's height?

hint: Write the equation of the regression line first.

### Answer Section

## Part 5

Interpret the slope and intercept in the context of the application and select the correct options.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}
- {{ params.part5.ans5.value }}

## Part 6

Given that $R^2 = {{params.correlation}}$, what is the correlation of heights in this data set?

### Answer Section

Please enter a numeric value in.

## Part 7

You meet a married man from Britain who is ${{ params.husband_height1 }}$ inches. What would you predict his wife's height to be?

### Answer Section

Please enter a numeric value in.

## Part 8

How reliable is this prediction?

### Answer Section

- {{ params.part8.ans1.value }}
- {{ params.part8.ans2.value }}

## Part 9

You meet another married man from Britain who is ${{ params.husband_height2}}$ inches. Would it be wise to use the same linear model to predict his wife's height?

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)