---
title: Final Grade Distribution
topic: Inference for categorical data
author: Gavin Kendal-Freedman
source: 11
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.9
- 6.1.1.15
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
- GKF
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part2:
  type: integer-input
  pl-customizations:
    weight: 1
    allow-blank: false
    label: $df = $
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: number-input
  pl-customizations:
    weight: 1
    comparison: decdig
    digits: 2
part5:
  type: number-input
  pl-customizations:
    weight: 1
    comparison: decdig
    digits: 4
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Chi Squared Choices
      class_size: 17
      table: |-
        <table style="width:550px">
        <tr>
        <th>Grade</th>
        <th>Expected Count</th>
        <th>Observed Count</th>
        </tr><tr>
        <th>A</th>
        <td>2</td>
        <td>1</td>
        </tr><tr>
        <th>B</th>
        <td>5</td>
        <td>6</td>
        </tr><tr>
        <th>C</th>
        <td>8</td>
        <td>6</td>
        </tr><tr>
        <th>D</th>
        <td>2</td>
        <td>4</td>
        </tr>
        </table>
      var_array: null
      part1:
        ans1:
          value: A chi-squared goodness of fit test
          feedback: Good Job!
        ans2:
          value: A chi-squared test of independence
          feedback: This is incorrect. A chi-squared test of independence is used
            to determine if there is an association between two categorical variables.
        ans3:
          value: A chi-squared test of homogeneity
          feedback: This is incorrect. A chi-squared test of homogeneity is used to
            determine if different populations have the same distribution of a categorical
            variable.
        ans4:
          value: None of the above
          feedback: This is incorrect.
      part3:
        ans1:
          value: '$H_0$: The distribution of grades follows the predicted distribution.
            $H_A$: The distribution of grades does not follow the predicted distribution.'
          feedback: Good Job!
        ans2:
          value: '$H_0$: The distribution of grades does not follow the predicted
            distribution. $H_A$: The distribution of grades follows the predicted
            distribution.'
          feedback: Try again.
        ans3:
          value: '$H_0$: The distribution of the grades follows a normal distribution.
            $H_A$: The distribution of the grades does not follow a normal distribution.'
          feedback: Try again.
        ans4:
          value: '$H_0$: The distribution of the grades follows a uniform distribution.
            $H_A$: The distribution of the grades does not follow a uniform distribution.'
          feedback: Try again.
      significance_level: 10%
      part6:
        ans1:
          value: Reject the null hypothesis because the p-value is less than the significance
            level
          feedback: Try again.
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than the significance level
          feedback: Good Job!
        ans3:
          value: Reject the null hypothesis because the p-value is greater than the
            significance level
          feedback: Try again.
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            the significance level
          feedback: Try again.
---
# {{ params.vars.title }}
A teacher predicts what the distribution of grades on the final exam will be and what they were in for a course of size {{ params.class_size }} in a table:

{{{ params.table }}}

<pl-hidden-hints>
<pl-hint hint-name="Table as R code">
<pl-variable-output digits="3" show-mathematica="false" show-matlab="false" show-python="false" show-sympy="false">
  <pl-variable params-name="var_array">mat</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

What type of chi-squared test would be most appropriate to use?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Identify the $df$.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

State the null and alternative hypotheses for this test.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

State the $\chi^2$ test statistic.

### Answer Section

Please enter a number to at least two decimal places of precision.

## Part 5

Find the p-value for this test statistic.

### Answer Section

Please enter a number to at least four decimal places of precision.

## Part 6

At a significance level of {{ params.significance_level }}, would you reject or fail to reject the null hypothesis? Why?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)