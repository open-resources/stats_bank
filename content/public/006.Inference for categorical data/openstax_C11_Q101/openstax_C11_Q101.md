---
title: Personality Types
topic: Inference for categorical data
author: Gavin Kendal-Freedman
source: 11.4
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.15
- 6.1.1.17
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
    label: $\chi^2 \text{ test statistic} =$
part5:
  type: number-input
  pl-customizations:
    weight: 1
    comparison: decdig
    digits: 4
    label: $p\text{-value} =$
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Personality Types
      significance: 1%
      table: |-
        <table style="width:500px">
        <tr>
        <th></th>
        <th>Open</th>
        <th>Conscientious</th>
        <th>Extrovert</th>
        <th>Agreeable</th>
        <th>Neurotic</th>
        </tr><tr>
        <th>Business Majors</th>
        <td>$41$</td>
        <td>$52$</td>
        <td>$46$</td>
        <td>$61$</td>
        <td>$58$</td>
        </tr><tr>
        <th>Social Science Majors</th>
        <td>$72$</td>
        <td>$75$</td>
        <td>$63$</td>
        <td>$80$</td>
        <td>$65$</td>
        </tr>
        </table>
      numbers: null
      part1:
        ans1:
          value: '$H_0$: The distribution for personality types is the same for both
            majors. $H_A$: The distribution for personality types is not the same
            for both majors.'
          feedback: Good Job!
        ans2:
          value: '$H_0$: The distribution for personality types is not the same for
            both majors. $H_A$: The distribution for personality types is the same
            for both majors.'
          feedback: Try Again!
        ans3:
          value: '$H_0$: The distribution for personality types are normally distributed
            for both majors. $H_A$: The distributions are not normally distributed
            for both majors.'
          feedback: Try Again!
        ans4:
          value: '$H_0$: The distribution for personality types are uniformly distributed
            for both majors. $H_A$: The distributions are not uniformly distributed
            for both majors.'
          feedback: Try Again!
      part3:
        ans1:
          value: $X \sim \chi^2_3$
          feedback: Good Job!
        ans2:
          value: $X \sim \chi^2_4$
          feedback: Try Again!
        ans3:
          value: $X \sim \chi^2_16$
          feedback: Try Again!
        ans4:
          value: $X \sim \chi^2_20$
          feedback: Try Again!
        ans5:
          value: $X \sim N(0,1)$
          feedback: Try Again!
      part6:
        ans1:
          value: The conclusion would be to reject the null hypothesis because the
            p-value is less than 0.01.
          feedback: Try Again!
        ans2:
          value: The conclusion would be to fail to reject the null hypothesis because
            the p-value is greater than 0.01.
          feedback: Good Job!
        ans3:
          value: The conclusion would be to reject the null hypothesis because the
            p-value is greater than 0.01.
          feedback: Try Again!
        ans4:
          value: The conclusion would be to fail to reject the null hypothesis because
            the p-value is less than 0.01.
          feedback: Try Again!
---
# {{ params.vars.title }}
A psychologist is interested in testing whether there is a difference in the distribution of personality types for business majors and social science majors. The results of the study are shown in a table below. Conduct a test of homogeneity at a {{ params.significance }} level of significance.

<style>
table:not([class]) {
  tr {
    border-bottom: 1px solid #ddd;
  }
  tr:hover {background-color: #D6EEEE;}
  th, td {
      padding: 10px;
      border-right: 2px solid #333; /* Vertical divider */
  }

  /* Remove the last column's right border */
  th:last-child, td:last-child {
      border-right: none;
  }
}
</style>

{{{ params.table }}}

<pl-hidden-hints>
<pl-hint hint-name="Table as R code">
<pl-variable-output digits="3" show-mathematica="false" show-matlab="false" show-python="false" show-sympy="false">
  <pl-variable params-name="numbers">mat</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

What is the null and alternative hypothesis?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Identify the degrees of freedom for the chi-squared test.

### Answer Section

Please enter an integer.

## Part 3

Identify the distribution to use for the test.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}
- {{ params.part3.ans5.value }}

## Part 4

Calculate the $\chi^2$ test statistic.

### Answer Section

Please enter a number to at least two decimal places of precision.

## Part 5

Find the p-value for this test statistic.

### Answer Section

Please enter a number to at least four decimal places of precision.

## Part 6

What would your conclusion be and why?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)