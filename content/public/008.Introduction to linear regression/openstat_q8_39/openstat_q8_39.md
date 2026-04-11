---
title: Husbands and wives, Part III
topic: Introduction to linear regression
author: Larita Kipkeu
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 8.1.1.1
- 8.1.1.12
- 8.1.1.14
- 8.1.1.17
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
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: ${p_{value}}= $
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
    label: $\text{slope}= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\text{intercept}= $
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
    label: $\text{correlation}= $
part7:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $\text{Wife}_{\text{age}}= $
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
        <td>$2.9364$</td>
        <td>$1.2547$</td>
        <td>$1.7$</td>
        <td>$0.0909$</td>
        </tr><tr>
        <th>age_husband</th>
        <td>$0.8223$</td>
        <td>$0.0388$</td>
        <td>$37.56$</td>
        <td>$0.0$</td>
        </tr>
        </table>
      sample: 179
      slope: 0.8223
      intercept: 2.9364
      intercept_std_error: 1.2547
      slope_std_error: 0.0388
      husband_age1: 55
      correlation: 0.942
      husband_age2: 37
      part2:
        ans1:
          value: Since p-value < 0.05, the data provide strong evidence that the average
            difference between husbands' and wives' ages has actually changed over
            time.
          feedback: Correct! You can observe this from the p-value.
        ans2:
          value: Since p-value > 0.05, the data does not provide convincing evidence
            that the average difference between husbands' and wives' ages has actually
            changed over time.
          feedback: Try again! Check your calculations for p-value.
        ans3:
          value: The data is insufficient to get the hypothesis test significance.
          feedback: There is sufficient data!
      part5:
        ans1:
          value: 'Slope: For each additional year in a husband''s age, the average
            wife''s age is expected to be an additional (slope value) years on average.'
          feedback: Correct!
        ans2:
          value: 'Slope: For each additional year in a wife''s age, the average husband''s
            age is expected to be an additional (slope value) years on average.'
          feedback: Try again please!
        ans3:
          value: 'Intercept: Men who are 0 years old are expected to have wives who
            are on average, (intercept value) years old.'
          feedback: Correct!
        ans4:
          value: wives' ages tend to be lower for later ages, suggesting the average
            gap of husband and wife age is larger for older people.
          feedback: Correct!
        ans5:
          value: The intercept here is meaningless, and it serves only to adjust the
            age of the line.
          feedback: Correct!
      part8:
        ans1:
          value: The prediction based on this regression model is very reliable since
            the given $R^2$ value is pretty high.
          feedback: Correct!
        ans2:
          value: Since $R^2$ is low, the prediction based on this regression model
            is not very reliable.
          feedback: Incorrect!
      part9:
        ans1:
          value: 'No'
          feedback: Incorrect! The husbands' age is within our data range.
        ans2:
          value: 'Yes'
          feedback: Correct! The husbands' age is within our data range.
---
# {{ params.vars.title }}
The scatter plot displays the relationship between husbands' and wives' ages in a random sample of ${{ params.sample }}$ married couples in Britain, where both partners' ages are below $65$ years. Given below is summary output of the least squares fit for predicting wife's age from husband's age.

<pl-figure file-name="figure1.png" type="dynamic" width="450px"></pl-figure>

{{{ params.table }}}

## Part 1

We might wonder, is the age difference between husbands and wives consistent across ages? If this were the case, then the slope parameter would be $\beta_1 = 1$. Use the information above to evaluate p-value.

### Answer Section

Please enter a numeric value in.

## Part 2

From your analysis above is there strong evidence to suggest that the difference in husband and wife ages differs for different ages?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}

## Part 3

What slope value is multiplied by wife's age when predicting wife's age from husband's age?

Hint: Write the equation of the regression line first.

## Part 4

What intercept value is used when predicting wife's age from husband's age?

Hint: Write the equation of the regression line first.

### Answer Section

Please enter a numeric value in.

## Part 5

Interpret the slope and intercept in the context of the application and select the correct options.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}
- {{ params.part5.ans5.value }}

## Part 6

Given that $R^2 = {{ params.correlation }}$, what is the correlation of ages in this data set?

### Answer Section

Please enter a numeric value in.

## Part 7

You meet a married man from Britain who is ${{ params.husband_age1 }}$ years. What would you predict his wife's age to be?

## Part 8

How reliable is this prediction?

### Answer Section

- {{ params.part8.ans1.value }}
- {{ params.part8.ans2.value }}

## Part 9

You meet another married man from Britain who is ${{ params.husband_age2 }}$ years. Would it be wise to use the same linear model to predict his wife's age?

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)