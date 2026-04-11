---
title: Scatterplot Linearity
topic: Introduction to linear regression
author: Gavin Kendal-Freedman
source: 12.5
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 8.1.1.1
- 8.1.1.3
- 8.1.1.4
difficulty:
- easy
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
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 5
    allow-blank: false
    allow-fractions: true
    allow-partial-credit: true
    label: $\hat{\beta} = $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $r = $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $p = $
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Scatterplot Linearity
      table: |-
        <table style="width:600px">
        <tr>
        <th>Page number</th>
        <th>Maximum value ($)</th>
        </tr><tr>
        <td>$4$</td>
        <td>$19$</td>
        </tr><tr>
        <td>$14$</td>
        <td>$15$</td>
        </tr><tr>
        <td>$25$</td>
        <td>$19$</td>
        </tr><tr>
        <td>$32$</td>
        <td>$16$</td>
        </tr><tr>
        <td>$43$</td>
        <td>$17$</td>
        </tr><tr>
        <td>$57$</td>
        <td>$15$</td>
        </tr><tr>
        <td>$72$</td>
        <td>$16$</td>
        </tr><tr>
        <td>$85$</td>
        <td>$17$</td>
        </tr><tr>
        <td>$90$</td>
        <td>$15$</td>
        </tr>
        </table>
      pages:
      - 4
      - 14
      - 25
      - 32
      - 43
      - 57
      - 72
      - 85
      - 90
      values:
      - 19
      - 15
      - 19
      - 16
      - 17
      - 15
      - 16
      - 17
      - 15
      part1:
        ans1:
          value: We wonder if the better discounts appear earlier in the book so we
            select page as X and discount as Y.
          feedback: You got it!
        ans2:
          value: We wonder if the better discounts appear earlier in the book so we
            select discount as X and page as Y.
          feedback: Try again please!
        ans3:
          value: We wonder if the better discounts appear later in the book so we
            select page as X and discount as Y.
          feedback: Try again please!
        ans4:
          value: We wonder if the better discounts appear later in the book so we
            select discount as X and page as Y.
          feedback: Try again please!
      significance: 0.05
      part5:
        ans1:
          value: There is a significant linear correlation.
          feedback: Try again!
        ans2:
          value: There is not a significant linear correlation.
          feedback: Good Job
        ans3:
          value: There is a significant quadratic correlation.
          feedback: Try again
        ans4:
          value: There is not a significant quadratic correlation.
          feedback: Try again
        ans5:
          value: There is a significant exponential correlation.
          feedback: Try again
        ans6:
          value: There is not a significant exponential correlation.
          feedback: Try again
      part6:
        ans1:
          value: Yes, because there is a significant correlation.
          feedback: Try again!
        ans2:
          value: No, because there is not a significant correlation.
          feedback: Good Job
        ans3:
          value: Yes, because 50 is in the range of data used to calculate the least
            squares line.
          feedback: Try again
        ans4:
          value: No, because 50 is not in the range of data used to calculate the
            least squares line.
          feedback: Try again
      part7:
        ans1:
          value: No, because 200 is not in the range of data used to calculate the
            least squares line.
          feedback: Good Job
        ans2:
          value: Yes, because there is a significant correlation.
          feedback: Try again!
        ans3:
          value: No, because there is not a significant correlation.
          feedback: Try again!
        ans4:
          value: Yes, because 200 is in the range of data used to calculate the least
            squares line.
          feedback: Try again
---
# {{ params.vars.title }}
The maximum discount value of the Entertainment® card for the “Fine Dining” section, Edition ten, for various pages is given in the table below:

{{{ params.table }}}

<pl-hidden-hints>
<pl-hint hint-name="Table as R code">
<pl-variable-output digits="3" show-mathematica="false" show-matlab="false" show-python="false" show-sympy="false">
  <pl-variable params-name="pages">page</pl-variable>
  <pl-variable params-name="values">maximum_value</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

Decide which variable should be the independent variable and which should be the dependent variable.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Calculate the least-squares line for the data, and provide the equation in matrix form. That is, the answer should be in the form, $\hat{\beta} = [\hat{\beta}\_0, \hat{\beta}\_1]$, where $\hat{y} = \hat{\beta}\_0 + \hat{\beta}\_1 x$. Answer to five decimal places of precision.

A scatteplot has been provided for your convinence:

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

## Part 3

Calculate the correlation coefficient $r$. Answer to four decimal places of precision.

### Answer Section

Please enter a number.

## Part 4

Calculate the p-value. Answer to four decimal places of precision.

### Answer Section

Please enter a number.

## Part 5

Interpert the regressdion line at a signficance level of $\alpha = {{ params.significance }}$.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}
- {{ params.part5.ans5.value }}
- {{ params.part5.ans6.value }}

## Part 6

Is the least squares line valid for page 50? Why or why not?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Part 7

Is the least squares line valid for page 200? Why or why not?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)