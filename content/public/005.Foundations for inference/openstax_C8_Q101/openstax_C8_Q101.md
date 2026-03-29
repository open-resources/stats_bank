---
title: Federal Election Donations
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.7
- 5.1.1.8
- 5.1.1.11
- 5.1.1.12
- 5.1.1.13
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
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $\bar{x}= \$$
part2:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $\text{Margin of Error}= \$$
part3:
  type: matrix-component-input
  pl-customizations:
    allow-fractions: true
    comparison: decdig
    digits: 0
    weight: 1
    allow-blank: false
    label: $\text{CI}=$
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Federal Election Donations
      candidates: 1595
      stdev: 919900
      confidence: 98
      table: |-
        <table style="width:550px">
        <tr>
        <td>$1,112,700.0</td>
        <td>$2,279,400.0</td>
        <td>$103,600.0</td>
        <td>$502,600.0</td>
        <td>$220,300.0</td>
        </tr><tr>
        <td>$836,300.0</td>
        <td>$398,800.0</td>
        <td>$627,800.0</td>
        <td>$1,308,800.0</td>
        <td>$405,400.0</td>
        </tr><tr>
        <td>$774,900.0</td>
        <td>$621,200.0</td>
        <td>$795,900.0</td>
        <td>$1,529,600.0</td>
        <td>$845,700.0</td>
        </tr><tr>
        <td>$5,100.0</td>
        <td>$816,400.0</td>
        <td>$1,588,400.0</td>
        <td>$2,306,400.0</td>
        <td>$462,800.0</td>
        </tr><tr>
        <td>$1,645,400.0</td>
        <td>$1,354,400.0</td>
        <td>$1,212,400.0</td>
        <td>$874,600.0</td>
        <td>$310,100.0</td>
        </tr><tr>
        <td>$1,596,000.0</td>
        <td>$688,300.0</td>
        <td>$1,287,600.0</td>
        <td>$457,000.0</td>
        <td>$1,710,400.0</td>
        </tr><tr>
        <td>$1,729,400.0</td>
        <td>$1,227,400.0</td>
        <td>$1,732,300.0</td>
        <td>$254,800.0</td>
        <td>$606,400.0</td>
        </tr><tr>
        <td>$876,500.0</td>
        <td>$1,079,400.0</td>
        <td>$638,700.0</td>
        <td>$489,100.0</td>
        <td>$311,800.0</td>
        </tr>
        </table>
      part4:
        ans1:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by house candidates is between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Good job!
        ans2:
          value: |-
            <div class="mathjax_ignore">
            We estimate that 98% of all contributions received from all individuals by house candidates are between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Try again please!
        ans3:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by House candidates is less than $(lower_bound).
            </div>
          feedback: Try again please!
        ans4:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by House candidates is greater than $(upper_bound).
            </div>
          feedback: Try again please!
---
# {{ params.vars.title }}
<div class="mathjax_ignore">
The Federal Election Commission collects information about campaign contributions and disbursements for candidates and political committees each election cycle. During a certain campaign season, there were {{ params.candidates }} candidates for the House of Representatives across the United States who received contributions from individuals. The table below shows the total receipts from individuals for a random selection of 40 House candidates rounded to the nearest $100.
</div>

The standard deviation for this data to the nearest hundred is $\sigma = {{ params.stdev }}$.

{{{ params.table }}}

## Part 1

Find the point estimate for the population mean.

### Answer Section

Please enter a numeric value in.

## Part 2

Using {{ params.confidence }}% confidence, calculate the margin of error.

### Answer Section

Please enter a numeric value in.

## Part 3

Create a {{ params.confidence }}% confidence interval for the mean total individual contributions.

### Answer Section

## Part 4

Interpret the confidence interval in the context of the problem.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)