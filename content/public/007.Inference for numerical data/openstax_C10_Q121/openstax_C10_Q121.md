---
title: Cancer Rates in the South
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 10
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.6
- 7.1.1.7
- 7.1.1.8
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
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
        title: Cancer Rates in the South
      table: |-
        <table style="width:550px">
        <tr>
        <th>Southern States</th>
        <th>Year 1</th>
        <th>Year 2</th>
        </tr><tr>
        <th>Alabama</th>
        <td>1990</td>
        <td>2152</td>
        </tr><tr>
        <th>Arkansas</th>
        <td>2150</td>
        <td>2123</td>
        </tr><tr>
        <th>Florida</th>
        <td>15540</td>
        <td>15183</td>
        </tr><tr>
        <th>Georgia</th>
        <td>15050</td>
        <td>13982</td>
        </tr><tr>
        <th>Kentucky</th>
        <td>2630</td>
        <td>2377</td>
        </tr><tr>
        <th>Louisiana</th>
        <td>6190</td>
        <td>7200</td>
        </tr><tr>
        <th>Mississippi</th>
        <td>7090</td>
        <td>7391</td>
        </tr><tr>
        <th>North Carolina</th>
        <td>4680</td>
        <td>4660</td>
        </tr><tr>
        <th>Oklahoma</th>
        <td>3570</td>
        <td>3301</td>
        </tr><tr>
        <th>South Carolina</th>
        <td>3160</td>
        <td>3694</td>
        </tr><tr>
        <th>Tennessee</th>
        <td>3450</td>
        <td>3609</td>
        </tr><tr>
        <th>Texas</th>
        <td>3320</td>
        <td>3300</td>
        </tr><tr>
        <th>Virginia</th>
        <td>6970</td>
        <td>6849</td>
        </tr>
        </table>
      year1: null
      year2: null
      part1:
        ans1:
          value: two means, unknown variances
          feedback: Try again! This is not a test for means
        ans2:
          value: two means, known variances
          feedback: Try again! This is not a test for means
        ans3:
          value: single mean
          feedback: Try again! We have more than one sample present
        ans4:
          value: two proportions
          feedback: Try again!
        ans5:
          value: single proportion
          feedback: Try again! There are no proportions in this scenario
        ans6:
          value: matched or paired samples
          feedback: Good job!
      part2:
        ans1:
          value: '$H_0:\mu_d = 0$ and $H_A: \mu_d > 0$'
          feedback: Good job!
        ans2:
          value: '$H_0: \mu_d = 0$ and $H_A: \mu_d < 0$'
          feedback: Try again!
        ans3:
          value: '$H_0: \mu_d = 0$ and $H_A: \mu_d \ne 0$'
          feedback: Try again!
        ans4:
          value: '$H_0: \mu_1 = \mu_2$ and $H_A: \mu_1 \ne \mu_2$'
          feedback: Try again!
        ans5:
          value: '$H_0: \mu_d > 0$ and $H_A: \mu_d \le 0$'
          feedback: Try again!
        ans6:
          value: '$H_0: \mu_d \le 0$ and $H_A: \mu_d > 0$'
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
          value: Student's t-distribution
          feedback: Good job!
        ans2:
          value: Normal distribution
          feedback: Try again!
        ans3:
          value: Chi-square distribution
          feedback: Try again!
        ans4:
          value: F-distribution
          feedback: Try again!
      alpha: 0.01
      part7:
        ans1:
          value: Reject the null hypothesis because the p-value is less than 0.01
          feedback: Try again!
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than 0.01
          feedback: Good Job
        ans3:
          value: Reject the null hypothesis because the p-value is greater than 0.01
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            0.01
          feedback: Try again
---
# {{ params.vars.title }}
A local cancer support group believes that the estimate for new female breast cancer cases in the south is higher in Year 2 than in Year 1. The group compared the estimates of new female breast cancer cases by southern state in Year 1 and in Year 2. The results are in the table below.

{{{ params.table }}}

<pl-hidden-hints>
<pl-hint hint-name="Table as R code">
<pl-variable-output digits="3" show-mathematica="false" show-matlab="false" show-python="false" show-sympy="false">
  <pl-variable params-name="year1">year1</pl-variable>
  <pl-variable params-name="year2">year2</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

Identify the correct hypothesis test to perform.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Part 2

Identify the null and alternative hypotheses.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}
- {{ params.part2.ans5.value }}
- {{ params.part2.ans6.value }}

## Part 3

What does the random variable represent?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

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

What would your conclusion be at a signifiance level of $\alpha={{ params.alpha }}$ be?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)