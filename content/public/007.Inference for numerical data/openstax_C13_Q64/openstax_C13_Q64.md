---
title: Lab Rat Weight
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 13.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
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
    label: $df_{num} = $
part3:
  type: integer-input
  pl-customizations:
    weight: 1
    allow-blank: false
    label: $df_{den} = $
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{test statistic} = $
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $p = $
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Lab Rat Weight
      table: |-
        <table style="width:550px">
        <tr>
        <th>Linda's Rats</th>
        <th>Tuan's Rats</th>
        <th>Javier's Rats</th>
        </tr><tr>
        <th>38.4</th>
        <td>38.8</td>
        <td>44.8</td>
        </tr><tr>
        <th>41.1</th>
        <td>42.4</td>
        <td>52.1</td>
        </tr><tr>
        <th>39.0</th>
        <td>47.6</td>
        <td>48.7</td>
        </tr><tr>
        <th>43.7</th>
        <td>45.0</td>
        <td>46.5</td>
        </tr><tr>
        <th>39.6</th>
        <td>41.9</td>
        <td>58.7</td>
        </tr><tr>
        <th>41.1</th>
        <td>43.6</td>
        <td>40.4</td>
        </tr><tr>
        <th>48.9</th>
        <td>39.3</td>
        <td>50.9</td>
        </tr><tr>
        <th>41.0</th>
        <td>42.7</td>
        <td>51.3</td>
        </tr>
        </table>
      linda_sample: null
      tuan_sample: null
      javier_sample: null
      significance_level: 1
      sample_size: 8
      part1:
        ans1:
          value: '$H_0: \mu_L = \mu_T = \mu_J$ and $H_A: \exists i\ne j: \mu_i \ne
            \mu_j$'
          feedback: Good job!
        ans2:
          value: '$H_0: \mu_L = \mu_T = \mu_J$ and $H_A: \forall i\ne j: \mu_i \ne
            \mu_j$'
          feedback: Try again!
        ans3:
          value: '$H_0: \mu_L = \mu_T = \mu_J$ and $H_A: \mu_L \ne \mu_J$'
          feedback: Try again!
        ans4:
          value: '$H_0: \mu_L = \mu_T = \mu_J$ and $H_A: \mu_L \ne \mu_T$'
          feedback: Try again!
        ans5:
          value: '$H_0: \exists i\ne j: \mu_i \ne \mu_j$ and $H_A: \mu_L = \mu_T =
            \mu_J$'
          feedback: Try again!
        ans6:
          value: '$H_0: \forall i\ne j: \mu_i \ne \mu_j$ and $H_A: \mu_L = \mu_T =
            \mu_J$'
          feedback: Try again!
      part3:
        ans1:
          value: The random variable is the mean difference in cancer rate across
            years.
          feedback: Good job!
        ans2:
          value: The random variable is the difference in the cancer rate across years.
          feedback: Try again!
        ans3:
          value: The random variable is the true difference in cancer rate across
            years.
          feedback: Try again!
        ans4:
          value: The random variable is the difference in variance of cancer rate
            across years.
          feedback: Try again!
      part4:
        ans1:
          value: F-distribution
          feedback: Good job!
        ans2:
          value: Student's t-distribution
          feedback: Try again!
        ans3:
          value: Normal distribution
          feedback: Try again!
        ans4:
          value: Chi-square distribution
          feedback: Try again!
      part7:
        ans1:
          value: Reject the null hypothesis because the p-value is less than 0.01
          feedback: Good Job
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than 0.01
          feedback: Try again!
        ans3:
          value: Reject the null hypothesis because the p-value is greater than 0.01
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            0.01
          feedback: Try again
---
# {{ params.vars.title }}
Three students, Linda, Tuan, and Javier, are given {{ params.sample_size }} laboratory rats each for a nutritional experiment. Each rat's weight is recorded in grams. Linda feeds her rats Formula A, Tuan feeds his rats Formula B, and Javier feeds his rats Formula C. At the end of a specified time period, each rat is weighed again, and the net gain in grams is recorded. Using a significance level of {{ params.significance_level }}%, test the hypothesis that the three formulas produce the same mean weight gain.

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
  <pl-variable params-name="linda_sample">linda_rats</pl-variable>
  <pl-variable params-name="tuan_sample">tuan_rats</pl-variable>
  <pl-variable params-name="javier_sample">javier_rats</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

Identify the null and alternative hypotheses.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Part 2

Identify the degrees of freedom for the numerator of the test statistic.

### Answer Section

Please enter an integer.

## Part 3

Identify the degrees of freedom for the denominator of the test statistic.

### Answer Section

Please enter an integer.

## Part 4

Identify the distribution to use for the test.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

What is the test statistic? Please provide at least 4 decimal places of precision.

### Answer Section

Please enter a number.

## Part 6

Calculate the p-value for this test statistic. Please provide at least 4 decimal places of precision.

### Answer Section

Please enter a number.

## Part 7

What would your conclusion be?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)